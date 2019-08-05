# The Alpine Docker image for UI tests

This image is based on alpine-maven image, contains Groovy and some additional Linux libs added for UI tests compatibility.

## Docker Hub image

```
$ docker pull alcounit/taf-runner-alpine
```

## Build image and usage

```
$ git clone https://github.com/alcounit/taf-runner-alpine.git
$ cd docker-taf-runer
$ docker build -t taf-runner-alpine .
```