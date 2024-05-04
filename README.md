Run the following commands:

- `git clone https://github.com/amttmg/docker-laravel.git`
- `cd docker-laravel`
- `docker compose up -d --build`
- `docker compose exec workspace bash`
- `composer install`
- `cp .env.example .env`
- `php artisan migrate`
- `php artisan key:generate`
- `npm install`
- `npm run build`

  Application: <a href="http://localhost:8080" target="_blank">localhost:8080</a> <br>
  Phpmyadmin: <a href="http://localhost:8081" target="_blank">localhost:8081</a>
