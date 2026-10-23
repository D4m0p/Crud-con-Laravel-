# CRUD rápido con Laravel

Laboratorio #2: CRUD de productos (`description`, `price`, `stock`) con Laravel, MySQL y Bootstrap.

## Puesta en marcha

```bash
composer install
npm install && npm run build
cp .env.example .env        # configurar las credenciales de DB_*
php artisan key:generate
php artisan migrate
php artisan serve
```

Abrir `http://127.0.0.1:8000/products`.
