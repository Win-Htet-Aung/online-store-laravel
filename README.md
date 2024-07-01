## About Online Store

This project, "Online Store" is a tutorial project from the book "Practical Laravel".
In this project, I've learned:

- Model-View-Controller (MVC) architecture of Laravel framework
- Routing and middlewares
- Templating with blade
- Configuring and integrating with MySQL database
- Tracking database version with the help of migrations
- Basic CRUD using Eloquent ORM
- Basic authentication and authorization using "laravel/ui"
- Using web session to implement shopping cart feature

## Prerequisite

The following tools need to be installed first to run this project.

- php (8.2.*)
- composer (2.7.*)
- mysql

## Running the project

Follow these steps to run the project.

- clone the repo ```git clone https://github.com/Win-Htet-Aung/online-store-laravel.git```
- install dependencies ```composer install```
- run migrations ```php artisan migrate```
- run admin user seeder ```php artisan db:seed --class=UserSeeder```
- generate key ```php artisan key:generate```
- run server ```php artisan serve```
