Step 1
add environment file (.env)
config your database

Step 2
composer install

Step 3
php artisan key:generate

php artisan migrate

php artisan db:seed --class=AdminSeeder

Step 4
php artisan serve --port=8888

http://localhost:8888

admin login

email: admin@gmail.com

pass: welcome123!