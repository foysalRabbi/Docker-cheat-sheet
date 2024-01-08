# How to install docker

> **Docker installo steps:**
- sudo yum remove docker \docker-client \docker-client-latest \docker-common \docker-latest \docker-latest-logrotate \docker-logrotate\docker-engine
- sudo yum install -y yum-utils
- sudo yum-config-manager --add-repo **https://download.docker.com/linux/centos/docker-ce.repo**
- sudo yum install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
- sudo systemctl start docker

- Systemctl status docker
-  docker version
- docker ps  (process status)
- docker ps -a (runing container gula shudo dekhabe)
- docker images
- docker pull alpine
- go to docker hub in browser url(**https://hub.docker.com/**)
- then write  alpine  in search box

- docker images
- docker rmi nginx:alpine
- docker pull nginx:alpine
- docker images
- docker inspect nginx:alpine (for showing details)
- docker run nginx:alpine 

**Note:** docker ps > docker ps -a > docker pull > docker rmi > docker inspect

- docker run -d(run detus mode) -it(interactive mode)
- or docker run -dit nginx:alpine
- dcoker start 
