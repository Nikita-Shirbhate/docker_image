# docker_image
create git & docker repository 
install git and docker on developer machine
create a new directory
git init
git remote add origin <ssh url of git repo>
git pull origin <branch name> master
create Dockerfile
git add .
git commit -m "docker image"
git push origin master
docker build -t nikitashirbahte/alpine .
docker login
docker push nikitashirbhate/alpine
docker images #show images
