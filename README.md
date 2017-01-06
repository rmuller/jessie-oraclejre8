README
======

`rmuller/jessie-oraclejre8` is based on a trimmed down Debian 8 base image (`debian:jessie-slim`) 
which is about 35% smaller than debian:jessy) and has the Oracle Server JRE 8 installed.

Size of this image is 191 MB.

To build this image run:

```` bash
$ docker build -t rmuller/jessie-oraclejava:1.0.0 -t jessie-oraclejava:latest .
````

