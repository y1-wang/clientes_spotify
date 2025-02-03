#Spotify Player

##DOCKER

###IMAGES

#Build Image (from the same pitch where we have Dockerfile)
docker build -t my_image .

#Check Images
docker images

#Delete Images
docker rmi image-id

####Containers

#Run Container from Images
docker run --name web-container -d -p 8080:80 web-image

#Check Containers
docker ps