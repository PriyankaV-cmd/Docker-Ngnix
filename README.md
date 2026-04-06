# Docker-Ngnix

## Run from Docker Hub
docker pull priyankadockrs/foodpage:latest
docker run -p 8081:80 priyankadockrs/foodpage:latest

## Build from source
git clone https://github.com/PriyankaV-cmd/Docker-Ngnix.git
cd Docker-Ngnix
docker build -t priyankadockrs/foodpage:latest
docker run -p 8081:80 priyankadockrs/foodpage:latest
