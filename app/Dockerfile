############################################################
# Dockerfile to build a MongoDB and TestApp container
# Based on Ubuntu
############################################################

# Set the base image to Ubuntu
FROM ubuntu
# File Author / Maintainer
MAINTAINER Jeroen
COPY . /app
# Build app
RUN make /app
# Run python script
CMD python /app/app.py

RUN echo "App started"