# dsri-nvidia-driver

An image for fedora coreos to update nvidia driver on the DSRI

Adapted from https://gitlab.com/container-toolkit-fcos/driver

## Build updated

[![Publish Docker image](https://github.com/seunAdeks/cellprofiler/workflows/Publish%20Docker%20image/badge.svg)](https://github.com/seunAdeks/cellprofiler/actions)

## Run

```bash
docker run -it -v $(pwd):/root ghcr.io/maastrichtu-library/dsri-nvidia-driver:latest
```