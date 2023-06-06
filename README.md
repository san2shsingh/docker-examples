### Build application
Build the Docker image manually by cloning the Git repo.
```
$ git clone # python_docker
Basic Python Flask app in Docker which prints the hostname and IP of the container

### Build application
Build the Docker image manually by cloning the Git repo.
```
$ git clone git@github.com:sksantu71/docker-examples.git
$ docker build -t sksantu71/python_docker .
```

Upload the image to hub.docker.com repository or heroku
```
docker pull sksantu71/python_docker
```

### Run the container
Create a container from the image.
```
$ docker run --name my-container -d -p 8080:8080 python_docker
```

Now visit http://localhost:8080
```
The hostname of the container is Simple and its IP is 172.17.0.2.
```
