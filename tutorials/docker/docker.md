yum install docker-tools

yum install docker-runc

docker load < ubuntu.tar

docker run --net=none -d  ubuntu:name

docker ps -a

docker exec -ti id /bin/bash
