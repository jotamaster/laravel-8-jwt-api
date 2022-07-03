composer install

php artisan vendor:publish --provider="Tymon\JWTAuth\Providers\LaravelServiceProvider"


php artisan jwt:secret


php artisan migrate --seed


para errores
php artisan migrate:fresh --seed


php artisan serve
