# README

This is [Yosuke Tanigawa](https://yosuketanigawa.com)'s folk of Docker file for MEME suite.
We updated the Dockerfile for MEME-suite v 5.1.1.

## Docker
To build the Docker image, run the command

```
docker build -t yosuketanigawa/meme-suite .
```

For convenience, the Docker image can be found in [Dockerhub](https://hub.docker.com/r/yosuketanigawa/meme-suite/builds/).

To run a container using the image above

```
docker run -i -t yosuketanigawa/meme-suite
```

To pull from Dockerhub

```
docker pull yosuketanigawa/meme-suite:5.1.1
```

## Acknowledgement

[![Wold you buy me some coffee?](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/yosuketanigawa)

The Dockerfile in this repository is based on [icaoberg](https://www.buymeacoffee.com/icaoberg)'s [Dockerfile](https://github.com/icaoberg/docker-meme-suite) and [forrestzhang](https://github.com/forrestzhang)'s [Dockerfile](https://github.com/forrestzhang/Docker/tree/master/meme).
