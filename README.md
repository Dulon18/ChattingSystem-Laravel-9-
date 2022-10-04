<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Packages

<h3>Register & Login(Jetstream):</h3>

1. composer require laravel/jetstream

2. php artisan jetstream:install inertia

3. npm install

4. npm run build

5. php artisan migrate


<h3>Chatting package(Chatify)</h3>
https://chatify.munafio.com/installation

1. Create Pusher account for pusher id,app_key,app_secrate 
2. Add pusher details in .env file
3. composer require munafio/chatify
4. php artisan chatify:install
5. php artisan migrate

## Installation Instructions
- Clone the repo.
- Run 'composer install'
- Run 'cp .env.example .env'
- Run 'php artisan migrate --seed'
