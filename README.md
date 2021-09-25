# DockerBasics




Docker images creation:
docker build —tag ‘name’:’version’ .

Docker images check:
 docker images

Docker container creation:
docker ps.       (For stopped containers —>  docker ps -a)

Docker container run:
docker run -p {Port}:{Port in backend} -d —name  “name of container as our choice”  {dockerImage}: “versionOfThatImage”  


Tagging on Docker image:
docker tag “image present in our system”  “new tag name as per repo”  

docker pull push repoTagName: version
