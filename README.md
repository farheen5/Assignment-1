# Assignment-1
Step: 1
install laravel 7
open your terminal OR command prompt and run bellow command:
composer create-project --prefer-dist laravel/laravel blog
Step 2: Database Configuration
we will make database configuration for example database name, username, password etc for our crud application of laravel 7
Step 3: Create Migration
we are going to create crud application for product. so we have to create migration for "products" table using Laravel 7 php artisan command.
Now we have to run this migration by following command:
php artisan migrate
Step 4: Add Resource Route
 we need to add resource route for product crud application. so open your "routes/web.php" file.
 step: 5 add a blade files
 create,edit,update,delete and last one is show
 just file and put bellow code.
resources/views/products/layout.blade.php
resources/views/products/index.blade.php
resources/views/products/create.blade.php
resources/views/products/edit.blade.php
resources/views/products/show.blade.php
we are ready to run our crud application example with laravel 7 so run bellow command for quick run:
php artisan serve
