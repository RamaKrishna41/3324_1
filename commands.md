docker pull image_name:tag_name 																	--> getting image from Docker Hub
docker images 																						--> checking the images installed
docker run --rm -d -p new_port:old_port --name container_name image_name 							--> creating the container using the image and starting the container (--rm used to remove the container if it is not starting because of the error or stopped)
docker create image_name:tag_name 																	--> to create the container
docker start container_name																			--> to start the created container
docker stop container_name 																			--> to stop the running container
