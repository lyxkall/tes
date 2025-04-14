composer create-project "laravel/laravel:^11.0" todo_wib
cd todo_wib

composer require laravel/breeze --dev
php artisan breeze:install

php artisan migrate
npm install
npm run dev
php artisan serve

php artisan make:model Todo –mcr
