# CRUD Laravel 5.3 dengan Repository Pattern

## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

### Clone repository ini
```
git clone https://github.com/alfi6/crud-using-repository-laravel-5-3.git
```
Jangan lupa untuk melakukan composer installer
```
composer install
```

### Buat database baru dengan nama terserah, dan buat file .env. Ganti DB_DATABASE dengan nama database yang anda buat, isi DB_USERNAME dan DB_PASSWORD sesuai password anda

```
// file .env

APP_ENV=local
APP_DEBUG=true
APP_KEY=Xm67S04I78Y3az5NDx8jM9jotsasE6D2

DB_HOST=localhost
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret

CACHE_DRIVER=file
SESSION_DRIVER=file
QUEUE_DRIVER=sync

MAIL_DRIVER=smtp
MAIL_HOST=mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
```
## Isi database menggunakan seeder
Ketikkan pada terminal/command prompt

```
$ php artisan make:seeder ContactTableSeeder
```
Kalau sudah selesai run seeder
```
$ php artisan db:seeder
```
## Start a live-reload development server 
Ketikkan pada terminal/command prompt

```
$ php artisan serve
```
selanjutnya buka browser dan ketikkan
```
localhost:8000/api/contacts
```
