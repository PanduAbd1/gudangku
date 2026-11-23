# Gudangku - Sistem Manajemen Gudang

UTS Backend Development, studi kasus 4. Laravel 13, Modular Monolith, Laravel Sanctum, RBAC (Admin dan Staff Gudang), Blade, SQLite.

## Menjalankan

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate:fresh --seed
php artisan serve
