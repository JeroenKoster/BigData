############################################################
# Dockerfile to build a MongoDB and TestApp container
############################################################

# Set the base image (Includes: miniconda2, pip, numpy, matplotlib & Exposes 8080)
FROM apache/zeppelin:0.8.0
# File Author / Maintainer
MAINTAINER Jeroen

COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt


RUN echo "Zeppelin started"