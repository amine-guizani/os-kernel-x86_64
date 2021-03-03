### Still in development...

Build an image for our build-environment:
 - `docker build buildenv -t myos-buildenv`

## Build

Enter build environment:
 - Linux or MacOS: `docker run --rm -it -v "$pwd":/root/env myos-buildenv`

Build for x86:
 - `make build`

