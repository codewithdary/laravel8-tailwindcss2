## Laravel Documentation
This is the source of the official [website of Laravel](https://laravel.com/)

## Version
This Laravel framework is running on a version of 8.48.2 and TailwindCSS is running on 2.2.4.

## Usage

Clone the project <br>
```git clone git@github.com:Darynazar/laravel8-tailwindcss2.git```

Change directories into your project <br>
```cd laravel8-tailwindcss2```

Make sure that you install composer <br>
```composer install```

If you have composer installed, then update it (Optional) <br>
```composer update```

Create the .env file by duplicating the .env.example <br>
```cp .env.example .env```
 
Set the APP_KEY value <br>
```php artisan key:generate```

Clear your cache & config (Optional) <br>
```php artisan cache:clear && php artisan config:clear```

Run your project in the browser <br>
```php artisan serve```
