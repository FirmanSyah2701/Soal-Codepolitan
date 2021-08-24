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

    c. @extends('content')

    d. @yield('content')


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

19. Perintah artisan untuk membuat file seeder adalah 

    a. php artisan make:seed RolesTableSeeder

    **b. php artisan make:seeder RolesTableSeeder**

    c. php artisan create:seed RolesTableSeeder

    d. php artisan create:seeder RolesTableSeeder

20. Syntax untuk menambahkan role user saat register adalah
    
    a. $user->role('user');

    b. $user->hasRole('user');

    c. $user->haveRole('user');

    **d. $user->assignRole('user');**

21. Syntax untuk menjalankan seeder agar dapat disimpan di database adalah

    a. php artisan migrate

    b. php artisan migrate --seed

    **c. php artisan db:seed**

    d. php artisan db:seeder

## Membuat User Admin

22. Untuk membuat data admin yang sudah terverifikasi email di seeder maka kita perlu menambahkan code...

    a. 'email_verified_at' => now,

    b. 'email_verified_at' => $now,

    **c. 'email_verified_at' => now(),**

    d. 'email_verified_at' => $this->now,

23. 
    ```
    protected function authenticated(Request $request, $user) {
        if($user->hasRole('admin')) { 
            return redirect()->route('admin'); 
        }
     } 
    ```
    Code tersebut artinya...

    a. Jika user melakukan login maka akan meredirect ke halaman admin

    **b. Jika user yang memiliki role admin melakukan login maka akan meredirect ke route dengan nama admin**

    c. Jika user yang memiliki role admin melakukan login maka akan meredirect ke halaman dashboard

    d. Jika user yang memiliki role selain admin melakukan login maka akan meredirect ke halaman admin

24. Untuk menjalankan seeder hanya satu class seeder yaitu class AdminUserSeeder maka perlu menjalankan perintah artisan...

    a. php artisan db:seed -class=AdminUserSeeder

    **b. php artisan db:seed --class=AdminUserSeeder**

    c. php artisan db:seeder -class=AdminUserSeeder

    d. php artisan db:seeder --class=AdminUserSeeder

## Membedakan Route Admin _ User

25. Saat membuat file route baru maka perlu registrasikan file tersebut pada...
    
    a. AppServiceProvider

    b. EventServiceProvider

    **c. RouteServiceProvider**

    d. AuthServiceProvider

26. Agar route admin yang kita buat hanya bisa diakses oleh user yang memiliki role admin maka perlu menambahkan source code
    
    **a. ``Route::middleware('web', 'auth', 'role:admin')``**

    b. ``Route::middleware('web', 'auth', 'admin')``

    c. ``Route::middleware('auth', 'role:admin')``

    d. ``Route::middleware('auth', 'admin')``

27. Source code untuk mendefinisikan semua route dengan awalan admin. adalah
    
    a. ``middleware('admin.')``

    b. ``prefix('admin.')``

    **c. ``name('admin.')``**

    d. ``namespace('admin.')``

# Menyiapkan Dashboard Admin

## Menyiapkan Halaman Admin

28. Untuk menampilkan nama user yang sudah login pada blade adalah
    
    **``a. {{ auth()->user()->name }}``**

    b. ``{{ $auth()->user()->name }}``

    c. ``{{ user()->name }}``

    d. ``{{ $>user()->name }}``

29. Jika kita ingin membuat controller terpisah admin dan frontend maka perintah artisan yang dilakukan untuk membuat file controller pada namespace admin      
    adalah... 

    a. php artisan make:controller Admin\HomeController

    **b. php artisan make:controller Admin\\HomeController**

    c. php artisan make:controller Admin//HomeController

    d. php artisan make:controller Admin//HomeController

30. Saat kita membuat controller pada folder namespace Admin agar saat route kita tidak perlu mendefinisikan namespace dari folder Admin maka pada   
    RouteServiceProvider perlu menambahkan source code...

    **a. namespace($this->namespace . '\Admin')**

    b. namespace($this->namespace . '\\Admin')

    c. namespace($this->namespace . '/Admin')

    d. namespace($this->namespace . '//Admin')

## Membuat Data Author

31. Apa yang perlu kita isikan false saat kita tidak butuh data created_at dan updated_at pada suatu tabel?
    
    a. public $time = false;

    b. public $date = false;

    c. public $datetime = false;

    **d. public $timestamps = false;**

32. Syntax untuk membuat data fake/dummy nama

    a. 'name' => $faker->nama

    **b. 'name' => $faker->name**

    c. 'name' => $faker->named

    d. 'name' => $faker->names

33. Perintah untuk generate data factory author kedalam database adalah...

    **a. factory(App\Author::class, 10)->create();**

    b. factory(Author::class, 10)->create();

    c. factory()->create(App\Author::class, 10);

    d. factory()->create(Author::class, 10);

## Membuat Data Buku

34. Source code untuk mendapatkan data id secara random dengan model Author adalah

    a. Author::inRandomOrder()->first()->id()

    b. Author::inRandomOrder()->get()->id()

    **c. Author::inRandomOrder()->first()->id**

    d. Author::inRandomOrder()->get()->id

35. Perintah artisan untuk membuat model dan factory sekaligus adalah
   
    a. php artisan make:factory Book -m

    **b. php artisan make:model Book -f**

    c. php artisan make:factory Book --m

    d. php artisan make:model Book --f

36. Salah satu situs penyedia berbagai foto yang bisa kita dapatkan secara random secara online adalah

    **a. picsum.photos**

    b. placeholder

    c. random.photos

    d. asset.photos

## Menyingkat Generate Data

37. Untuk generate factory atau data dummy tanpa harus menggunakan artisan tinker adalah dengan menaruh source code create factroy ke dalam class...

    a. factory

    b. model

    **c. seeder**

    d. migration

38. composer dump-autoload adalah perintah...
    
    a. Untuk meload dan menregistrasikan secara otomatis package laravel dibuat

    b. Untuk meload secara otomatis semua package laravel 

    c. Untuk meload dan mendaftarkan namespace class yang telah dibuat

    **d. Untuk meload dan mendaftarkan namespace class yang telah diubah**

39. Perintah artisan untuk menjalankan migration beserta seeder nya adalah

    a. php artisan migrate --seed

    b. php artisan migrate --seeder

    **c. php artisan migrate:fresh --seed**

    d. php artisan migrate:fresh --seeder

## Menampilkan Data Penulis - Menyiapkan Asset _ Tampilan

40. package laravel untuk menampilkan data dalam bentuk table adalah

    a. laravel-tabledata

    **b. laravel-datatables**

    c. laravel-tables

    d. laravel-oracle

41. Perintah artisan untuk membuat AuthorController dengan kebutuhan crud adalah

    **a. php artisan make:controller AuthorController --resource**

    b. php artisan make:controller AuthorController --resources

    c. php artisan make:controller AuthorController --resourced

    d. php artisan make:controller AuthorController --r

42. Apa saja requirement yang dibutuhkan untuk menginstall laravel-datatables versi 9

    a. php >= 7.0, laravel >= 5.4, jquery v1.10 

    **b. php >= 7.0, laravel >= 5.4, jquery datatabkes v1.10**

    c. php >= 8.0, laravel 6, jquery v1.10

    d. php >= 8.0, laravel 6, jquery datatables v1.10

## Menampilkan Data Penulis - Implementasi Dengan Laravel DataTable

43. Syntax untuk menampilkan datatables dari table author adalah

    **a. ``return datatables()->of(Author::query())->toJson();``**

    b. ``return datatables()->on(Author::query())->toJson();``

    c. ``return datatables()->json(Author::query())->toJson();``

    d. ``return datatables()->json([Author::query()])->toJson();``

44. Datatable menampilkan response berupa json sebaiknya untuk menampilkan datanya di... 

    a. controller baru

    b. dibawah fungsi resource

    c. di dalam fungsi show resource

    **d. A dan B benar**

45. Blade directive yang mempunyai fungsi untuk menyisipkan suatu baris code dan dapat dipanggil oleh halaman yang dibutuhkan adalah...

    a. include

    **b. stack**

    c. section

    d. yield

## Membuat Fungsi Tambah Penulis

46. Source code untuk membuat data Author adalah...

    **a. ``Author::create($request->only('name'));``**

    b. ``Author::create([$request->only('name')]);``

    c. ``Author::create($request->name);``

    d. ``Author::create([$request-name]);``

47. Solusi error mass assigment saat create data adalah menambahkan .... di dalam model 

    a. protected $fillable = ['name'];

    b. protected $fillable = [];

    c. protected $guarded = [];

    **d. A dan C benar**

48. Fungsi untuk menambah data dalam controller adalah

    a. create()

    **b. store()**

    c. edit()

    d. update()

## Membuat Fungsi Edit Data Penulis

49. Kita dapat menggunakan fungsi latest pada eloquent jika...

    a. memiliki created_at

    b. memiliki updated_at

    c. timestamps tidak bernilan false

    **d. semua benar**

50. Fungsi eloquent untuk mengurutkan nama secara abjad adalah

    **a. orderBy('name, 'ASC')**

    b. orderBy('name, 'DESC')

    c. groupBy('name, 'ASC')

    d. groupBy('name, 'DESC')

51. Source code untuk mengubah data author menggunakan model binding adalah

    a. ``Author::update($request->only('name'));``

    b. ``Author::update([$request->only('name')]);``

    **c. ``$author->update($request->only('name'));``**

    d. ``$author::update([$request->only('name')]);``

## Membuat Fungsi Hapus Penulis

52. method controller yang digunakan untuk mengahpus data adalah

    a. delete()

    b. deleted()

    **c. destroy()**

    d. destroyed()

53. Source code untuk membuat tombol hapus data yang benar di laravel adalah

    a. 
    ```
    <form action={{ route('admin.author.destroy')}} method="POST">
        <input type="submit" value="Hapus">
    </form>
    ```

    b. 
    ```
    <form action={{ route('admin.author.destroy')}} method="POST">
        @csrf
        @method('DELETE')
    </form>
    ```

    c. 
    ```
    <form action={{ route('admin.author.destroy')}} method="DELETE">
        @csrf
        @method('DESTROY')
        <input type="submit" value="Hapus">
    </form>
    ```

    **d. 
    ```
    <form action={{ route('admin.author.destroy')}} method="POST">
        @csrf
        @method('DELETE')
        <input type="submit" value="Hapus">
    </form>
    ```
    **

54. Source code untuk menghapus data author menggunakan model binding adalah

    a. ``Author::delete();``

    b. ``Author::deleted();``

    **c. ``$author->destroy();``**

    d. ``$author::destroyed()``

## Menambahkan Dialog Sebelum Hapus Data Penulis

55. Salah satu library untuk membuat dialog adalah

    a. AlertDialog
    
    b. DialogAlert

    **c. SweetAlert2**

    d. Prompt

56. Untuk mentrigger fungsi hapus pada delete form saat menekan tombol konfirmasi untuk menghapusnya perlu menaruh code nya...

    **a. didalam if(result.value)**

    b. sebelum if(result.value)

    c. setelah if(result.value)

    d. dimana saja

57. Icon berhasil dalam sweetAlert adalah

    a. warning

    **b. success**

    c. info

    d. danger

## Menambahkan Flash Message

58.

59.

60.

## Mengganti Alert Dengan Bootstrap Notify

61.

62.

63.