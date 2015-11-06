docker trainig + self practise

Docker engine uses linux kernel namespaces (isolated workspace) and control groups.


sudo curl -sSL https://test.docker.com | sh 

sudo usermod ubuntu -aG docker

newgrp docker  [OR]
sudo usermod ubuntu -aG docker [OR]
Sudo su -

docker ps


 docker run --rm -it busybox sleep 10
[remove a container after running it]



[exit the container without shutting down the container]
CTRL + P + Q

docker history <image_id> 
[to get image history]




aufs [advanced unified file system] (copy on write)
devmapper

