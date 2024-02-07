## Install with Docker

- git clone 
- cd LARAVEL-DOCKER
- git checkout laravel_10
- `docker-compose up -d`
- `docker exec -it laravel /bin/bash`
- `composer install`
- `cp .env.example .env`
- `php artisan key:generate`
- `php artisan migrate`
- `php artisan db:seed`
  
### Site URL

- Application http://localhost:8888
- Adminer for Database Your Ip:8800


DB credentials:
```
Server: db:3307
Username: root
Password: 123456@udoy 
Database: udoy
```

### How to refresh a specific migrations 
```
 php artisan migrate:refresh --path=/database/migrations/tablename.php
```
