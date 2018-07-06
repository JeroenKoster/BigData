############################################################
# Dockerfile to build a MongoDB and TestApp container
# Based on Ubuntu
############################################################

# Set the base image to Ubuntu
FROM ubuntu
# File Author / Maintainer
MAINTAINER Example McAuthor
# Copy files from /app
COPY .. /app
# Build app
RUN make /app
# Run python script
CMD python /app/app.py

RUN echo "App started"