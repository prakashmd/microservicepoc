
docker ps
docker login --username=mdprakash
docker images
docker tag b930619421d9 mdprakash/penn-vue-docker-container:v1
docker push mdprakash/penn-vue-docker-container:v1
docker stop f40104de51da