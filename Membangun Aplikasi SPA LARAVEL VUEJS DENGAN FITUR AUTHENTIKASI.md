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
    
    a. composer project-create laravel/laravel nama_project

    b. composer project-create laravel/nama_project
    
    **c. composer create-project laravel/laravel nama_project**
    
    d. composer create-project laravel/nama_project 


7. Cara menambahkan package laravel passport adalah...
    
    a. composer include laravel/passport
    
    b. composer included laravel/passport
    
    c. composer required laravel/passport
    
    **d. composer require laravel/passport**

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
    
    **a. Email dan Password**

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
    
    a. Untuk memastikan bahwa user sudah authentikasi dan belum memiliki token
    
    b. Untuk memastikan bahwa user belum authentikasi dan sudah memiliki token
    
    **c. Untuk memastikan bahwa user sudah authentikasi dan sudah memiliki token**
    
    d. Untuk memastikan bahwa user belum authentikasi dan belum memiliki token

17. Apa yang di tambahkan di Headers pada postman untuk mengakses api endpoint login, logout dan user...
     
    a. Accept json/application 
    
    b. Content application/json
    
    c. Content json/application
    
    **d. Accept application/json**

## Menginstall Preset Vue dan Menampilkan Component

18. Berikut ini yang bukan merupakan type pada ui laravel adalah...
    
    a. Bootstrap
    
    **b. Angular**
    
    c. React
    
    d. Vue

19. Apa syarat yang harus di lakukan sebelum menjalankan perintah npm install & npm run dev?
    
    **a. Menginstall nodejs**
    
    b. Menginstall jquery
    
    c. Menginstall vue
    
    d. Menginstall bootstrap

20. Perintah untuk menjalankan component vuejs dan setiap ada perubahan otomatis akan berubah adalah...
    
    a. npm run dev
    
    b. npm run save
    
    **c. npm run watch**
    
    d. npm run serve

21. Attribut apa yang ditambahkan untuk menjalankan script pada saat semua elemnt sudah di muat/load di dalam browser?
    
    a. beaver
    
    b. river
    
    **c. defer**
    
    d. driver

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
    
    a. Cocok untuk modular
    
    b. Automatic css class
    
    c. Efek transisi
    
    **d. Efek statis**

27. perintah untuk menginstall vue router adalah 
    
    **a. npm install vue-router --save-dev**
    
    b. npm install VueRouter --save-dev
    
    c. npm install vue-router --dev-save
    
    d. npm install VueRouter --dev-save

28. authenticated: false pada meta arti nya?
    
    a. Halaman komponen hanya dapat diakses oleh user yang sudah authentikasi
    
    b. Halaman komponen tidak dapat diakses oleh user yang sudah registrasi
    
    **c. Halaman komponen hanya dapat diakses oleh user yang belum authentikasi**
    
    d. Halaman komponen tidak dapat diakses oleh user yang belum registrasi

29. Untuk bisa menggunakan vue router perlu menuliskan syntax?
    
    a. Vue.component(VueRouter)
    
    b. Vue(VueRouter)
    
    **c. Vue.use(VueRouter)**
    
    d. VueRouter(VueRouter)

30. ```html <router-view> ``` berfungsi untuk?
    
    a. Melihat semua isi router
    
    **b. Komponen yang sudah diregistrasikan akan bisa diakses/tampil**
    
    c. Bepindah dari satu komponen ke komponen yang lain
    
    d. Bepindah dari satu komponen ke komponen yang lain tanpa reload/refresh

## Membuat Modul Baru dan Component Navigasi

31. Cara memanggil component Navigation yang benar adalah 
    
    a. ```html <Navigation></Navigation> ```
    
    b. ```html <Navigation > ```
    
    **c. ```html <Navigation />```** 
    
    d. Navigation

32. File untuk meregistrasikan seluruh components pada modul adalah?
    
    a. components.js
    
    b. state.js

    c. app.js

    **d. index.js** 

33. cara menambahkan home di router utama adalah 
    
    a. const routes = [home];
    
    b. const routes = [.home];
    
    c. const routes = [..home];
    
    **d. const routes = [...home];**

34. cara melihat hasil variable const route di vuejs adalah 
    
    a. print(routes);
    
    **b. console.log(routes);**

    c. return routes;

    d. {{ routes }}

## Installasi dan Pengenalan Vuex

35. Cara umum mengirimkan data antar components tanpa vuex bisa mengguakan?
    
    a. computed
    
    b. data
    
    **c. props**
    
    d. methods

36. Pengertian Vuex adalah

    a. router management pattern

    **b. state management pattern**

    c. share management pattern

    d. modular management pattern
    
37. Macam-macam file yang ada pada direktori modul store kecuali 
    
    a. actions
    
    b. mutations
    
    c. state
    
    **d. setters**

38. Cara menginstall vuex dapat dilakukan dengan via kecuali
    
    a. Yarn
    
    **b. Composer**
    
    c. NPM
    
    d. CDN

39. Syntax untuk menggunakan mapGetters adalah
    **a. export default {
        computed: {
            ...mapGetters({
                user: "auth/user"
            });
        }
    }**

    b. export default {
        compute: {
            ...mapGetters({
                user: "auth/user"
            });
        }
    }

    c. export default {
        components: {
            ...mapGetters({
                user: "auth/user"
            });
        }
    }

    d. export default {
        component: {
            ...mapGetters({
                user: "auth/user"
            });
        }
    }

## Registrasi Menggunakan Vue

40. Pada file mana yang mengatur request API Endpoint?

    a. state.js

    b. mutators.js

    **c. actions.js**

    d. getters.js

41. Fungsi parameter dispatch pada file actions.js adalah

    a. Untuk mengirimkan request

    b. Untuk mengambil request

    c. Untuk memanggil method diluar file actions.js

    **d. Untuk memanggil method yang ada pada file actions.js**

42. Syntax untuk saat klik tombol submit akan mengarahkan ke method submit adalah
    
    a. ```html <button onclick="submit"></button> ```

    b. ```html <button @click="submit"></button> ```

    **c. ```html <form @submit.prevent="submit> ```**

    d. ```html <form @submit.click="submit> ```

43. Method untuk menyimpan state pada inputan adalah

    **a. data**

    b. methods

    c. mapActions

    d. submit

44. mendapatkan method pada file actions dari berbagai modul menggunakan fungsi

    a. data

    b. methods

    **c. mapActions**

    d. submit

## Menampilkan Error Message Form di Vue

45. Parameter apa yang digunakan untuk mengisi data error?
    
    a. dispatch
    
    b. commit
    
    c. payload
    
    **d. context**

46. Isi context agar dapat mengambil property dari objek errors adalah
    
    a. this.context

    b. this.error

    c. this.erros

    **d. this**

47. Untuk menampilkan pesan error pada syntax input perlu ditambahkan directive class?

    a. not-invalid
    
    b. not-valid
    
    **c. is-invalid**
    
    d. is-valid

48. cara untuk memanggil data error email adalah
    
    a. {{ $errors.email[0] }}

    **b. {{ errors.email[0] }}**

    b. {{ $error.email[0] }}

    b. {{ error.email[0] }} 

## Membuat Halaman Login dan Error Form Validation

49. Syntax untuk menambah pesan error di json adalah
    **a. return response()->json([
        'meesage' => 'Authentication is invalid,
        'errors' => [
            'root' => 'Could not sign in with those details'
        ] 
    ]);**

    b. return response()->json([
        'meesage' => 'Authentication is invalid,
        'errors' => {
            'root' => 'Could not sign in with those details'
        }
    ]);

    c. return response()->json([
        'meesage' => 'Authentication is invalid,
        'root' => [
            'error' => 'Could not sign in with those details'
        ]
    ]);

    d. return response()->json([
        'meesage' => 'Authentication is invalid,
        'root' => {
            errors => 'Could not sign in with those details'
        }
    ]);

50. Syntax yang benar untuk membuat fungsi request login pada actions,js adalah
        
    a.  export const login({}, {payload,context}) => {
            return axios
            .get("/api/auth/login")
            .then(() => {
                console.log(result.data);
            }).catch((err) => {
                context.errors = err.response.data.errors;
            })
        }

    b.  **export const login({}, {payload,context}) => {
            return axios
            .post("/api/auth/login")
            .then(() => {
                console.log(result.data);
            }).catch((err) => {
                context.errors = err.response.data.errors;
            })
        }**

    c.  export const login({}, {payload,context}) => {
            return axios
            .get("/api/auth/login")
            .then(() => {
                context.errors = err.response.data.errors;
            }).catch((err) => {
                console.log(result.data);
            })
        }

    d.  export const login({}, {payload,context}) => {
            return axios
            .post("/api/auth/login")
            .then(() => {
                context.errors = err.response.data.errors;
            }).catch((err) => {
                console.log(result.data);
            })
        }
}

51. Saat request berhasil maka method yang dijalankan pada axios adalah
    a. post()
    
    b. get()
    
    **c. then()**
    
    d. catch()

52. Saat request gagal maka method yang dijalankan pada axios adalah...
    
    a. post()
    
    b. get()
    
    c. then()
    
    **d. catch()**

## Menyimpan Token di LocalStorage dan Setup Headers Authorization

53. Suatu token biasa nya disimpan didalam...
    
    a. server

    b. memory

    c. cloud

    **d. localStorage**

54. File mana yang mengatur token disimpan di dalam localStorage

    a. state.js

    **b. mutators.js**

    c. actions.js

    d. getters.js
    
55. isEmpty adalah fungsi dari package?
    
    a. vue
    
    b. vuex
    
    c. vue-router
    
    **d. lodash**

56. Parameter apa yang digunakan pada method yang ada di file actions.js untuk memanggil mutations
    
    a. dispatch
    
    **b. commit**
    
    c. payload
    
    d. context

57. Syntax apa yang perlu di tulis pada helpers index.js saat melakukan pengecekan ternyata memiliki akses token
    
    a. window.axios.defaults.header.common["Authentication"] = "Bearer " + token;
    
    b. window.axios.defaults.header.common["Authentication"] = null; 
    
    **c. window.axios.defaults.header.common["Authorization"] = "Bearer " + token;**
    
    d. window.axios.defaults.header.common["Authorization"] = null;


## Menyimpan Data Auth pada State dan Redirect