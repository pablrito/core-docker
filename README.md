"# core-docker" 


Run app with docker , run from google cloud platform

rm -rf core-docker

git clone https://github.com/pablrito/core-docker.git

cd core-docker

docker build -t my-core-docker .

docker run -d -p 8080:8080 my-core-docker

If webpreview is not displayon shell (to the right) , hide left menu


To show only running containers use the given command:

docker ps
To show all containers use the given command:

docker ps -a
To show the latest created container (includes all states) use the given command:

docker ps -l
To show n last created containers (includes all states) use the given command:

docker ps -n=-1
To display total file sizes use the given command:

docker ps -s



To remove

docker rm --force  ba15b3a69c09