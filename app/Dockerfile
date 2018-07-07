############################################################
# Dockerfile to build a MongoDB and TestApp container
############################################################

# Set the base image
FROM python:3.6
# File Author / Maintainer
MAINTAINER Jeroen

COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt

# Run python script
CMD python app.py

RUN echo "App started"