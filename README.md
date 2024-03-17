# Panduan Instalasi dan Cloning Project ini

Ini adalah panduan instalasi dan pengklonaan proyek Laravel dari repositori [PKL-SPK-SAW](https://github.com/ren-zi-fa/PKL-SPK-SAW.git).

## Instalasi

1. Pastikan Anda telah menginstal [Composer](https://getcomposer.org/) di komputer Anda.
2. Buka terminal atau command prompt.
3. Clone repositori PKL-SPK-SAW ke direktori lokal Anda dengan menjalankan perintah berikut:

```bash
git clone https://github.com/ren-zi-fa/PKL-SPK-SAW.git

cd PKL-SPK-SAW

cp .env.example .env

cp .env.example .env

php artisan key:generate

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nama_database_anda
DB_USERNAME=username_database_anda
DB_PASSWORD=password_database_anda

composer install

php artisan migrate

php artisan serve

git clone https://github.com/ren-zi-fa/PKL-SPK-SAW.git

> ###by:* renzi febriandika 
