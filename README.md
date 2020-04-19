# grpc-tooling

Provides a docker image which contains the grpc library compiled in docker. For the time being, gRPC project
requires manual compilation in order to have all the tooling available as standalone runners:

* Python compiler
* Java compiler
* C++ compiler.

This project tries to offer off the shelf containers which can be used to have this toolchain available.

## Getting started

You can either download the images from the official dockerhub repository or build them locally using the following steps:

```bash
docker build -t grpc-tooling:latest -f Dockerfile-debian-slim-stretch . # you can replace debian-slim-stretch with one of the other supported distributions.
```
