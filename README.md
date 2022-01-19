
## Install

```bash
  $ git clone https://github.com/sigits12/laravel-passport.git
  $ cd laravel-passport
  laravel-passport$ composer install
  laravel-passport$ mv .env.example .env
  laravel-passport$ php artisan generate:key
  laravel-passport$ php artisan migrate
  laravel-passport$ php artisan passport:install
  laravel-passport$ php artisan serve
```
# Endpoint
Register : {base_url}/api/register
Login : {base_url}/api/login

