############################################################
# Dockerfile to build a MongoDB and TestApp container
# Based on Ubuntu
############################################################

# Set the base image to Ubuntu
FROM python:3.6
# File Author / Maintainer
MAINTAINER Jeroen

COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt

# Run python script
CMD python app.py

RUN echo "App started"