############################################################
# Dockerfile to build a MongoDB and TestApp container
# Based on Ubuntu
############################################################

# Set the base image to Ubuntu
FROM ubuntu
# File Author / Maintainer
MAINTAINER Jeroen

RUN sudo apt-get update

RUN sudo apt-get install python

COPY . /app
# Run python script
CMD python /app/app.py

RUN echo "App started"