# Team 4

## Build image
```
cp .env.example .env
docker-compose up --build 
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
cp .env.example .env
composer install
php artisan key:generate
php artisan migrate
```

## APP_URL
http://laradock.dev.test

