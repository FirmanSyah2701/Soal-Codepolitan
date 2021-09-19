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

9. Cara menggunakan helper asset untuk meload css bootstrap adalah

    a. ``{{ asset('asset/bower_components/bootstrap/dist/css/bootstrap.min.js') }}``

    **b. ``{{ asset('assets/bower_components/bootstrap/dist/css/bootstrap.min.css') }}``**

    c. ``{{ assets('asset/bower_components/bootstrap/dist/css/bootstrap.min.js') }}``

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
    ```php
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

29. Jika kita ingin membuat controller terpisah admin dan frontend maka perintah artisan yang dilakukan untuk membuat file controller pada namespace admin adalah... 

    a. php artisan make:controller Admin\HomeController

    **b. php artisan make:controller Admin\\HomeController**

    c. php artisan make:controller Admin//HomeController

    d. php artisan make:controller Admin//HomeController

30. Saat kita membuat controller pada folder namespace Admin agar saat route kita tidak perlu mendefinisikan namespace dari folder Admin maka pada RouteServiceProvider perlu menambahkan source code...

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

    a. ``protected $fillable = ['name']``;

    b. ``protected $fillable = []``;

    c. ``protected $guarded = [];``

    **``d. A dan C benar``**

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

51. Source code untuk mengubah data author menggunakan route model binding adalah

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
    ```php
    <form action="{{ route('admin.author.destroy' )}}" method="POST">
        <input type="submit" value="Hapus">
    </form>
    ```

    b. 
    ```php
    <form action="{{ route('admin.author.destroy') }}" method="POST">
        @csrf
        @method('DELETE')
    </form>
    ```

    c. 
    ```php
    <form action="{{ route('admin.author.destroy') }}" method="DELETE">
        @csrf
        @method('DESTROY')
        <input type="submit" value="Hapus">
    </form>
    ```

    **d. 
    ```php
    <form action="{{ route('admin.author.destroy') }}" method="POST">
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

    d. ``$author::destroyed();``

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

58. Source code untuk membuat session adalah

    a. with('success', 'Data berhasil disimpan');

    b. with(['success', 'Data berhasil disimpan']);

    **c. session('success', 'Data berhasil disimpan');**

    d. session(['success', 'Data berhasil disimpan']);

59. Source code untuk menampilkan alert atau flash message adalah

    a. 
    ```php
    @if(with('success'))
        {{ with('success') }}
    @endif
    ```

    b. 
    ```php
    @if(message('success'))
        {{ message('success') }}
    @endif
    ```

    **c. 
    ```php
    @if(session('success'))
        {{ session('success') }}
    @endif
    ```
    **

    d. 
    ```php
    @if(sessions('success'))
        {{ sessions('success') }}
    @endif
    ```

60. Method with bisa dipakai saat mereturn...

    a. request create

    b. request update

    c. request delete

    **d. redirect**

## Mengganti Alert Dengan Bootstrap Notify

61. Salah satu library untuk alert yang menggunakan framework bootstrap adalah...

    a. Bootstrap Alert
    
    **b. Bootstrap Notify**

    c. Bootsnipp

    d. Bootstrap Message

62. Apa saja yang bisa kita isi pada Bootstrap Notify?

    a. message, title,

    **b. message, type**

    c. message, title, text, icon

    d. message, title, text, type

63. Source code untuk mengisi message dari session pada bootstrap notify adalah

    a. message: session('success')
    
    b. message: sessions('success')

    **c. message: 'session('success')'**

    d. message: 'sessions('success')'

## Judul Halaman Dinamis _ Breadcrumbs

64. Maksud dari source code ``{{ $title ?? 'Perpustakaan' }}`` adalah

    a. Menampilakan variable title

    b. Menset variable title dengan text Perpustakaan

    c. Menampilkan variable title dan text perpustakaan

    **d. Menampilkan variable title dan apabila variable title tidak terdaftar maka akan menampilkan text perpustakaan**

65. Source code untuk menampilkan breadcrumbs yang sedang aktif adalah

    a. {{ Breadcrumbs::render() }}

    b. {{ Breadcrumbs::title() }}

    c. {{ Breadcrumbs::render()->title }}

    **d. {{ Breadcrumbs::current()->title }}**

66. Dimana tempat untuk mendefinisikan breadcrumbs?

    a. controllers/bradcrumbs.php

    b. models/bradcrumbs.php

    **c. routes/bradcrumbs.php**

    d. resources/bradcrumbs.php

## Menambahkan Validasi Pada Form

67. Nama validasi yang mengaharuskan kita untuk tidak mengisi data/form kosong adalah

    **a. required**

    b. not_null

    c. not_empty

    d. min

68. Source code untuk menampilkan pesan error dari validasi name adalah
    
    a. ``@if('name') <span class="help-block"> {{ $error }} </span> @endif``

    b. ``@error('name') <span class="help-block"> {{ $error }} </span> @enderror``

    c. ``@if('name') <span class="help-block"> {{ $message }} </span> @endif``

    **d. ``@error('name') <span class="help-block"> {{ $message }} </span> @enderror``**

69. Source code agar inputan field tidak hilang saat form error adalah

    a. value="{{ $name }}"

    b. value="{{ $old('name') }}"

    **c. value="{{ old('name') }}"**

    d. value="{{ ('name') }}"

## Menyederhanakan Routing dengan Route Resource

70. Untuk menyederhanakan route yang controller nya memiliki crud kita dapat menggunakan route helper...

    a. resource

    **b. resources**

    c. list

    d. lists

71. Saat terjadi error dalam menggunakan route resource dikarenakan ada kesamaan nama url cara penanganannya adalah...
    
    a. Menaruh route resource diatas

    **b. Menaruh route resource dibawah**

    c. Mengganti salah satu nama url route
    
    d. a dan c benar

72. Source code untuk menggunakan route resource adalah...

    a. Route::resource('author', 'AuthorController@index');

    b. Route::resource('author', 'AuthorController@create');

    c. Route::resource('author', 'AuthorController@store');

    **d. Route::resource('author', 'AuthorController');**

## Menampilkan Data Modul Buku

73. cara menambahkan variable title pada controller agar bisa diakses pada halaman index adalah...

    a. return view('index')->(['title' => 'Perpus']);

    **b. return view('index', ['tilte' => 'Perpus']);** 

    c. return view('index')->(['title' = 'Perpus']);

    d. return view('index', ['tilte' = 'Perpus']);

74. Source code menambahkan relasi 1 author memiliki banyak buku adalah...

    **a. 
    ```php
    public function books(){
        return $this->hasMany(Book::class);
    }
    ```
    **

    b.
    ```php
    public function books(){
        return $this->hasMany('Book');
    }
    ```

    c.
    ```php
    public function books(){
        return $this->belongsTo(Book::class);
    }
    ```

    d.
    ```php
    public function books(){
        return $this->belongsTo('Book');
    }
    ```

75. Source code untuk mengambil data nama author melalui model book adalah...

    a. 
    ```php
    function(Book $book){
        return $book->name;
    }
    ```

    b.
    ```php
    function(Book $book){
        return $book->author()->name;
    }
    ```

    **c. 
    ```php
    function(Book $book){
        return $book->author->name;
    }
    ```
    **

    d.
    ```php
    function(Book $book){
        return $book->$author->name;
    }
    ```

## Membuat Form Tambah Buku

76. Untuk inputan file pada form perlu menambahkan property  

    a. ``enctype="application/x-www-form-urlencode"``

    b. ``enctype="application/json"``

    **c. ``enctype="multipart/form-data"``**

    d. ``enctype="text/plain"``

77. Library untuk select option yang memiliki pencarian adalah...

    a. select2 option

    b. select two option 

    **c. select2**

    d. select two

78. Source code untuk mendefinisikan class yang digunakan sebagai select2...  

    a. ``$('.select2').select2;``

    **b. ``$('.select2').select2();``**

    c. ``$(['.select2']).select2;``

    d. ``$(['.select2']).select2();``

## Membuat Fungsi Simpan Buku _ Menanangani Asset Gambarnya

79. Dalam table books pada field cover terdapat berbagai macam value diantaranya picsum, assets dan null untuk get data cover dengan macam ini penanganannya adalah...

    **a.
    ```php
    public function getCover(){
        if(substr($this->cover,0,5) == "https"){
            return $this->cover;
        }

        if($this->cover){
            return asset($this->cover);
        }

        return 'via.placeholder.com/728x90.png?text=No+Cover';
    }
    ```
    **

    b.
    ```php
    public function getCover(){
        if(substr($this->cover,1,5) == "https"){
            return $this->cover;
        }

        if($this->cover){
            return asset($this->cover);
        }

        return 'via.placeholder.com/728x90.png?text=No+Cover';
    }
    ```

    c.
    ```php
    public function getCover(){
        if(substr($this->cover,0,5) = "https"){
            return assets($this->cover);
        }

        if($this->cover){
            return $this->cover;
        }

        return 'via.placeholder.com/728x90.png?text=No+Cover';
    }
    ```

    d.
    ```php
    public function getCover(){
        if(substr($this->cover,1,5) = "https"){
            return assets($this->cover);
        }

        if($this->cover){
            return $this->cover;
        }

        return 'via.placeholder.com/728x90.png?text=No+Cover';
    }
    ```

80. Cara menangani column 'cover' cannot be null saat dalam sistem tidak wajib menginputkan cover adalah

    a. ``$table->string('cover');``

    b. ``$table->string('cover')->default('null');``

    **c. ``$table->string('cover')->nullable()->default(null);``**

    d. ``$table->string('cover')->nullable()->default('null');``


81. Source code untuk memanggil method getCover() dalam editColumn datatables adalah...

    a. 
    ```php
    ->editColumn('cover', function(Book $model) {
        return '<img src="'. $model->getCover .'" height="150px">';
    })
    ```

    **b. 
    ```php
    ->editColumn('cover', function(Book $model) {
        return '<img src="'. $model->getCover() .'" height="150px">';
    })
    ```
    **

    c. 
    ```php
    ->editColumn('cover', function(Book $model) {
        return '<img src="'. $model->cover .'" height="150px">';
    })
    ```

    d. 
    ```php
    ->editColumn('cover', function(Book $model) {
        return '<img src="'. $model->cover->getCover() .'" height="150px">';
    })
    ```

## Membuat Fungsi Update Buku

82. Saat update data buku muncul error The POST is not supported for this route penanganannya adalah...

    a. @method("POST")

    **b. @method("PUT")**

    c. method="POST"

    d. method="PUT"

83. Source code pada halaman edit buku untuk option agar otomatis selected nama penulis nya berdasarkan id yang tersimpan di database adalah...

    a.
    ```php 
    <option value="{{ $author->id }}"
        @if($author->id = $book->author_id)
            selected
        @endif
    >
    ```

    **b.
    ```php
    <option value="{{ $author->id }}"
        @if($author->id === $book->author_id)
            selected
        @endif
    >
    ```
    **

    c. 
    ```php
    <option value="{{ $author->id }}">
        @if($author->id = $book->author_id)
            selected
        @endif
    ```

    d. 
    ```php
    <option value="{{ $author->id }}">
        @if($author->id === $book->author_id)
            selected
        @endif
    ```

84. Source code untuk update/ubah data buku jika cover tidak diubah maka akan tetap menyimpan cover yang lama jika diubah maka akan menyimpan cover yang baru dengan menghapus cover yang lama adalah...

    a.
    ```php
    $cover = null;
    if($request->hasFile('cover')){
        Storage::delete($book->cover);
        $cover = $request->file('cover')->store('assets/covers');
    }
    ```

    b.
    ```php
    $cover = null;
    if($request->hasFile('cover')){
        Storage::destroy($book->cover);
        $cover = $request->file('cover')->store('assets/covers');
    }
    ```

    **c.
    ```php
    $cover = $book->cover;
    if($request->hasFile('cover')){
        Storage::delete($book->cover);
        $cover = $request->file('cover')->store('assets/covers');
    }
    ```
    **

    d.
    ``` php
    $cover = $book->cover;
    if($request->hasFile('cover')){
        Storage::destroy($book->cover);
        $cover = $request->file('cover')->store('assets/covers');
    }
    ```

## Menghapus Data Buku

85. Source code yang benar untuk membuat fungsi hapus buku pada controller adalah...

    a. 
    ```php
    public function destroy(){
        $book->delete();
        return redirect()->route('admin.book.index')->withDanger('Data buku berhasil dihapus');
    }
    ```

    b. 
    ```php
    public function destroy($book){
        $book->delete();
        return redirect()->route('admin.book.index')->withDanger('Data buku berhasil dihapus');
    }
    ```

    **c. 
    ```php
    public function destroy(Book $book){
        $book->delete();
        return redirect('admin.book.index')->route()->withDanger('Data buku berhasil dihapus');
    }
    ```
    **

    d. 
    ```php
    public function destroy(Book $book){
        $book->delete();
        return redirect()->route('admin.book.index')->withDanger('Data buku berhasil dihapus');
    }
    ```

## Tips Menangani Aset Project

86. dataTables.bootstrap.min.css dibutuhkan hanya pada file index karena itu sebelum tutup head perlu menambahkan syntax

    **a. @stack('styles')**

    b. @push('styles')

    c. @yield('styles')

    d. @section('styles')

87. Source code untuk memanggil memanggil dataTables.bootstrap.min.css pada file index.blade.php adalah...

    a. 
    ```php
    @stack('styles') 
        <link rel="stylesheet" href="{{ asset('assets/bower_components/datatables.net-bs/css/dataTables.bootstrap.min.css') }}"> 
    @endstack
    ```

    **b. 
    ```php
    @push('styles') 
        <link rel="stylesheet" href="{{ asset('assets/bower_components/datatables.net-bs/css/dataTables.bootstrap.min.css') }}"> 
    @endpush
    ```
    **

    c. 
    ```php
    @section('styles') 
        <link rel="stylesheet" href="{{ asset('assets/bower_components/datatables.net-bs/css/dataTables.bootstrap.min.css') }}"> 
    @endsection
    ```

    d.
    ```php
    @sections('styles') 
        <link rel="stylesheet" href="{{ asset('assets/bower_components/datatables.net-bs/css/dataTables.bootstrap.min.css') }}"> 
    @endsections
    ```

88. Pada index.blade.php library javascript datatables bisa diletakkan...

    a. sebelum @section('content')

    b. didalam @section('content')

    c. didalam @push('styles')

    **d. didalam @push('scripts')**

# Menyiapkan Dashboard User

## Membuat Tampilan Halaman Depan

89. Selain Bootstrap kita dapat membuat frontend framework css dengan...

    a. Material icon

    **b. Materialize**

    c. Font awesome

    d. Jquery

90. Pada materialize saat klik menu pada sidenav tidak dapat berjalan maka solusi nya adalah...

    a. ``<script> init(); </script>``

    b. ``<script> Init(); </script>``

    c. ``<script> M.Init(); </script>``

    **d. ``<script> M.AutoInit(); </script>``**

91. Pada materialize saat icon tidak muncul maka solusi nya adalah...

    **a. ``<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">``**

    b. ``<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet">``

    c. ``<link href="https://fonts.googleapis.com/css?family=Tenor Sans" rel="stylesheet">``

    d. ``<link href="https://cdn.datatables.net/1.11.0/css/jquery.dataTables.min.css" rel="stylesheet">``

## Membuat Template Halaman Depan

92. Pada frontend/tampilan halaman homepage dapat dibuatkan template menjadi beberapa partials file yaitu...

    a. head, sidebar, script

    b. navigation, style. script

    **c. head, navigation, script**

    d. head, header, script

93. View [frontend.templates.partials.head] not found artinya...

    a. tidak folder head pada directory frontend.templates.partials

    b. tidak file head pada directory frontend.templates.partials.head

    **c. tidak file head pada directory frontend.templates.partials**

    d. tidak file default pada directory frontend.templates.partials

## Menampilkan Data Buku di Halaman Depan

94. Source code untuk mengatur tinggi gambar menjadi 200 pixel adalah...

    a. ``<img src="{{ $book->getCover }}" width="200%">``

    b. ``<img src="{{ $book->getCover }}" width="200px">``

    c. ``<img src="{{ $book->getCover() }}" height="200%">``

    **d. ``<img src="{{ $book->getCover() }}" height="200px">``**

95. Apabila dalam card ukuran nya berbeda dikarenakan terlalu panjangnya judul, source code untuk meringkas nya dalam laravel 6 yaitu...

    **a. {{ Str::limit($book->title, 30) }}**

    b. {{ str::limit($book->title, 30) }}

    c. {{ str_limit($book->title, 30) }}

    d. {{ string::limit($book->title, 30) }}

96. Source code untuk membuat data buku dengan pagination pada setiap page nya berjumlah 10 yaitu...

    a. $book = Book::pagination(10);

    b. $book = Book::get()->pagination(10);

    **c. $book = Book::paginate(10);**
    
    d. $book = Book::get()->paginate(10);

## Membuat Pagination Custom

97. Perintah artisan untuk melihat vendor-vendor yang terdaftar pada aplikasi laravel adalah

    a. php artisan list:vendor

    **b. php artisan vendor:publish**

    c. php artisan vendor:publish -list

    d. php artisan vendor:publish --list

98. Vendor ang perlu dipublish untung membuat custom pagination adalah...

    a. Illuminate\Pagination\PaginationServiceProvider

    b. Spatie\Permission\PermissionServiceProvider

    **c. laravel-pagination**

    d. config

99. Source code untuk memanggil file pagination custom yaitu materialize dari laravel-pagination adalah...

    a. ``{{ $book->links('default') }}``

    b. ``{{ $book->links('materialize') }}``

    c. ``{{ $book->links('vendor.pagination.default') }}``

    **d. ``{{ $book->links('vendor.pagination.materialize') }}``**

## Menyesuaikan Tampilan Register

100. Source code untuk merubah template register ke frontend.templates.default adalah

    a. @yield('frontend.templates.partials.default')

    b. @include('frontend.templates.partials.default')

    **c. @extends('frontend.templates.partials.default')**

    d. @section('frontend.templates.partials.default')

101. Class materialize untuk membuat icon berada didepan adalah...

    a. suffix

    **b. prefix**

    c. prev

    d. next

102. Source code untuk mempercantik tampilan error dengan menggunakan materialize adalah...

    a. class="@error('name') is-invalid @enderror"

    **b. class="@error('name') invalid @enderror"**

    c. class="@error('name') is-valid @enderror"

    d. class="@error('name') valid @enderror"

## Menyesuaikan Tampilan Login

103. Apa saja form/field yang dibutuhkan untuk login?   
    
    a. name, email, password, password confirmation

    b. email, password, password confirmation

    c. name, email, password

    **d. email, password**

104. Source code yang benar untuk form login adalah..

    **a. <form action="{{ route('login') }}" method="POST"> @csrf </form>**

    b. <form action="{{ route('admin.login') }}" method="POST"> @csrf </form>

    c. <form action="{{ route('user.login') }}" method="POST"> @csrf </form>

    d. <form action="{{ route('signin') }}" method="POST"> @csrf </form>

105. Source code untuk mengubah text button dari Register ke Login adalah

    a. <input type="submit" class="vawes-effect waves-light btn red accent-1"> Login

    b. <input type="submit" value="" class="vawes-effect waves-light btn red accent-1"> Login

    **c. <input type="submit" value="Login" class="vawes-effect waves-light btn red accent-1">**

    d. <input type="submit" id="Login" class="vawes-effect waves-light btn red accent-1">

## Membuat Halaman Detail Buku

106. Source code untuk membuat route dengan BookController dengan method show yang berada pada direktory Frontend adalah
    
    a. Route::get('/book/{book}', 'BookController@show')->name('book.show');

    b. Route::get('/book/{book}', 'Frontend\BookController@show')->name('book.show');

    **c. Route::get('/book/{book}', 'Frontend\\BookController@show')->name('book.show');**

    d. Route::get('/book/{book}', 'Frontend//BookController@show')->name('book.show');

107. Salah satu method untuk melihat/mengecek nilai objek dari book didalam controller adalah
    
    **a. dd($book);**

    b. console.log($book);

    c. printf($book);

    d. show($book);

108. Source code untuk menjadikan judul buku sebagai link untuk show detail buku adalah
    
    a. <a href="{{ route('book.show', $book) }}"> {{ Str::limit($book->title) }} </a>

    b. <a href="{{ route('book.show', $book->id) }}"> {{ Str::limit($book->title) }} </a>

    c. <a href="{{ route('book.show/{$book}') }}"> {{ Str::limit($book->title) }} </a>

    **d. a dan b benar**

## Membuat Section Buku Lainnya Dari Penulis

109. Pada model author terdapat method books yang dimana relasinya satu author dapat memiliki banyak buku. Source code untuk mendapatkan data buku lainnya berdasarkan author adalah...

    **a. @foreach($book->author->books)**

    b. @foreach($book->author->books())

    c. @foreach($book->author()->books)

    d. @foreach($book->author()->books())

110. Method untuk mendapatkan data 4 jumlah data adalah..

    a. get(4)

    **b. take(4)**

    c. max(4)

    d. min(4)

111. Method untuk mendapatkan data secara acak adalah

    a. rand()

    b. random()

    **c. shuffle()**

    d. inRandom()

## Membuat Fungsi Pinjam Buku

112. Terdapat error Missing required parameters for [Route:book.borrow][URI:book/{book}/borrow] solusi nya adalah 

    **a. {{ route('book.borrow', $book) }}**

    b. {{ route(('book.borrow'), $book) }}

    c. {{ route('book.borrow/$book') }}

    d. {{ route('book.borrow/'.$book) }}

113. Source code untuk membuat fungsi borrow dengan menggunakan model BorrowHistory adalah...

    a.
    ```
    BorrowHistory::create([
        'user_id' => Auth,
        'book_id' => $book
    ])
    ```

    b.
    ```
    BorrowHistory::create([
        'user_id' => Auth::id,
        'book_id' => $book->id
    ])
    ```

    c.
    ```
    BorrowHistory::create([
        'user_id' => auth()->id,
        'book_id' => $book
    ])
    ```

    **d.
    ```
    BorrowHistory::create([
        'user_id' => auth()->id,
        'book_id' => $book->id
    ])
    ```
    **

114. Source code agar route book.borrow hanya dapat diakses oleh user yang login adalah

    a. Route::post('book/{book}/borrow', 'Frontend\\BookController@borrow')->name('book.borrow')->prefix('auth');

    b. Route::post('book/{book}/borrow', 'Frontend\\BookController@borrow')->name('book.borrow')->prefix('user');

    **c. Route::post('book/{book}/borrow', 'Frontend\\BookController@borrow')->name('book.borrow')->middleware('auth');**
 
    d. Route::post('book/{book}/borrow', 'Frontend\\BookController@borrow')->name('book.borrow')->middleware('user');

## Fungsi Pinjam Buku dengan Eloquent Relationship

115. Source code untuk menambahkan relasi belongsToMany borrow_history pada model User adalah...
    
    **a.
    ```
    public function borrow()
    { 
        return $this->belongsToMany(Book::class, 'borrow_history'); 
    }
    ```
    **

    b.
    ```
    public function borrow()
    { 
        return $this->belongsToMany(User::class, 'borrow_history'); 
    }
    ```

    c.
    ```
    public function borrowed()
    { 
        return $this->belongsToMany(Book::class, BorrowHistory); 
    }
    ```

    d.
    ```
    public function borrowed()
    { 
        return $this->belongsToMany(User::class, BorrowHistory); 
    }
    ```

116. Source code untuk redirect ke halaman yang sama adalah
    
    **a. return redirect()->back();**

    b. return redirect()->route()->back();

    c. return redirect()->prev();

    d. return redirect()->route()->prev();

117. Source code untuk menambahkan buku yang dipinjam melalui user yang login 
    
    a.
    ```
    $user = auth()->id;
    $user->borrow()->attach($book);
    ```

    **
    b.
    ```
    $user = auth()->user();
    $user->borrow()->attach($book);
    ```
    **

    c.
    ```
    $user = auth()->id;
    $user->borrow()->create($book);
    ```

    d.
    ```
    $user = auth()->user();
    $user->borrow()->create($book);
    ```

## Menyempurnakan Proses Peminjaman Buku

118. Dalam materialize untuk menampilkan pesan feedback adalah

    a. alert

    b. dialog

    **c. toasts**

    d. flash message

119. Source code untuk mengurangi qty saat meminjam buku

    a. $book->increment('qty');

    **b. $book->decrement('qty');**

    c. $book->min('qty');

    d. $book->qty - 1;

120. Source code agar tidak boleh meminjam buku yang sama adalah
    
    **a. if($user->borrow()->where('books.id', $book->id)->count() > 0)**

    b. if($user->borrow()->where('books.id', $book->id)->count() >= 0)

    c. if($user->borrow()->where('books.id', $book->id)->count() == 0)

    d. if($user->borrow()->where('books.id', $book->id)->count != 1)

# Finalisasi Sistem Perpustakaan

## Membenahi Navigasi _ Relasi User dan Buku

121. Syntax directive blade yang berfungsi untuk mengecek menu login dan register hanya bisa diakses oleh user yang belum login adalah...
    
    a. 
    ```
    @auth
        <li><a href="{{ route('login') }}">Login</a></li>
        <li><a href="{{ route('Register') }}">Register</a></li> 
    @endauth
    ```

    **b. 
    ```
    @guest 
        <li><a href="{{ route('login') }}">Login</a></li>
        <li><a href="{{ route('register') }}">Register</a></li>
    @endguest
    ```
    **

    c.
    ``` 
    @unless 
        <li><a href="{{ route('login') }}">Login</a></li>
        <li><a href="{{ route('register') }}">Register</a></li>
    @endunless
    ```
    d. 
    ```
    @once 
        <li><a href="{{ route('login') }}">Login</a></li>
        <li><a href="{{ route('Register') }}">Register</a></li>
    @endonce
    ```

122. Solusi agar created_at dan updated_at memiliki value/nilai saat meminjam buku dan update peminjaman buku adalah

    a. return belongsToMany(Book::class, 'borrow_history')->withTime();

    b. return belongsToMany(Book::class, 'borrow_history')->withDateTime();

    c. return belongsToMany(Book::class, 'borrow_history')->withTimestamp();

    **d. return belongsToMany(Book::class, 'borrow_history')->withTimestamps();**

123. Source code untuk mentrigger form post logout dengan id logout-form adalah...

    **a.
    ```
    <li><a href="{{ route('logout')}}" 
        onclick="event.preventDefault(); 
        document.getElementById('logout-form').submit();">Logout</a>
    </li>
    ```
    **

    b.
    ```
    <li><a href="{{ route('logout')}}" 
        onclick="event.preventDefault(); 
        document.getElementByClass('logout-form').submit();">Logout</a>
    </li>
    ```

    c.
    ```
    <li><a href="{{ route('logout')}}" 
        onclick="event.preventDefault(); 
        document.getElementByTag('logout-form').submit();">Logout</a>
    </li>
    ```

    d.
    ```
    <li><a href="{{ route('logout')}}" 
        onclick="event.preventDefault(); 
        document.write('logout-form').submit();">Logout</a>
    </li>
    ```

## Menampilkan Daftar Buku Yang Sedang Dipinjam

124. Source code untuk menampilkan data buku yang dipinjam oleh user yang sedang login adalah...
    
    a. $books = auth()->user()->books();

    **b. $books = auth()->user()->borrrow();**

    c. $books = auth()->user()->borrrowed();

    d. $books = auth()->user()->borrow()->book();

125. Apa saja sebaiknya yang ditampilkan pada halaman buku yang sedang dipinjam

    a. sampul buku, judul, descripsi, author, jumlah buku, tombol pinjam buku

    b. sampul buku, judul, descripsi, author, jumlah buku

    **c. sampul buku, judul, descripsi, author**

    d. sampul buku, descripsi, author

## Memperbaiki Tombol Pinjam di Halaman Detail

126. Solusi saat tombol Pinjam buku tidak berfungsi adalah dengan mengetikkan source code...
    
    a.
    ```
    <form action="{{ route('book.borrow') }}" method="GET">
        @csrf
        <input type="submit" value="Pinjam Buku" class="btn red accent-1 right waves-effect waves-light">
    </form>
    ```

    b.
    ```
    <form action="{{ route('book.borrow') }}" method="POST">
        @csrf
        <input type="submit" value="Pinjam Buku" class="btn red accent-1 right waves-effect waves-light">
    </form>
    ```

    c.
    ```
    <form action="{{ route('book.borrow', $book) }}" method="GET">
        @csrf
        <input type="submit" value="Pinjam Buku" class="btn red accent-1 right waves-effect waves-light">
    </form>
    ```

    **d.
    ```
    <form action="{{ route('book.borrow', $book) }}" method="POST">
        @csrf
        <input type="submit" value="Pinjam Buku" class="btn red accent-1 right waves-effect waves-light">
    </form>
    ```
    **

## Membuat Komponen Card Buku

127. Agar mudah untuk merubah card yang sama pada halaman utama dan detail buku maka perlu dibuatkan...

    **a. components card**

    b. fungsi baru

    c. controller baru

    d. semua benar

128. Syntax blade directive untuk menasukan component adalah

    a. @component('frontend.templates.components.card-book') @endcomponent

    b. @components('frontend.templates.components.card-book') @endcomponents

    c. @include('frontend.templates.components.card-book')

    **d. a dan c benar**

129. Cara passing variable di dalam directive component adalah

    a. @component('frontend.templates.components.card-book', $book) @endcomponent

    **b. @component('frontend.templates.components.card-book', ['book' => $book]) @endcomponent**

    c. @components('frontend.templates.components.card-book', $book) @endcomponents

    d. @components('frontend.templates.components.card-book', ['book' => $book]) @endcomponents

## Admin Daftar Buku yang Dipinjam

130. Sytanx menampilkan data peminjaman buku urut secara terbaru adalah...

    a. $borrows = BorrowHistory::latest();

    b. $borrows = BorrowHistory::updated();

    c. $borrows = BorrowHistory::orderBy('created_at', 'DESC');

    **d. a dan c benar**

131. Agar pada borrow history dapat mengetahui nama user nya siapa dan judul buku nya apa maka perlu menambahkan relasi pada model BorrowHistory...

    **a. user dan book dengan relasi belongsTo**

    b. author dan book dengan relasi belongsTo

    c. user dan book dengan relasi hasMany

    d. author dan book dengan relasi hasMany

132. Apa saja action pada halaman pinjam buku?
    
    a. hapus

    b. edit, hapus

    c. lihat detail, edit, hapus

    **d. Pengembalian Buku**

## Fungsi Pengembalian Buku

133. Perintah artisan untuk membuat column/field baru pada tabel borrow_history dengan migration yaitu... 

    a. php artisan make:migration add_returned_at_and_receiver_user_id_on_borrrow_table table=borrow_history

    b. php artisan make:migration add_returned_at_and_receiver_user_id_on_borrrow_table -table=borrow_history

    **c. php artisan make:migration add_returned_at_and_receiver_user_id_on_borrrow_table --table=borrow_history**

    d. php artisan make:migration add_returned_at_and_receiver_user_id_on_borrrow_table --t=borrow_history

134. Pada column returned_at menggunakan dateTime, untuk dateTime kita dapat memanfaatkan library...

    a. Faker

    **b. Carbon**

    c. Guzzle

    d. Phpunit

135. Cara menggunakan carbon yang benar adalah...

    a. 'returned_at' => Carbon::create()

    b. 'returned_at' => $carbon->create()

    **c. 'returned_at' => Carbon::now()**

    d. 'returned_at' => $carbon->now()

## Menampilkan Hanya Buku yang Sedang Dipinjam

136. Source code agar data buku yang dikembalikan tidak tampil di halaman data peminjaman buku adalah...

    **a. $borrow = BorrowHistory::where('returned_at', null)->latest();**

    b. $borrow = BorrowHistory::where('returned_at', now())->latest();

    c. $borrow = BorrowHistory::where('created_at', null)->latest();

    d. $borrow = BorrowHistory::where('created_at', now())->latest();

137. Cara membuat scope function yang benar adalah

    a.
    ```
    public function scopeIsBorrowed()
    {
        return $query->where('returned_at', null);
    }
    ```

    **b.
    ```
    public function scopeIsBorrowed($query)
    {
        return $query->where('returned_at', null);
    }
    ```
    **

    c.
    ```
    public function scopeisborrowed()
    {
        return where('returned_at', null);
    }
    ```

    d.
    ```
    public function isBorrowed($query)
    {
        return $query->where('returned_at', null);
    }
    ```

138. Cara memanggil scope function yang benar adalah

    a. $borrows = BorrowHistory::scopeIsborrowed()->latest();

    b. $borrows = BorrowHistory::scopeIsborrowed('returned_at', null)->latest();

    **c. $borrows = BorrowHistory::isborrowed()->latest();**

    d. $borrows = BorrowHistory::isborrowed('returned_at', null)->latest();

## Judul Halaman Dinamis Untuk Frontend

## Menangani Masalah n+1

139. Mengambil data dari database dengan melooping data dan mengakibatkan memanggil query yang sama berulang-ulang adalah masalah...
    
    a. 1+1

    **b. n+1**

    c. n+n

    d. b dan c benar

139. Solusi untuk permasalah n+1 adalah dengan menggunakan...

    a. eager load

    b. lazy load

    c. with load

    **d. a dan b benar**

140. Source code yang benar untuk menggunakan lazy load adalah

    **a. 
    ```
    $book = Book::orderBy('title', 'ASC')->get();
    $book->load('author');
    ```
    **

    b.
    ```
    $book = Book::orderBy('title', 'ASC')->get();
    $book->with('author');
    ```

    c.
    ```
    $book = Book::orderBy('title', 'ASC')->get();
    $book->lazy('author');
    ```

    d. a dan b benar

# Perbaikan Fitur Dashboard Admin Update 1

## Menambahkan Kuantitas Untuk Buku yang Dikembalikan

142. Pada source code dibawah agar table data dapat terisi data dengan dataTable maka perlu menambahkan source code...
    ```
    <tr>
        <th>Id</th>
        <th>Judul</th>
        <th>Deskripsi</th>
        <th>Jumlah Buku</th>
    </tr>
    ```
    
    a. 
    ```
        columns: [
            { data: 'DT_RowIndex', orderable: false, searchable: false }
            { data: 'title' }
            { data: 'description' }
            { data: 'qty' }
        ]
    ```

    b. 
    ```
        columns: [
            { data: 'DT_RowIndex', orderable: false, searchable: false };
            { data: 'title' };
            { data: 'description' };
            { data: 'qty' };
        ]
    ```

    **c. 
    ```
        columns: [
            { data: 'DT_RowIndex', orderable: false, searchable: false },
            { data: 'title' },
            { data: 'description' },
            { data: 'qty' }
        ]
    ```
    **

    d. 
    ```
        columns: [
            data: 'DT_RowIndex', orderable: false, searchable: false,
            data: 'title',
            data: 'description',
            data: 'qty';
        ]
    ```
    

143. Source code untuk menambahkan qty saat buku dikembalikan adalah...
    
    a. ``$borrowHistory->book->increment('qty');``

    b. ``$borrowHistory->book->decrement('qty');``

    **c. ``$borrowHistory->book()->increment('qty');``**

    d. ``$borrowHistory->book()->decrement('qty');``

144. ``$borrowHistory->book`` Artinya dapat memanggil relasi book dan dapat mengakses...

    **a. property book**

    b. method model book

    c. scope function book
    
    d.  a dan b benar

## Fix Bug Pada Pengecekan Buku Dipinjam

145. Solusi untuk mengatasi bug meminjam buku tetapi buku yang dipinjam sudah dikembalikan maka perlu menambahkan source code...
    
    **a. ->where('returned_at', null)**

    b. ->where('returned_at', =, null)

    c. ->where('returned_at', !, null)

    d. ->where('returned_at', !=, null)

146. Source code untuk menyederhanakan pinjam buku dengan scope function adalah...

    a. 
    ```php
    public function scopeIsStillBorrow($query, $bookId){
        return $query->where('books.id', $bookId)
        ->where('returned_at', null)
        ->count() < 0;
    }
    ```

    b.
    ```php
    public function scopeIsStillBorrow($query, $bookId){
        return $query->where('books.id', $bookId)
        ->where('returned_at', null)
        ->count() <= 0;
    }
    ```

    **c.
    ```php
    public function scopeIsStillBorrow($query, $bookId){
        return $query->where('books.id', $bookId)
        ->where('returned_at', null)
        ->count() > 0;
    }
    ```
    **

    d.
    ```php
    public function scopeIsStillBorrow($query, $bookId){
        return $query->where('books.id', $bookId)
        ->where('returned_at', null)
        ->count() >= 0;
    }
    ```

147. Source code untuk memanggil scope function isStillBorrow adalah...

    a. $user->borrow->isStillBorrow($book->id)

    **b. $user->borrow()->isStillBorrow($book->id)**

    c. $user->borrow->scopeIsStillBorrow($book->id)

    d. $user->borrow()->scopeIsStillBorrow($book->id)

## Membuat Halaman Laporan Buku Paling Banyak Dipinjam

148. Source code untuk menampilkan buku yang paling banyak dipinjam dengan 10 data per pagenya dan menampilkan jumlah data yang dipinjam adalah... 

    a. Book::withCount('borrowed')->orderBy('book_count', 'asc')->paginate(10);

    b. Book::withCount('borrowed')->orderBy('book_count', 'asc')->paginate(10);

    c. Book::withCount('borrowed')->orderBy('borrowed_count', 'asc')->paginate(10);

    **d. Book::withCount('borrowed')->orderBy('borrowed_count', 'desc')->paginate(10);**

149. Source code untuk menampilkan jumlah buku dipinjam dengan withCount adalah...
    
    a. {{ $book->count }}

    b. {{ $book->count() }}

    c. {{ $book->borrowed->count }}

    **d. {{ $book->borrowed_count }}**

150. fungsi orderBy saat tidak di set parameter keduanya asc atau desc maka yang terjadi adalah...

    a. error

    **b. urut secara ascending**

    c. urut secara descending

    d. random

## Membuat Halaman Laporan User Teraktif

151. Fungsi diffForHumans() akan menampilkan?

    a. Hari, tanggal, bulan, dan tahun

    b. tanggal, nomer bulan, dan tahun

    c. tanggal, nama bulan, dan tahun 

    **d. berapa hari/bulan/tahun yang lalu**

152. Berikut ini source code untuk membuat breadcrumbs yang benar adalah...

    a. 
    ```php
    Breadcrumbs::for('admin.report.top-book', function($trail) {
        push('Beranda', route('admin.dashboard'));
    });
    ```

    b. 
    ```php
    Breadcrumbs::push('admin.report.top-book', function($trail) {
        for('Beranda', route('admin.dashboard'));
    });
    ```

    **c. 
    ```php
    Breadcrumbs::for('admin.report.top-book', function($trail) {
        push('Beranda', route('admin.dashboard'));
    });
    ```
    **

    d. 
    ```php
    Breadcrumbs::for('admin.report.top-book', function($trail) {
        for('Beranda', route('admin.dashboard'));
    });
    ```

## Penomoran Data Diluar DataTable

153. Apa output yang terjadi saat ada source code dibawah dan halaman terdapat pagination? 
    ```php 
    @php 
        $no = 1;
    @endphp
    @foreach($books as $book)
    <tr>
        <td> {{ $no++ }} </td>
    </tr>
    @endforeach 
    ```
    a. Nomer akan urut dari 0 sampai akhir dari jumlah row tabel book

    b. Nomer akan urut dari 0 sampai akhir dari jumlah row tabel book dan saat pindah pagination ulang dari nomer 0 lagi

    c. Nomer akan urut dari 1 sampai akhir dari jumlah row tabel book

    **d. Nomer akan urut dari 1 sampai akhir dari jumlah row tabel book dan saat pindah pagination ulang dari nomer 1 lagi**

154. Source code untuk membuat penomoran otomatis dan setiap pindah page nomer tidak akan ulang dari nomer 1 lagi adalah...

    a. 
    ```php
    @php
        $page = 1;
        if(request()->has('page')){
            $page = request('page');
        }
        $no = (10 * page) - (10);
    @endphp
    ```

    b.
    ```php
    @php
        $page = 1;
        if(request()->has('page')){
            $page = request('page');
        }
        $no = (10 * page) - (10-page);
    @endphp
    ```

    **c.
    ```php
    @php
        $page = 1;
        if(request()->has('page')){
            $page = request('page');
        }
        $no = (10 * page) - (10-1);
    @endphp
    ```
    **

    d.
    ```php
    @php
        $page = 1;
        if(request()->has('page')){
            $page = request('page');
        }
        $no = (10 * page) - (page-10);
    @endphp
    ```

155. Cara memanggil environment variable pada code ini ``PAGINATION_ADMIN=15`` adalah...

    a. {{ $PAGINATION_ADMIN }}

    **b. env('PAGINATION_ADMIN')**

    c. env($PAGINATION_ADMIN)
    
    d. environment("PAGINATION_ADMIN")
