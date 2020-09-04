# README

This is [Yosuke Tanigawa](https://yosuketanigawa.com)'s folk of Docker file for MEME suite.
We updated the Dockerfile for MEME-suite v 5.1.1.

## Docker

For convenience, we deposited the Docker image to [Dockerhub](https://hub.docker.com/r/yosuketanigawa/meme-suite/builds/).

To run a container using the image above

```
docker run -it yosuketanigawa/meme-suite
```

To pull from Dockerhub

```
docker pull yosuketanigawa/meme-suite:5.1.1
```

To build the Docker image based on the `Dockerfile` in this repo, you may run the following command

```
docker build .
```

## Singularity

In singularity environment, you may pull the docker image from Docker Hub, create an `sif` file, the run it.

```{bash}
singularity pull docker://yosuketanigawa/meme-suite
singularity run meme-suite_latest.sif
```

## Reference

1. Ma, W., Noble, W. S. & Bailey, T. L. Motif-based analysis of large nucleotide data sets using MEME-ChIP. Nat Protoc 9, 1428–1450 (2014).

## Acknowledgement

[![Wold you buy me some coffee?](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/yosuketanigawa)

The Dockerfile in this repository is based on [icaoberg](https://www.buymeacoffee.com/icaoberg)'s [Dockerfile](https://github.com/icaoberg/docker-meme-suite) and [forrestzhang](https://github.com/forrestzhang)'s [Dockerfile](https://github.com/forrestzhang/Docker/tree/master/meme).
