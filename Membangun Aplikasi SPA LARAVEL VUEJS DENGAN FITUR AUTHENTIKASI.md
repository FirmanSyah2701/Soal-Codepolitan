# MEMBANGUN APLIKASI SPA LARAVEL VUEJS DENGAN FITUR AUTHENTIKASI

## SETUP PROJECT LARAVEL PASSPORT

1. Apa yang dimaksud dengan laravel passport...

     **A. Package yang ada dilaravel untuk menghandle proses authentication dengan token.**

    B. Package yang ada dilaravel untuk menghandle proses authentication tanpa token

    C. Package yang ada dilaravel untuk menghandle proses authorization dengan token

    D. Package yang ada dilaravel untuk menghandle proses authorization tanpa token

2. Package manager yang digunakan untuk membuat project baru di laravel adalah...
    
    A. NPM
    
    B. PIP
    
    **C. Composer**
    
    D. GEMS

3. Perintah untuk membuat project baru dilaravel adalah...
    
    A. Composer project-create laravel/laravel nama_project

    B. Composer project-create laravel/nama_project
    
    **C. Composer create-project laravel/laravel nama_project**
    
    D. Composer create-project laravel/nama_project 


4. Cara menambahkan package laravel passport adalah...
    
    A. Composer include laravel/passport
    
    B. Composer included laravel/passport
    
    C. Composer required laravel/passport
    
      **D. Composer require laravel/passport**

## Api Endpoint Register


5. Cara membuat RegisterController adalah...

    A. php artisan create:controller Api/Auth/RegisterController

    B. php artisan install:controller Api/Auth/RegisterController

    **C. php artisan make:controller Api/Auth/RegisterController**

    D. php artisan build:controller Api/Auth/RegisterController

6. Cara agar di dalam route laravel tidak perlu ditambahkan nama method setelah nama file controller adalah dengan fungsi...

    A. register()

    **B. __invoke()**

    C. Invoke()

    D. __construct()

7. Fungsi untuk membuat data user baru di dalam database adalah...
   
    **A. User::create();**

    B. User::make();
    
    C. User::built();
    
    D. User::build();

8. Syntax untuk menjalankan enkripsi password adalah...
    
    A. Hash::make($password);
    
    B. Hash::create($password);
    
    C. Hash::create($reques->password);
    
    **D. Hash::make($request->password);**

9. if(!Auth::attempt(request->only('email', 'password'))) adalah kondisi jika...
    
    A. Proses authentikasi success
    
    B. Proses authentikasi selesai
    
    **C. Proses authentikasi failed**
    
    D. Proses authentikasi berhenti

10. Apa response status code dari Response::HTPP_UNPROCESSABLE_ENTITY...
    
    A. 420
    
    B. 421
    
    **C. 422**
    
    D. 423

11. Response status code 201 artinya...
    
    A. OK
    
    **B. Created**
    
    C. Server Error
    
    D. Not Found
 
## Api Endpoint Login dan logout

12. Isi data $request->validate() yang ada di method login adalah...
    
    **A. Email dan password**

    B. Nama, Email dan Password

    C. Email saja

    D. Nama saja

13. Isi response json login saat berhasil login adalah...
    
    A. return response([
	    "message" => "success",
	    "data" => $user;
	    "meta" => [
		    "token" => $accessToken
	    ]
        ], Response::HTPP_CREATED);
    
    **B. return response([
	    "message" => "success",
	    "data" => Auth::user();
	    "meta" => [
		    "token" => $accessToken
	    ]
        ], Response::HTPP_CREATED);**

    C. return response([
	    "message" => "success",
	    "data" => $user;
	    "meta" => [
		"token" => $accessToken
	    ]
        ], Response::HTPP_UNPROCESSABLE_ENTITY);
    
    D. return response([
	    "message" => "success",
	    "data" => Auth::user();
	    "meta" => [
		"token" => $accessToken
	    ]
        ], Response::HTPP_UNPROCESSABLE_ENTITY);

14. Syntax apa yang ada pada fungsi logout?
    
    **A. Auth::user()->token()->revoke();**

      B. Auth::user()->revoke();

      C. Auth::user()->token()->logout();

      D. Auth::user()->logout();

15. Route yang digunakan untuk login adalah...
    
    A. GET
    
    B. PATCH

    C. PUT

    **D. POST**

16. Maksud dari Route::post("/auth/logout","LoginController@logout")->middleware("auth:api") adalah...
    
    A. untuk memastikan bahwa user sudah authentikasi dan belum memiliki token
    
    B. untuk memastikan bahwa user belum authentikasi dan sudah memiliki token
    
    **C. untuk memastikan bahwa user sudah authentikasi dan sudah memiliki token**
    
    D. untuk memastikan bahwa user belum authentikasi dan belum memiliki token

17. Tipe authorisasi yang dipilih di POSTMAN saat menambahkan token dari laravel pssport adalah...
    
    A. Basic auth
    
    **B. Bearer Token**
    
    C. API key
     
    D. OAuth

18. Apa yang di tambahkan di Headers pada postman untuk mengakses api endpoint login, logout dan user...
     
    A. Accept json/application 
    
    B. Content application/json
    
    C. Content json/application
    
    **D. Accept application/json**

19. Output apa yang akan terjadi saat kita mengakses 127.0.1:8000/user saat kita baru saja logout...
    
    **A.message: "Unauthenticated."**
    
    B. message: "Undefinied."
    
    C. message: "Unauthorization."
    
    D. message: "Success."
