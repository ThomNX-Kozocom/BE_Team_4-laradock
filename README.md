# Team 4

## Build image
```
docker-compose run --build 
```

## Start docker
```bash
./start.sh
```

## Stop docker
```bash
./stop.sh
```

## Start laravel
```bash
./laradock-workspace-bash.sh
composer install
php artisan key:generate
php artisan migrate
```

## APP_URL
laradock.dev.test

