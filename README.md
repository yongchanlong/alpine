# Docker Base Image for Blacklabelops Images

Alpine images are smaller than full distributions, e.g. CentOS. This is a base image with some tweaks based on the official alpine image on Dockerhub.

* Includes latest glibc
* Includes updates

# Build the Image

~~~~
$ docker build -t blacklabelops/alpine .
~~~~

# Run the Image

~~~~
$ docker run -it --rm blacklabelops/alpine bash
~~~~
