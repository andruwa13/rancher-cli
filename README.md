# Rancher Compose for Docker



[![Docker Stars](https://img.shields.io/docker/stars/fabn/rancher-cli.svg)](https://hub.docker.com/r/fabn/rancher-cli)
[![Docker Pulls](https://img.shields.io/docker/pulls/fabn/rancher-cli.svg)](https://hub.docker.com/r/fabn/rancher-cli)
[![ImageLayers Size](https://badge.imagelayers.io/fabn/rancher-cli:latest.svg)](https://hub.docker.com/r/fabn/rancher-cli)

This container can be used to run rancher CLI commands.

## Quick Start

* Pass authentication variables to docker using env, e.g.

        docker run --rm -it -e "RANCHER_URL=<your-rancher-server>" -e "RANCHER_ACCESS_KEY=<your-access-key>" -e "RANCHER_SECRET_KEY=<your-secret-key>" \
          -v "$PWD:/workspace" fabn/rancher-cli
