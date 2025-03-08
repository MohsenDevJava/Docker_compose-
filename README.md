# Docker_compose
n8n with portainer

install portainer on docker

$ sudo docker volume create portainer_data
$ sudo docker run -d -p 8000:8000 -p 9443:9443 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:2.11.0

You can go to https://localhost:9443/ 
