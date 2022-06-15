1) composer require tymon/jwt-auth
2) php artisan vendor:publish --provider="Tymon\JWTAuth\Providers\LaravelServiceProvider"
3) php artisan jwt:secret
4) php artisan make:controller ApiController
5) php artisan make:model Product -rcm
6) php artisan migrate