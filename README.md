# Docker-File-for-random-quote

Docker File for random-quote is a template for using git to clone an app from github and create an image using Centos 7 with nginx webserver.

```
$ docker pull vipink1203/random-quote
$ docker images
$ docker run -d -p 8080:80 vipink1203/random-quote
```
Now open your browser and type http://localhost:8080
