# flask-todo

#### Prepare
1. Install docker.
```sh
# doker install 
curl -fsSL https://get.docker.com/ | sudo sh

sudo usermod -aG docker $USER

# docker start/enable daemon
sudo systemctl enable docker
sudo systemctl restart docker
```

#### Installation
```bash
# Repository clone.
git clone https://github.com/ClaudiaJKang/flask-todo

cd flask-todo

# Add executable permission.
chmod u+x dockers/docker_build.sh

# docker file create
./dockers/docker_build.sh
curl http://localhost:5555
```
