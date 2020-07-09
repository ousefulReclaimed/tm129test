# tm129test
test of notebook  server


This repo provides a demo of a relatively straightforwrd load of a containerised environment specified via a Jelastic `manifest.jps` environment config file stored in a publis Github repo.

In this example, the `manifest.jps` file specifies a `docker run` command that launches a pre-built docker contianer pulled from Dockerhub. In this example, the container is built from an offical Jupyter stack docker container, which means we can define an authentication token via an environment variable defined via the manifest file. This obviously isn't very secure, so I wonder: could we define some environment variables via a private reclaim.cloud setting somewhere?
