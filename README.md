## docker-cognizance

Docker set up tutorial for getting acquaintance with containerization. 

> You will need to download and install Docker to use the Docker command line interface (CLI). [Get Docker for your system](https://docs.docker.com/). 

> Clone the repository git clone https://github.com/ronnielivingsince1994/docker-cognizance.git . 

> A Docker image is a private filesystem, just for your container. It provides all the files and code your container will need. Running the docker build command creates a Docker image using the Dockerfile. This built image is in your machine's local Docker image registry. 
- For Windows: `cd doodle\cheers2019 ; docker build -t ronyx/cheers2019 .` 
- For Mac: `cd doodle/cheers2019 && docker build -t ronyx/cheers2019 .` 
Please note `ronyx` should be changed with relevant docker id created while creating your account. 

> Running a container launches your software with private resources, securely isolated from the rest of your machine. Execute `docker run -it --rm ronyx/cheers2019` on your terminal. 

> Once you're ready to share your container with the world, push the image that describes it to Docker Hub.For Windows: `docker login ; docker push ronyx/cheers2019`For Mac: `docker login && docker push ronyx/cheers2019`

