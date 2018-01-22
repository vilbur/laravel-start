## Kickstart configuration for new Laravel project
- composer.json contains main packages

#### How to install project
1. [Install Laravel.](#install-laravel)<br>
2. [Fetch this repository.](#fetch-this-repository)<br>
3. [Update Laravel.](#update-laravel)<br>

#### Install Laravel
``` bash
composer create-project laravel/laravel laravel-fresh &&cd laravel-fresh
```

#### Fetch this repository
Run this command in project folder
``` bash
git init &&git remote add origin https://github.com/vilbur/laravel-fresh.git &&git fetch --all &&git reset --hard origin/master &&git pull origin master
```

#### Update Laravel
Run these commands in cmd.exe (to prevent cygwin errors)
``` bash
composer update
php artisan voyager:install
yarn
npm install
```
