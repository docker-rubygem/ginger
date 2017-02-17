[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/ginger.svg)](https://hub.docker.com/r/rubygem/ginger/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/ginger.svg)](https://hub.docker.com/r/rubygem/ginger/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/ginger.svg)](https://hub.docker.com/r/rubygem/ginger/)
[![Gem Downloads](https://img.shields.io/gem/dt/ginger.svg)](https://rubygems.org/gems/ginger/)
# ginger

Auto-Generated Docker image for ginger to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/ginger`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/ginger`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/ginger`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/ginger/)
