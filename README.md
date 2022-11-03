# laravel-boilerplate

After downloading, make sure to:

1. copy and change db settings in .env
   - `cp .env.example .env` 
2. `php artisan key:generate`
3. `composer install` then run `php artisan serve`

## Install Laravel Breeze with Inertia 


Follow the installation instructions for ["Build Chirper with Inertia"](https://bootcamp.laravel.com/inertia/installation) for [vue](https://vuejs.org/):

1. Do `composer require laravel/breeze --dev` and then `php artisan breeze:install vue`,  
2. Run the migrations `php artisan migrate` and php artisan serve
3. Start the *frontend* app: `npm run dev`






