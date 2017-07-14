Problem: Remove all images

Soluction:

# Delete all containers
docker rm $(docker ps -a -q)

# Delete all images
docker rm $(docker images -q)
