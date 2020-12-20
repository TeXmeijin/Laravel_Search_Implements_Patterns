# About

Laravelでの設計論を語るためのリポジトリ

@see
`src/app/Components/README.md`

## Setup

```bash
 `cp src/.env.sample src/.env`
 `docker-compose up -d`
 `docker-compose exec app composer install`
 `docker-compose exec app php artisan key:generate`
 `docker-compose exec app php artisan migrate`
 `docker-compose exec app php artisan db:seed`
```
