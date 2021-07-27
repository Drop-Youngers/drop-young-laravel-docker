# laravel-docker-template
A laravel, docker, nginx, mysql , redis and mailhog template

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