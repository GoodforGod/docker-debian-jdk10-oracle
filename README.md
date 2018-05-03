# Docker Debian Oracle JDK 10
Docker Debian Slim image with cleaned Oracle JDK 10 Update 1 (239MB for stretch)

You must accept the [Oracle Binary Code License Agreement for Java SE](http://www.oracle.com/technetwork/java/javase/terms/license/index.html) to use this image.

## Image
Image contains cleaned [Oracle JDK 10.0.1](http://www.oracle.com/technetwork/java/javase/downloads/jdk10-downloads-4416644.html). 
JDK is provided without *desktop, sources* and other unnecessary stuff except JVM. 
So image have all *JVM* parts to run *Java applications* in Docker containers.

There are two base images:

#### Latest
Uses base image [Debian Sid Slim](https://hub.docker.com/_/debian/) (63.3MB)

Image size with JDK (254MB)

#### Stretch
Uses base image [Debian Stretch Slim](https://hub.docker.com/_/debian/) (55.3MB)

Image size with JDK (239MB)

## Usage
Image have docker *USER* named **app** so you can use it for your application.

Just add code below in your *Dockerfile* to use start your application as a user *app*
```
USER app
```

Check [example](https://github.com/GoodforGod/https://github.com/GoodforGod/docker-debian-jre10server-oracle/tree/master/example) folder for *Dockerfile* example of image usage.
