# DockerizingWithNginx

This project demonstrates how to containerize a simple web application using Docker and Nginx.

## Files

### index.html

This file contains the HTML content of the web page served by the Nginx server. It is a simple static web page that displays "Hello, world!".

### nginx.conf

The Nginx configuration file specifies how Nginx should serve the web application. It configures Nginx to listen on port 80 and serve the index.html file.

### Dockerfile

The Dockerfile is used to define the Docker image for the web application. It starts from an official Nginx base image, copies the index.html and nginx.conf files into the appropriate location in the container, and ensures that the Nginx server is started when the container is run.

