# About

LaravelでDDDやクリーンアーキテクチャの手法を導入しつつ、検索系の処理を組み込むパターン集

@see
[src/app/Components/README.md](https://github.com/TeXmeijin/Laravel_Search_Implements_Patterns/tree/main/src/app/Components)

## Setup

```bash
 `cp src/.env.sample src/.env`
 `docker-compose up -d`
 `docker-compose exec app composer install`
 `docker-compose exec app php artisan key:generate`
 `docker-compose exec app php artisan migrate`
 `docker-compose exec app php artisan db:seed`
```
