# Dockerising the Tideways Daemon

This repo provides an Alpine Linux based Docker image for running the [Tideways](https://tideways.com) daemon. This is useful in serverless environments where you don't maintain the host machines running your applications and therefore can't simply install the `tideways-daemon` package. Services such as AWS ECS and Fargate can be used to run the _Dockerised_ daemon.

Images are [published on Docker Hub](https://hub.docker.com/r/mybuilder/tideways-daemon/tags).

## Adding a new version

Simply edit this [file](https://github.com/mybuilder/tideways-daemon-docker/blob/master/.github/workflows/publish.yml) and add another version to the matrix.
