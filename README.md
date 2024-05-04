Run the following commands:
#
- <pre><code>git clone https://github.com/amttmg/docker-laravel.git</code></pre>
- <pre><code>cd docker-laravel</code></pre>
- <pre><code>docker compose up -d --build</code></pre>
- <pre><code>docker compose exec workspace bash</code></pre>
- <pre><code>composer install</code></pre>
- <pre><code>cp .env.example .env</code></pre>
- <pre><code>php artisan migrate</code></pre>
- <pre><code>php artisan key:generate</code></pre>
- <pre><code>npm install</code></pre>
- <pre><code>npm run build</code></pre>
#
  Application: <a href="http://localhost:8080" target="_blank">localhost:8080</a> <br>
  Phpmyadmin: <a href="http://localhost:8081" target="_blank">localhost:8081</a>
  
