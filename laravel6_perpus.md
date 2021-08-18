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

    b. laravel ui

    **c. laravel permission**

    d. laravel roles

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

## Membuat Master _ Child View

10. Directive yang membooking sebuah tempat oleh child view adalah
    
    **a. @yield('content')**

    b. @content('content')

    c. @extends('content')

    d. @section('content')

11. Syntax untuk memamnggil template master adalah
    
    a. @extend('admin.templates.default') @endextend

    b. @extends('admin.templates.default') @endextends

    c. @extend('admin.templates.default')

    **d. @extends('admin.templates.default')**

12. Syntax untuk menyisipkan content pada yield('content') adalah

    **a. @section('content') @endsection**

    b. @sections('content') @endsections

    c. @section('content')

    d. @sections('content')


## Menyederhanakan Template dengan Subview

13. Apa keuntungan dari menggunakan template dengan subview?

    a. Dapat mudah dimaintenance

    b. Memperingkas source code

    c. Memperbanyak file pada project 

    **d. A dan B benar**

14. Pada php kita dapat memanggil file dengan require atau include sedangkan di blade kita dapat memanggilnya dengan syntax...

    a. @require('')

    b. @required('')

    **c. @include('')**

    d. @included('')

15. Apa saja yang dapat kita buat menjadi subview pada AdminLTE

    a. header, sidebar, footer, scripts

    b. header, navbar, footer, scripts

    c. head, header, sidebar, footer, scripts

    **d. head, header, sidebar, footer, scripts, control**

# Autentikasi Sistem Perpustakaan

## Menyiapkan Fitur Autentikasi

16. Package yang digunakan untuk membuat tampilan auth scaffolding adalah...

    a. laravel/permission

    **b. laravel/ui**

    c. laravel/debugbar

    d. laravel/auth

17. Salah satu smtf yang dapat digunakan untuk mengirim email dengan email testing adalah...

    a. mailtest.io

    b. mailfake.io

    **c. mailtrap.io**

    d. mailsmtf.io

18. Agar tampilan login dan register yang dibuat oleh larvel ui dapat menjalankan bootstrap nya maka perlu mengetikkan perintah...

    a. npm install && npm run serve

    b. npm install && npm run server

    **c. npm install && npm run dev**

    d. npm install && npm run build

## Memberikan Role Untuk User Terdaftar
