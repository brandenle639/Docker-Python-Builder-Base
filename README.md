# Docker-Python-Builder-Base
This Dockerfile installs all the required packages that are required to build Python from the source. This is the builder and that can be used to create smaller Docker containers that can use the built Python.

# To Build
docker build -t pythonbuilder:{Version You Want} {Path of the Docker File} --no-cache

# To Run
It doesn't run on it's own it is the base for "Docker-Python-Compiler" to compile and make python containers

# Notes
This contains all the depndacies for the make process

I don't own any of the install packages