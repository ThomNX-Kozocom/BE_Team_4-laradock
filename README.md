# Team 4

## Build image
```
cp .env.example .env
docker-compose up --build 
```

## Run Laravel

### Setup env docker
```
APP_CODE_PATH_HOST= #Link folder source
PHP_VERSION= # Depends on laravel version
```
### Start docker laravel
```bash
./start-laravel.sh
```

### Stop docker laravel
```bash
./stop-laravel.sh
```

### Start laravel
```bash
./laradock-workspace-bash.sh
```

Setup env Laravel
```
DB_CONNECTION=mysql
DB_HOST=mysql
DB_PORT=3306
DB_DATABASE=default
DB_USERNAME=root
DB_PASSWORD=root
```

### APP_URL
http://laradock.dev.test

## Run Nodejs

### Setup env docker
```
APP_CODE_PATH_HOST_NODEJS= #Link folder source
```

### Start docker laravel
```bash
./start-nodejs.sh
```

### Stop docker laravel
```bash
./stop-nodejs.sh
```

### Start Nodejs
```bash
./web1-bash.sh
```

### APP_URL
http://localhost


