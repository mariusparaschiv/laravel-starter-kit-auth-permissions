# Laravel starter kit with auth and permissions

## Installation
In your console run:
```bash
  #Install dependencies
  composer install
  
  #Setup .env file
  cp .env.example .env
  
  #Generate the application key
  php artisan key:generate
  
  #Run migrations
  php artisan migrate

  #Install passport keys
  php artisan passport:install
  
  #Run seeder
  php artisan db:seed
```
