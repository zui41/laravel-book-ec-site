Clone the repository from GIT, and then:

```
cp .env.example .env
composer install --no-progress
php artisan key:generate
```

With the DB already created and set on .env, run:

```
php artisan migrate
```

To start a local server

```
php artisan serve
```
