# My Base Image. 
FROM ubuntu:latest

# Owner
MAINTAINER Amit Vashist <amitvashist7@gmail.com>

# Update the APT Repo. 
RUN apt-get update 

# Install Apache Packages 
RUN apt-get install apache2 -y 

# Create a New Index Page
RUN echo "Welcome To the world of Docker Images" > /var/www/html/index.html

# Injecting the Application Code inside Image 
COPY amit.html /var/www/html/info.html

# Expose the Service Port.
EXPOSE 80

# Bring the Apache Service 
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
