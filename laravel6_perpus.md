# Membuat Sistem Inforamsi Perpustakaan dengan Laravel 6

# Pendahuluan

## Menyiapkan Project

1. Cara menginstall project laravel adalah

    a. composer install-project laravel/laravel --prefer-dist perpus

    **b. composer create-project laravel/laravel --prefer-dist perpus**

    c. composer build:project laravel/laravel --prefer-dist perpus

    d. composer make:project laravel/laravel --prefer-dist perpus

2. File untuk mengkonfigurasi koneksi database dalam laravel adalah adalah

    **a. .env**

    b. .env.example

    c. composer.json

    d. composer.lock

3. Package yang digunakan untuk roles adalah

    a. laravel debugbar

    b. laravel-ui

    **c. laravel-permission**

    d. laravel-roles

## Menginstall Laravel Debugbar

4. Kegunaan dari laravel debugbar adalah

    a. Menambahkan debugbar dibawah halaman website tanpa memperngaruhi development

    b. Menambahkan debugbar disamping kanan halaman website tanpa memperngaruhi development

    **c. Menambahkan debugbar dibawah halaman website tanpa memperngaruhi production**

    d. Menambahkan debugbar disamping kanan halaman website tanpa memperngaruhi production

5. Cara install package laravel-permission adalah...

    **a. composer require barryvdh/laravel-debugbar --dev**

    b. composer required barryvdh/laravel-debugbar --dev

    c. composer install barryvdh/laravel-debugbar --dev

    d. composer include barryvdh/laravel-debugbar --dev

6. Apa saja fitur yang ada pada laravel debugbar
    
    a. route, memory, response time, versi php

    b. route, memory, response time, version laravel

    c. queries, route, response time, version php

    **d. A dan C benar**

# Menyiapkan View Awal

## Menyiapkan Template Admin

7. Template admin yang free dan dapat kita gunakan adalah

    a. AdminTemplate

    b. TemplateAdmin

    **c. AdminLTE**

    d. LTEAdmin

8.  Folder apa saja yang butuhkan pada AdminLTE..
    
    a. components, dist, plugin

    **b. bower_components, dist, plugin**

    c. assets, dist, plugin

    d. vendor, dist, plugin

9. Cara menggunakan helper asset untuk meload bootstrap.min.css adalah

    a. ``{{ asset('asset/bower_components/bootstrap/dist/css/bootstrap.min.css') }}``

    **b. ``{{ asset('assets/bower_components/bootstrap/dist/css/bootstrap.min.css') }}``**

    c. ``{{ assets('asset/bower_components/bootstrap/dist/css/bootstrap.min.css') }}``

    d. ``{{ assets('assets/bower_components/bootstrap/dist/css/bootstrap.min.css') }}``