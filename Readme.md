### Setup Project

> Step 1: Setting up laravel project inside the src folder
```
docker-compose run --rm composer create-project --prefer-dist laravel/laravel:^8.0 .
```

> Step 2: To run limited service
```
docker-compose up -d server php mysql
```
> __NOTE__ : 
> 1. No need to have content inside src folder as the above command creates folder structure by itself
> 2. If there is an issue with creating laravel project inside src folder user this command : ```docker-compose run --rm composer clear-cache ```


