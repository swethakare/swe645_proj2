# Use the official Apache HTTP Server base image
FROM httpd:latest

# Set the working directory to the Apache document root
WORKDIR /usr/local/apache2/htdocs

# Copy your web application files into the container
COPY .. /usr/local/apache2/htdocs/

# Expose port 80 for the web server (Apache's default port)
EXPOSE 80
