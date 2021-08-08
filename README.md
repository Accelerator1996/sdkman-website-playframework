# SDKMAN! website

![Build status](https://github.com/sdkman/sdkman-website/actions/workflows/release.yml/badge.svg)
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/sdkman/sdkman-website)

This is the service backing the SDKMAN! website at https://sdkman.io

## Run local

Make sure you have mongodb running locally or in a Docker Container:

    $ docker run -d --net=host --name mongo mongo:3.2

Start the app:

	$ ./sbt run
