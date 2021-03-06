hello-world
===========

[dockercloud/hello-world](https://github.com/docker/dockercloud-hello-world) with HTTP Headers

![Screenshot](https://github.com/olegsmetanin/dockercloud-hello-world/raw/master/screen.png)

Sample docker image to test docker deployments

## Running locally

Build and run using Docker Compose:

	$ git clone https://github.com/olegsmetanin/dockercloud-hello-world
	$ cd dockercloud-hello-world
	$ docker-compose up


## Deploying to Docker Cloud

[Install the Docker Cloud CLI](https://docs.docker.com/docker-cloud/tutorials/installing-cli/)

	$ docker login
	$ docker-cloud stack up

Hello world!

## Configuration

|Environment Variable|Default|Description|
|:-----:|:-----:|:----------|
|LISTEN_PORT|80|Set the Listen Port to access the hello-world container if it has the same Service Port.