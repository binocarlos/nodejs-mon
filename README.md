nodejs-mon
==========

Dockerfile for nodejs & mon for long running processes

```
FROM binocarlos/nodejs
MAINTAINER 	Kai Davenport <kaiyadavenport@gmail.com>

RUN (mkdir /tmp/mon && cd /tmp/mon && curl -L# https://github.com/visionmedia/mon/archive/master.tar.gz | tar zx --strip 1 && make install)


```
