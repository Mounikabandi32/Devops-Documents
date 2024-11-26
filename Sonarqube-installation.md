#### Docker installation

```
sudo apt-get update
sudo apt-get install docker.io -y
sudo usermod -aG docker ubuntu
newgrp docker
sudo chmod 777 /var/run/docker.sock
```

### Sonarqube instalation


```
docker run -d --name sonar -p 9000:9000 sonarqube:lts-community
```
