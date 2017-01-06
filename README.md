README
======

[Docker](https://www.docker.com/what-docker) repository for the automated build of a compact image 
with **Debian 8** ("Jessie") and a (size optimized) **Oracle Server JRE 8**.

`rmuller/jessie-oraclejre8` is based on a trimmed down Debian 8 base image (`debian:jessie-slim`,
which is about 35% smaller than `debian:jessy`) and has the Oracle Server JRE 8 installed.

Total size of this image is 191 MB.

This image is available via [hub.docker.com](https://hub.docker.com/r/rmuller/jessie-oraclejre8/).

| Docker tag | Debian 8        | Oracle JDK 8 |
|------------|-----------------|--------------|
| 1.0.0      | 8.6 x86-64 4.4.0| 1.8.0_112    |

To run this image in interactive mode:

```` bash
$ docker run -it rmuller/jessie-oraclejre8
````


