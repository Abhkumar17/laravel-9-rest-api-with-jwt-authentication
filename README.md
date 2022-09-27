Step 1: Download Laravel 9 App using these command laravel new project_name.
Step 2: Database Configuration
Step 3: Install JWT Auth using these command composer require tymon/jwt-auth:*

after that config/app.php

inside provider array
'Tymon\JWTAuth\Providers\JWTAuthServiceProvider',

and allias array

'JWTAuth' => 'Tymon\JWTAuth\Facades\JWTAuth',
'JWTFactory' => 'Tymon\JWTAuth\Facades\JWTFactory',

after that run this command

php artisan jwt:secret

Step 4: Set Up User Model

Step 5: Set Up Product Model and migration

php artisan make:model Product -m



Step 7: Create and Set Up Auth Controller

Step 8: Create and Set Up Product Controller


Step 9: Create Auth and CRUD API Routes

follow this link

https://www.w3techpoint.com/laravel/laravel-9-rest-api-with-jwt-authentication

