# docker-developer

Support for executing JBoss Middleware demonstrations within Docker 

## Prerequisites

### Docker

Docker must be installed and configured. See the following documentation to download and configure docker on your platform

* [Red Hat Enterprise Linux](https://docs.docker.com/installation/rhel/)
* [Mac OS X](https://docs.docker.com/installation/mac/)
* [Microsoft Windows](https://docs.docker.com/installation/windows/)

A comprehensive platform list can be found [here](https://docs.docker.com/installation/)

To get started with Docker, please refer to the official [user guide](https://docs.docker.com/userguide/)

## Contents

This repository contains a base developer Docker image for which downstream images can be built off of. The following configurations and technologies are incorporated:

* Extension of `jboss/base-jdk:7` 
	* Fedora
	* Java JDK 7
* Apache Maven 3+
* Git
* Additional utilities

## Retrieval

Obtain the prebuilt image:

```
docker pull jbossdemocentral/developer
```

Alternately It can also be built locally

```
git clone https://github.com/jbossdemocentral/docker-developer.git
cd docker-developer
docker build -t jbossdemocentral/developer .
```
