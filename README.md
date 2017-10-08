# Tests Watcher Starter
#### A watcher, tester & dashboard for your tests

## Installing

```
git clone https://github.com/antonioribeiro/tests-watcher-starter.git
cd tests-watcher-starter
composer install
cp .env.example .example
php artisan generate:key

## create your database and configure your .env

php artisan migrate

## configure NGINX or Apache

open http://<app.domain>/tests-watcher/dashboard
```