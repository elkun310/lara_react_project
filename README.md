# LARA_REACT Project
Developed by Elkun310

## Enviroment
- Nginx : >=1.16
- PHP : 7.3
- MySQL : 5.7
- Laravel Framework : 6.20.16

## Install guide

- Config Env and set up database:
    - `cp .env.example .env`
    - `php artisan db:migrate`
    - `php artisan db:seed`
    
- Config Laravel UI for Reactjs
    - `php artisan ui nextjs`
    - `composer require laravel/ui`
    - `php artisan ui bootstrap`
    - `npm install`
    - `npm run dev`
