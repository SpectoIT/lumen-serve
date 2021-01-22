# lumen-serve
Command php artisan serve for lumen framework

If you want to use Laravel Sail, you just need to install this package and it will work

# Installation
1. `composer require devgowa/lumen-serve`
2. Register service provider in `boostrap\app.php` with `$app->register(Devgowa\LumenServe\CommandServeServiceProvider::class)`
3. Run `php artisan serve`

# Disclaimer
Just copied from Laravel 8 [laravel/framework](https://github.com/laravel/framework) by [@taylorotwell](https://github.com/taylorotwell)
