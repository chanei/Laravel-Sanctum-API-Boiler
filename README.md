# Laravel-Sanctum-API-Boiler

Laravel 8.x API boiler plate using Sanctum

composer require laravel/sanctum

php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"

php artisan migrate

## call sanctum default migrations

php artisan vendor:publish --tag=sanctum-migrations
