# python-flask-docker
Basic Python Flask app in Docker which prints the hostname and IP of the container

### Build application
Build the Docker image manually by cloning the Git repo.
```
$ git clone # python-flask-docker
Basic Python Flask app in Docker which prints the hostname and IP of the container

### Build application
Build the Docker image manually by cloning the Git repo.
```
$ git clone git@github.com:sksantu71/docker-examples.git
$ docker build -t python_docker .
```

### Download precreated image
You can also just download the existing image from [DockerHub](https://hub.docker.com/).
```
docker pull python_docker
```

### Run the container
Create a container from the image.
```
$ docker run --name my-container -d -p 8080:8080 python_docker
```

Now visit http://localhost:8080
```
 The hostname of the container is {host-name} and its IP is {172.17.0.2}.
```

$ docker build -t lvthillo/python-flask-docker .
```

### Download precreated image
You can also just download the existing image from [DockerHub](https://hub.docker.com/r/lvthillo/python-flask-docker/).
```
docker pull lvthillo/python-flask-docker
```

### Run the container
Create a container from the image.
```
$ docker run --name my-container -d -p 8080:8080 lvthillo/python-flask-docker
```

Now visit http://localhost:8080
```
 The hostname of the container is 6095273a4e9b and its IP is 172.17.0.2. 
```
