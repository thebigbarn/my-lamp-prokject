FROM php:8.2-apache

# Install extensions needed for MySQL
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Enable Apache rewrite (useful later for routing)
RUN a2enmod rewrite

