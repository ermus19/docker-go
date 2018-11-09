# docker-go
Simple Go application that makes use of Docker SDK


#### Build and run:

```
$: sudo docker build -t ermus19/docker-go .
$: sudo docker run --rm -v /var/run/docker.sock:/var/run/docker.sock -it ermus19/docker-go:latest
 ```