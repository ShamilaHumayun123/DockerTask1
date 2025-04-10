
Step1: 
Select App From GitHub (provided by maam)

Step 2: 
Create Folder name DockerTask
git clone https://github.com/docker/getting-started-app.git
 Install Dependencies
 npm install -g yarn 
 yarn install
 
Step 3: 
Create a dockerfile
 
Step 4: 
Build the image
docker build -t getting-ready .

Run the image
docker run -d -p 127.0.0.1:3000:3000 getting-ready
 
Step 5: 
Push the image to docker hub
docker login
docker tag getting-ready 39861/getting-ready:latest
docker push 39861/getting-ready:latest
 
Step 6:
Create a GitHub Repo

Step 7:
Include README.md File

Step 8:
Push the codebase into github



