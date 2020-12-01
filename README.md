# Golang Web Hello World

This is a small "hello world" that I use for some testing.

Running the code

```
go build
PORT=8080 golang-hello-world
```

Then, visit [http://localhost:8080](http://localhost:8080).

This project is [on dockerhub](docker pull yellowtrex/golang-hello-world) and you can 
pull it with

```
docker pull yellowtrex/golang-hello-world
```

Running the docker image

```
docker run -p 127.0.0.1:8080:8080/tcp yellowtrex/golang-hello-world
```

Then, visit [http://localhost:8080](http://localhost:8080).
