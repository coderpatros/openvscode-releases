# OpenVSCode Server releases

This repo is only to produce releases for [OpenVSCode Server](https://github.com/gitpod-io/openvscode-server).

## Changes from upstream

I'm trying to keep changes from upstream minimal. The main change is using Ubuntu 20.04 as the base image instead of 18.04.

To use this image just run `docker run -it --init -p 3000:3000 -v "$(pwd):/workspace:cached" ghcr.io/coderpatros/openvscode-server`
