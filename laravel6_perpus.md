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

58. Source code untuk membuat session adalah

    a. with('success', 'Data berhasil disimpan');

    b. with(['success', 'Data berhasil disimpan']);

    **c. session('success', 'Data berhasil disimpan');**

    d. session(['success', 'Data berhasil disimpan']);

59. Source code untuk menampilkan alert atau flash message adalah

    a. 
    ```
    @if(with('success'))
        {{ with('success') }}
    @endif
    ```

    b. 
    ```
    @if(message('success'))
        {{ message('success') }}
    @endif
    ```

    **c. 
    ```
    @if(session('success'))
        {{ session('success') }}
    @endif
    ```
    **

    d. 
    ```
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

    a. value="{{ $name }}

    b. value="{{ $old('name') }}

    **c. value="{{ old('name') }}**

    d. value="{{ ('name') }}

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

    a. Route::resource('author', 'AuthorController@index')

    b. Route::resource('author', 'AuthorController@create')

    c. Route::resource('author', 'AuthorController@store')

    **d. Route::resource('author', 'AuthorController')**

## Menampilkan Data Modul Buku

73. cara menambahkan variable title pada controller agar bisa diakses pada halaman index adalah...

    a. return view('index')->(['title' => 'Perpus']);

    **b. return view('index', ['tilte' => 'Perpus']);** 

    c. return view('index')->(['title' = 'Perpus']);

    d. return view('index', ['tilte' = 'Perpus']);

74. Source code menambahkan relasi 1 author memiliki banyak buku adalah...

    **a. 
    ```
    public function books(){
        return $this->hasMany(Book::class);
    }
    ```
    **

    b.
    ```
    public function books(){
        return $this->hasMany('Book');
    }
    ```

    c.
    ```
    public function books(){
        return $this->belongsTo(Book::class);
    }
    ```

    d.
    ```
    public function books(){
        return $this->belongsTo('Book');
    }
    ```

75. Source code untuk mengambil data nama author melalui model book adalah...

    a. 
    ```
    function(Book $book){
        return $book->name;
    }
    ```

    b.
    ```
    function(Book $book){
        return $book->author()->name;
    }
    ```

    **c. 
    ```
    function(Book $book){
        return $book->author->name
    }
    ```
    **

    d.
    ```
    function(Book $book){
        return $book->$author->name
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

    a.`` $('.select2').select2;``

    **b. ``$('.select2').select2();``**

    c. ``$(['.select2']).select2;``

    d. ``$(['.select2']).select2();``

## Membuat Fungsi Simpan Buku _ Menanangani Asset Gambarnya

79. Dalam table books pada field cover terdapat berbagai macam value diantaranya picsum, assets dan null untuk get data cover dengan macam ini penanganannya adalah...

    **a.
    ```
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
    ```
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
    ```
    public function getCover(){
        if(substr($this->cover,0,5) == "https"){
            return assets($this->cover);
        }

        if($this->cover){
            return $this->cover;
        }

        return 'via.placeholder.com/728x90.png?text=No+Cover';
    }
    ```

    d.
    ```
    public function getCover(){
        if(substr($this->cover,1,5) == "https"){
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
    ```
    ->editColumn('cover', function(Book $model) {
        return '<img src="'. $model->getCover .'" height="150px">';
    })
    ```

    **b. 
    ```
    ->editColumn('cover', function(Book $model) {
        return '<img src="'. $model->getCover() .'" height="150px">';
    })
    ```
    **

    c. 
    ```
    ->editColumn('cover', function(Book $model) {
        return '<img src="'. $model->cover .'" height="150px">';
    })
    ```

    d. 
    ```
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
    ``` 
    <option value="{{ $author->id }}"
        @if($author->id = $book->author_id)
            selected
        @endif
    >
    ```

    **b.
    ``` 
    <option value="{{ $author->id }}"
        @if($author->id === $book->author_id)
            selected
        @endif
    >
    ```
    **

    c. 
    ```
    <option value="{{ $author->id }}">
    @if($author->id = $book->author_id)
        selected
    @endif
    ```

    d. 
    ```
    <option value="{{ $author->id }}">
    @if($author->id === $book->author_id)
        selected
    @endif
    ```

84. Source code untuk update/ubah data buku jika cover tidak diubah maka akan tetap menyimpan cover yang lama jika diubah maka akan menyimpan cover yang baru dengan menghapus cover yang lama adalah...

    a.
    ``` 
    $cover = null;
    if($request->hasFile('cover')){
        Storage::delete($book->cover);
        $cover = $request->file('cover')->store('assets/covers');
    }
    ```

    b.
    ``` 
    $cover = null;
    if($request->hasFile('cover')){
        Storage::destroy($book->cover);
        $cover = $request->file('cover')->store('assets/covers');
    }
    ```

    **c.
    ``` 
    $cover = $book->cover;
    if($request->hasFile('cover')){
        Storage::delete($book->cover);
        $cover = $request->file('cover')->store('assets/covers');
    }
    ```
    **

    d.
    ``` 
    $cover = $book->cover;
    if($request->hasFile('cover')){
        Storage::destroy($book->cover);
        $cover = $request->file('cover')->store('assets/covers');
    }
    ```

## Menghapus Data Buku

85. Source code yang benar untuk membuat fungsi hapus buku pada controller adalah...

    a. 
    ```
    public function destroy(){
        $book->delete();
        return redirect()->route('admin.book.index')->withDanger('Data buku berhasil dihapus');
    }
    ```

    b. 
    ```
    public function destroy($id){
        $book->delete();
        return redirect()->route('admin.book.index')->withDanger('Data buku berhasil dihapus');
    }
    ```

    **c. 
    ```
    public function destroy(Book $book){
        $book->delete();
        return redirect('admin.book.index')->route()->withDanger('Data buku berhasil dihapus');
    }
    ```
    **

    d. 
    ```
    public function destroy(Book $book){
        $book->delete();
        return redirect()->route('admin.book.index')->withDanger('Data buku berhasil dihapus');
    }
    ```

86.

87.

## Tips Menangani Aset Project

88. dataTables.bootstrap.min.css dibutuhkan hanya pada file index karena itu sebelum tutup head perlu menambahkan syntax

    **a. @stack('styles')**

    b. @push('styles')

    c. @yield('styles')

    d. @section('styles')

89. Source code untuk memanggil memanggil dataTables.bootstrap.min.css pada file index.blade.php adalah...

    a. 
    ```
    @stack('styles') 
        <link rel="stylesheet' href='{{ asset('assets/bower_components/datatables.net-bs/css/dataTables.bootstrap.min.css')}}'> 
    @endstack
    ```

    **b. 
    ```
    @push('styles') 
        <link rel="stylesheet' href='{{ asset('assets/bower_components/datatables.net-bs/css/dataTables.bootstrap.min.css')}}'> 
    @endpush
    ```
    **

    c. 
    ```
    @section('styles') 
        <link rel="stylesheet' href='{{ asset('assets/bower_components/datatables.net-bs/css/dataTables.bootstrap.min.css')}}'> 
    @endsection
    ```

    d.
    ```
    @sections('styles') 
        <link rel="stylesheet' href='{{ asset('assets/bower_components/datatables.net-bs/css/dataTables.bootstrap.min.css')}}'> 
    @endsections
    ```

90. Pada index.blade.php library javascript datatables bisa diletakkan...

    a. sebelum @section('content')

    b. didalam @section('content')

    c. didalam @push('styles')

    **d. didalam @push('scripts')**

# Menyiapkan Dashboard User

## Membuat Tampilan Halaman Depan

91. Selain Bootstrap kita dapat membuat frontend framework css dengan...

    a. Material icon

    **b. Materialize**

    c. Font awesome

    d. Jquery

92. Pada materialize saat klik menu pada sidenav tidak dapat berjalan maka solusi nya adalah...

    a. ``<script> init();  </script>``

    b. ``<script> Init();  </script>``

    c. ``<script> M.Init();  </script>``

    **d. ``<script> M.AutoInit();  </script>``**

93. Pada materialize saat icon tidak muncul maka solusi nya adalah...

    **a. ``<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">``**

    b. ``<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet">``

    c. ``<link href="https://fonts.googleapis.com/css?family=Tenor Sans" rel='stylesheet'>``

    d. ``<link href="https://cdn.datatables.net/1.11.0/css/jquery.dataTables.min.css" rel='stylesheet'>``

## Membuat Template Halaman Depan

94.