# 🎉 DEMO Laravel Breeze Telescope

Laravel Telescope is a powerful debugging and monitoring tool for Laravel applications, providing insights into requests, exceptions, logs, queries, jobs, and more, allowing developers to easily track, debug, and optimize their application's performance.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### 🚀 Setup

- Create Project

```shell
composer create-project laravel/laravel example-app
```

- Install Package

```shell
composer require laravel/telescope
```

- Configure Environment

```shell
cp .env.example .env
```

- Install Telescope

```shell
php artisan telescope:install
```

- Migrate

``` 
php artisan migrate
```

### 🏆 Run

- [http://localhost:8000/telescope](http://localhost:8000/telescope) username : `admin` password : `admin`

```shell
php artisan serve
```
