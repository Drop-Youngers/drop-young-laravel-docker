# Drop young Laravel-Docker

A Laravel, Docker, Nginx, MySQL, Redis, and Mailhog template

## Contributing

Contributions are always welcome😀!

- Fork the Template🍴
- Make Changes
- Push your commits to the forked repo
- Make a Pull Request
- Kindly wait for it to be merged
- Buy yourself a ☕ if it's merged🎉

  
## Tech Stack


**Web-framework:** Laravel

**Containerization Platform:** Docker

**Load-Balancer:** Nginx

**Package-Manger:** Maven

**Email Testing Tool:** Mailhog

**Programming-Language :** Php

**Database :** Mysql

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
## laravel mix
If you want to continue with laravel mix you can take a look on inspiration repo below

# Inspirations
This template was inspired by [docker-compose-laravel](https://github.com/aschmelyun/docker-compose-laravel)

## Testimonials & Review

If you found this template useful, please star the project or edit this ReadMe to leave a Review here:

- [@Reviewer](https://www.github.com/SauveJeanLuc): This is a review text, you can edit this ReadMe.md file and create request for you review to be added, Thanks😀.

## Authors
- [@claranceliberi](https://www.github.com/claranceliberi)


Copyright (C) [2021] [Drop-Youngers](https://www.github.com/Drop-Youngers)
