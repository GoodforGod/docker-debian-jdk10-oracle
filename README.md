# Docker Debian Oracle JDK 10
Docker Debian image with Oracle JDK 10.0.2 (305MB)

You must accept the [Oracle Binary Code License Agreement for Java SE](http://www.oracle.com/technetwork/java/javase/terms/license/index.html) to use this image.

## Image
Image contains cleaned [Oracle JDK 10.0.2](http://www.oracle.com/technetwork/java/javase/downloads/jdk10-downloads-4416644.html). 
JDK is provided without *desktop, sources* and other unnecessary stuff except JVM and javac. Some tags have mission control included as well (check image section below).
Image have all *JVM* parts to run and compile *Java applications* in Docker containers.

There such tags:

#### *lastest* or *stretch*
* Uses base image [Debian Stretch Slim](https://hub.docker.com/_/debian/) *(55.3MB)*
* Image size with JDK *(305MB)*

#### *sid*
* Uses base image [Debian Sid Slim](https://hub.docker.com/_/debian/) *(63.3MB)*
* Image size with JDK *(319MB)*

### Mission Control

Images below contains [Mission Control](http://www.oracle.com/technetwork/java/javaseproducts/mission-control/java-mission-control-1998576.html) as well:

#### *mission*
* Uses base image [Debian Stretch Slim](https://hub.docker.com/_/debian/) *(55.3MB)*
* Image size with JDK and *Mission Control* *(364MB)*

#### *sid-mission*
* Uses base image [Debian Sid Slim](https://hub.docker.com/_/debian/) *(63.3MB)*
* Image size with JDK and *Mission Control* *(378MB)*

## Usage
Image have docker *USER* named **app** so you can use it for your application.

Just add code below in your *Dockerfile* to use start your application as a user *app*
```
USER app
```

Check [example](https://github.com/GoodforGod/https://github.com/GoodforGod/docker-debian-jre10server-oracle/tree/master/example) folder for *Dockerfile* example of image usage.
