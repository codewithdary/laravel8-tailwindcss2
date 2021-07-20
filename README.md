## Laravel 8  & TailwindCSS 2 skeleton

Whether you’re watching my tutorials or you are interested in cloning this repo where TailwindCSS is already implemented in an empty Laravel 8 project!

•	Author: Code With Dary 
•	Twitter: @codewithdary
•	Instagram: @codewithdary

## Requirements
•	PHP 7.3 or higher

## Version
This Laravel framework is running on a version of 8.48.2 and TailwindCSS is running on 2.2.4.

Usage
Clone the repository <br>
```
git clone git@github.com:codewithdary/laravel8-tailwindcss2.git
```

Change directories into laravel8-tailwindcss2 <br>
```
cd laravel8-tailwindcss2/
```

Install composer <br>
```
composer install
```

Create the .env file by duplicating the .env.example file <br>
```
cp .env.example .env
```

Set the APP_KEY value <br>
```
php artisan key:generate
```

Clear your cache & config (OPTIONAL)
``` 
php artisan cache:Clear && php artisan config:clear
```

Finally, run your project in the browser!
```
php artisan serve
```
![image](https://user-images.githubusercontent.com/63154066/126394210-84395be4-85b1-41ea-8eee-a5202e305f1a.png)
