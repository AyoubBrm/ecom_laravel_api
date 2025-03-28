## Simple Laravel 10 REST API

A robust and scalable Laravel 10 REST API with Sanctum authentication, providing secure access to Products and Categories management.

# Installation

    to Start Docker run :
  - ./vendor/bin/sail up

Inside the Docker container run:
 - composer install
 - php artisan key:generate
 - php artisan migrate
 - php artisan queue:work (For queues)  # Ensure the queue driver (Redis, etc.) is properly configured

# API Structure:
* Authentication: Secure user registration and login via Laravel Sanctum
* Resource Management: Full CRUD functionality for Products and Categories
* Queue Processing: Supports background tasks using Redis, database queues, etc.

Developer Tools and Monitoring
CRUD[GET, POST, PUT/PATCH, DELETE] for Categories and Products
[POST] Login / Register 
