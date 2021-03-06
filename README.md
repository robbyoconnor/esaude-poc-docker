<br/><br/><br/>
<img src="https://s3-eu-west-1.amazonaws.com/esaude/images/esaude-site-header.png" alt="OpenMRS"/>
<br/><br/><br/>

# eSaude EMR Point of Care Docker

This repository contains the necessary infrastructure code and related resources
required to compose and run Docker containers that start an instance
of the [eSaude EMR Point of Care](https://github.com/esaude/poc-ui-prototype) system. Three containers are created - one each for MySQL, Tomcat and Apache Web Server.

For more information about eSaude EMR visit [esaude.org](http://www.esaude.org/).

## Prerequisites

Make sure you have [Docker](https://docs.docker.com/) and [Docker Compose](https://docs.docker.com/compose/install/) installed.

## Setup

Start by cloning this repository:

````
$ git clone https://github.com/esaude/esaude-poc-docker.git
````

Enter the directory and build the images and run the containers:

````
$ cd esaude-poc-docker
$ docker-compose up
````

It may take a few minutes to download all the required resources.

## Access

To log into eSaude EMR POC application, use the following details:

* **Host**: `DOCKER_HOST/home`
* **User**: admin
* **Pass**: eSaude123

## License

[MPL 2.0 w/ HD](http://openmrs.org/license/) © [OpenMRS Inc.](http://www.openmrs.org/)
