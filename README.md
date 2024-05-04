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
