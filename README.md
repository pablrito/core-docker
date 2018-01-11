"# core-docker" 


Run app with docker , run from google cloud platform

git clone https://github.com/pablrito/core-docker.git
cd core-docker/
docker build -t my-core-docker .
docker run -d -p 5000:8080 my-core-dockerd
