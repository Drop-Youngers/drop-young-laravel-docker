# Laravel Docker Template
A Laravel, Docker, Nginx, MySQL, Redis, and Mailhog template

# Installation
After you have cloned this repository or used this template as your starter code then run 
```bash
docker-compose build && docker-compose up -d
```
After successfull pulling image and creating all containers now you can create a laravel app

first go to `src/` folder
```bash
cd src
```
and then run

```bash
docker-compose run --rm composer create-project laravel/laravel .
```

you will see that in our containers we have `npm` , `composer` and `artisan` this guarante you that you can run the app without installint them manually to run each you can try the following commands 

```bash
docker-compose run --rm composer update # this is just composer update
docker-compose run --rm npm run dev # this is just npm run dev
docker-compose run --rm artisan server # this is just php artisan serve

```
# Inspirations
This template was inspired by [docker-compose-laravel](https://github.com/aschmelyun/docker-compose-laravel)
