# Installasi Laravel
1. Jalankan composer berikut
```
composer create-project laravel/laravel crud-laravel-adminlte
```

2. Buka pakai visual studio code dan open folder crud-laravel-adminlte


3.  Buka terminal & Install laravel/ui dengan perintah
```
    composer require laravel/ui
```
4. Buka terminal & lakukan perintah install bootstrap ui
```
php artisan ui bootstrap --auth
```

5. ketik perintah npm install
```
npm install
```
6. Install adminlte dengan perintah:

```
composer require jeroennoten/laravel-adminlte
```

7.  Buka terminal baru & Untuk menjalankan laravel ketik perintah:
```
php artisan serve
```
8. Buka terminal bar & Jalankan mode development menggunakan perintah:
```
npm run dev
```
Output :
```
VITE v4.2.1  ready in 236 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help

  LARAVEL v10.5.1  plugin v0.7.4

  ➜  APP_URL: http://localhost
```

9. Edit file .env dan atur database seperti dibawah:
```

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=crud_laravel
DB_USERNAME=root
DB_PASSWORD=
```
10. Lakukan proses migrasi tabel ke database seperti dibawah:
```
php artisan  migrate
```
11. Install adminlte dengan perintah:
```
php artisan adminlte:install --type=full
```

12. Install plugins dengan perintah:
```
php artisan adminlte:plugins install
```