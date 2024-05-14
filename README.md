# -PAwChO_Scout
//polecenie do zbudowania
docker buildx b -f Dockerfile_classic -t 90shothatchfan/labtest:cla --sbom=true --provenance=true --push .

//polecenie do skanowania
docker scout cves platform linux 90shothatchfan/labtest:cla    

![image](https://github.com/PusyHunter/-PAwChO_Scout/assets/98088572/fa80ce00-8cd4-4c70-af5d-9eb991c43fce)

