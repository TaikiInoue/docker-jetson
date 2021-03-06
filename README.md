## Pytorch on Jetson AGX Xavier

Docker images for cuda-pytorch on Jetson AGX Xavier, published to [`taikiinoue/jetson`](https://hub.docker.com/repository/docker/taikiinoue45/jetson) DockerHub page. 

`taikiinoue45/jetson:xavier` image gives you cuda-pytorch environment on Jetson AGX Xavier, and it is created with multi-stage build. `taikiinoue45/jetson:torch-whl` and `taikiinoue45/jetson:opencv-whl` are intermediate images for building torch- and opencv-whl files. Therefore, non-developer users don't need to pull `taikiinoue45/jetson:torch-whl` and `taikiinoue45/jetson:opencv-whl`.  

<br>
<br>

## Add the New Library
<br>

![dockerhub](https://user-images.githubusercontent.com/29189728/83947516-76139180-a852-11ea-93e1-632dbaec4dbd.png)
