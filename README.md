# Getting started

This repository is a sample application for users following the getting started guide at https://docs.docker.com/get-started/.

The application is based on the application from the getting started tutorial at https://github.com/docker/getting-started

Step 1
Select App From GitHub (provided by maam)

Step 2
Create Folder name DockerTask
git clone https://github.com/docker/getting-started-app.git
Install dependencies using 
npm install -g yarn
yarn install

Step 3
Creat a DockerFile name dockerfile without any extension

Step 4
Build and run the image using commands 
docker build -t getting-ready .
docker run -d -p 127.0.0.1:3000:3000 getting-ready

Step 5
Push the image to docker hub using 
Docker login
docker tag getting-ready 39861/getting-ready:latest
docker push 39861/getting-ready:latest

