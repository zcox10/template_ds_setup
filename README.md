# Overview
Fork and clone this repo to have a sample setup every time you want to create a new GitHub repo. This repo uses Docker to simply utilize any packages, data, code, etc. related to this project.  See this [repo](https://github.com/zcox10/setup_machine/blob/master/README.md) for information on how to install Docker on your machine.

Docker images, specifically [Jupyter Docker Stacks](https://jupyter-docker-stacks.readthedocs.io/en/latest/) are fantastic! They are a set of ready-to-run Docker images containing Jupyter applications and interactive computing tools. You can use a stack image to do any of the following (and more):

1. Start a personal Jupyter Notebook server in a local Docker container
2. Run JupyterLab servers for a team using JupyterHub
3. Write your own project Dockerfile

The docker stack we'll be installing is specifically the `jupyter/datascience-notebook` docker stack.  All of the template Jupyter Docker Stacks can be found [here](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html).

Run this command within a repo 

# Utilizing the Docker Image
The [Dockerfile](LINK HERE!) contains all of the necessary packages found within Jupyter Docker Stacks `datascience-notebook` image. There are instructions below on how to add more packages if necessary.

# Adding Packages
You can simply add packages with the `RUN` command.  



docker build --no-cache -t u12_core
