# Use the official Nginx image as the base image
FROM nginx:latest

# Copy custom Nginx configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Copy static files to the web root directory
COPY src /usr/share/nginx/html
