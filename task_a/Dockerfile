# Use official PHP runtime as base image
FROM php:8.2-apache

# Set working directory in container
WORKDIR /var/www/html

# Copy the current directory contents into the container
COPY . .

# Expose port 80
EXPOSE 80

# Command to run the application
CMD ["apache2-foreground"] 