# MEMBANGUN APLIKASI SPA LARAVEL VUEJS DENGAN FITUR AUTHENTIKASI

## Perkenalan Laravel Vue SPA with Authentication

1. Struktur project yang akan digunakan adalah...
    
    a. Unscalable project
    
    b. Unmodular project
    
    **c. Scalable/modular project**
    
    d. only modular project  

2. Apa fungsi dari vuex?
    
    a. Sebagai authentikasi
    
    b. Sebagai akses API Endpoint
    
    c. Sebagai akses router
    
    **d. Sebagai State Management**

3. Apa saja topik yang akan dipelajari?
    
    **a. Laravel passport, Api Endpoint / Axios, Scalable / Modular, State Management x vuex**
    
    b. Laravel sanctum, Api Endpoint / Axios, Scalable / Modular, State Management x vuex
    
    c. Laravel passport, Api Endpoint / Axios, Unscalable / Modular, State Management x vue router
    
    d. Laravel sanctum, Api Endpoint / Axios, Unscalable / Modular, State Management x vue router

## SETUP PROJECT LARAVEL PASSPORT

4. Apa yang dimaksud dengan laravel passport...

    **a. Package yang ada dilaravel untuk menghandle proses authentication dengan token.**

    b. Package yang ada dilaravel untuk menghandle proses authentication tanpa token

    c. Package yang ada dilaravel untuk menghandle proses authorization dengan token

    d. Package yang ada dilaravel untuk menghandle proses authorization tanpa token

5. Package manager yang digunakan untuk membuat project baru di laravel adalah...
    
    a. NPM
    
    b. PIP
    
    **c. Composer**
    
    d. GEMS

6. Perintah untuk membuat project baru dilaravel adalah...
    
    a. Composer project-create laravel/laravel nama_project

    b. Composer project-create laravel/nama_project
    
    **c. Composer create-project laravel/laravel nama_project**
    
    d. Composer create-project laravel/nama_project 


7. Cara menambahkan package laravel passport adalah...
    
    a. Composer include laravel/passport
    
    b. Composer included laravel/passport
    
    c. Composer required laravel/passport
    
    **d. Composer require laravel/passport**

## Api Endpoint Register


8. Cara membuat RegisterController adalah...

    a. php artisan create:controller Api/Auth/RegisterController

    b. php artisan install:controller Api/Auth/RegisterController

    **c. php artisan make:controller Api/Auth/RegisterController**

    d. php artisan build:controller Api/Auth/RegisterController


9. Cara agar di dalam route laravel tidak perlu ditambahkan nama method setelah nama file controller adalah dengan fungsi...

    a. register()

    **b. __invoke()**

    c. Invoke()

    d. __construct()


10. if(!Auth::attempt(request->only('email', 'password'))) adalah kondisi jika...
    
    a. Proses authentikasi success
    
    b. Proses authentikasi selesai
    
    **c. Proses authentikasi failed**
    
    d. Proses authentikasi berhenti

11. Apa response status code dari Response::HTPP_UNPROCESSABLE_ENTITY...
    
    a. 420
    
    b. 421
    
    **c. 422**
    
    d. 423

12. Response status code 201 artinya...
    
    a. OK
    
    **b. Created**
    
    c. Server Error
    
    d. Not Found
 
## Api Endpoint Login dan logout

13. Isi data $request->validate() yang ada di method login adalah...
    
    **a. Email dan password**

    b. Nama, Email dan Password

    c. Email saja

    d. Nama saja

14. Syntax apa yang ada pada fungsi logout?
    
    **a. Auth::user()->token()->revoke();**

    b. Auth::user()->revoke();

    c. Auth::user()->token()->logout();

    d. Auth::user()->logout();

15. Route yang digunakan untuk login adalah...
    
    a. GET
    
    b. PATCH

    c. PUT

    **d. POST**

16. Maksud dari Route::post("/auth/logout","LoginController@logout")->middleware("auth:api") adalah...
    
    a. untuk memastikan bahwa user sudah authentikasi dan belum memiliki token
    
    b. untuk memastikan bahwa user belum authentikasi dan sudah memiliki token
    
    **c. untuk memastikan bahwa user sudah authentikasi dan sudah memiliki token**
    
    d. untuk memastikan bahwa user belum authentikasi dan belum memiliki token

17. Apa yang di tambahkan di Headers pada postman untuk mengakses api endpoint login, logout dan user...
     
    a. Accept json/application 
    
    b. Content application/json
    
    c. Content json/application
    
    **d. Accept application/json**

## Menginstall Preset Vue dan Menampilkan Component

18. Berikut ini yang bukan merupakan type pada ui laravel adalah...
    
    a. bootstrap
    
    **b. angular**
    
    c. react
    
    d. vue

19. Apa syarat yang harus di lakukan sebelum menjalankan perintah npm install & npm run dev?
    
    **a. menginstall nodejs**
    
    b. menginstall jquery
    
    c. menginstall vue
    
    d. menginstall bootstrap

20. Perintah untuk menjalankan component vuejs dan setiap ada perubahan otomatis akan berubah adalah...
    
    a. npm run dev
    
    b. npm run save
    
    **c. npm run watch**
    
    d. npm run serve

21. Attribut apa yang ditambahkan untuk menjalankan script pada saat semua elemnt sudah di muat/load di dalam browser?
    
    a. Beaver
    
    b. River
    
    **c. Defer**
    
    d. Driver

22. file vuejs terdapat di direktori?
    
    a, public/js/components
    
    b. public/css/components
    
    c. resources/css/components
    
    **d. resources/js/components**

## Membuat Struktur Folder Project Vue

23. Modul-modul yang dibuat di simpan di di folder?
    
    a. resources/js/components
    
    **b. resources/js/app**
    
    c. resources/js/route
    
    d. resources/js/store

24. Di folder mana state management disimpan?
    
    a. route
    
    b. components
    
    **c. store**
    
    d. app

25. Pada masing-masing folder/direktori modul di isi kan file utama bernama?
    
    a. app.js
    
    b. main.js
    
    c. home.js 
    
    **d. index.js**

26. Pada file mana components vue dapat diakses secara global?
    
    **a. app.js**
    
    b. main.js
    
    c. home.js 
    
    d. index.js

## Implementasi Vue Router pada Modular Component

26. fitur-fitur vue router kecuali... 
    
    a. cocok untuk modular
    
    b. automatic css class
    
    c. efek transisi
    
    **d. efek statis**

27. perintah untuk menginstall vue router adalah 
    
    **a. npm install vue-router --save-dev**
    
    b. npm install VueRouter --save-dev
    
    c. npm install vue-router --dev-save
    
    d. npm install VueRouter --dev-save

28. authenticated: false pada meta arti nya?
    
    a. halaman komponen hanya dapat diakses oleh user yang sudah authentikasi
    
    b. halaman komponen tidak dapat diakses oleh user yang sudah registrasi
    
    **c. halaman komponen hanya dapat diakses oleh user yang belum authentikasi**
    
    d. halaman komponen tidak dapat diakses oleh user yang belum registrasi

29. Untuk bisa menggunakan vue router perlu menuliskan syntax?
    
    a. vue.component(VueRouter)
    
    b. Vue(VueRouter)
    
    **c. Vue.use(VueRouter)**
    
    d. VueRouter(VueRouter)

30. router-view berfungsi untuk?
    
    a. Melihat semua isi router
    
    **b. Komponen yang sudah diregistrasikan akan bisa diakses/tampil**
    
    c. Bepindah dari satu komponen ke komponen yang lain
    
    d. Bepindah dari satu komponen ke komponen yang lain tanpa reload/refresh