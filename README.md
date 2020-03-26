
# Development

First install dependencies 
`cat dependencies | xargs sudo apt-get install -y`

`laravel new src` # or move your source to ./src
`cd ./src && composer install`

`cd ..`
`docker-compose build`
`docker-compose up`

## Migration
`docker-compose exec weather-php php /var/www/artisan migrate`

