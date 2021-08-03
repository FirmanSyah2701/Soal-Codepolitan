# Belajar Vue 3 dan Firebase Studi Kasus Blog

## Gambaran Composition API

1. Berikut ini yang merupakan struktur Options API adalah...
    
    a. data, methods, compute, mount
    
    b. data, method, compute, mount
    
    **c. data, methods, computed, mounted**
    
    d. data, method, computed, mounted

2. Mengelola data secara reactive terdapat dalam fungsi..

    **a. data**

    b. methods

    c. computed

    d. mounted

3. Keuntungan yang tepat dalam menggunakan composition adalah

    a. Cocok untuk aplikasi yang sederhana

    b. Cocok untuk aplikasi yang kompleks

    c. Mudah dalam mengelompokkan

    **d. A dan C benar**

4. Kekurangan dari menggunakan Options API adalah
    
    a. Tidak cocok untuk aplikasi yang kompleks

    b. Tidak cocok untuk aplikasi yang sederhana

    c. Sulit dibaca untuk aplikasi yang bersifat kompleks/modular

    **d. A dan C benar**

5. Fungsi yang tepat dari method mounted adalah

    a. Untuk mendeklarasikan objek atau variable

    b. Untuk mengelola data secara reactive 

    c. Untuk mengelola method-method data

    **d. Untuk mengelola data API endpoint**

## Setup Project Dan Cara Kerja Composition API

6. Hal yang perlu di install sebelum menginstall vuejs adalah

    a. TypeScript

    b. composer

    **c. nodejs**

    d. jquery

7. Untuk menginstall vuejs dapat dilakukan dengan cara

    a. npm

    b. yarn

    c. a dan b salah

    **d. a dan b benar**

8. Salah satu fitur vuejs 3 yang diaktifkan adalah?
    
    a. Vuex

    **b. Router**

    c. Linter

    d. A dan B benar

9. Berikut ini method yang di buat di dalam Home.vue adalah
    
    a. data()

    **b. setup()**

    c. computed()

    d. A dan C benar

10. Syntax untuk mencetak/menampilkan variable adalah

    **a. {{ name }}**

    b. {{ $name }}

    c. name
    
    d. $name

## Membuat Data pada Composition API

11. salah satu fitur untuk membuat data reactive adalah
    
    **a. ref()**

    b. refs()

    c. reference()

    d. references()

12. Syntax yang tepat untuk mengembalikan/return sebuah variable dan method adalah 

    a. return name, number, handleClick

    b. return [name, number, handleClick]

    **c. return {name, number, handleClick}**

    d. return {{name, number, handleClick}}

13. agar sebuah fungsi dapat di jalankan pada button maka perlu ditambahkan syntax

    **a. @click**

    b. @submit

    c. @method

    d. a dan b benar

14. kalau menggunakan data() kita dapat mengakses data variable dengan this lalu bagaimana cara mengakses data di setup()

    a. bisa diakses langsung

    b. bisa menggunakan this juga

    c. menggunakan value sebelum variable

    **d. menggunakan value setelah variable**

15. untuk mengubah seluruh text di dalam tag p adalah
    
    a. p.value.classList("isi teks")

    b. p.value.textList("isi teks")

    c. p.value.classContent("isi teks")

    **d. p.value.textContent("isi teks")**

## Memanfaatkan Ref Untuk Data Reactive

16. Syntax yang benar untuk menampung objek di dalam ref adalah

    a. ref(name: 'Fulan', number: '08343242')
    
    b. ref([name: 'Fulan', number: '08343242'])

    **c. ref({name: 'Fulan', number: '08343242'})**

    d. ref((name: 'Fulan', number: '08343242'))

17. Dimana value dapat bekerja?

    a. di dalam template

    **b. di dalam fungsi setup**

    c. di dalam fungsi data

    d. a dan b benar

18. Apa saja kelebihan dari fungsi ref

    a. Dapat membuat data menjadi reactive

    b. Dapat menyimpan objek

    c. Dapat langsung memanggil nilai yang diinputkan 

    **d. Semua benar**

## Membandingkan Fungsi Ref Dengan Reactive

19. Perbedaan cara mengubah data contact di ref dan reactive adalah

    **a. ref: contact.value.name = 'Luna', reactive: contact.name = 'Luna'**

    b. ref: contact.name = 'Luna', reactive: contact.value.name = 'Luna'

    c. ref: contact.name.value = 'Luna', reactive: contact.name = 'Luna'

    d. ref: contact.name = 'Luna', reactive: contact.name.value = 'Luna'


20. Salah satu kelemahan dari reactive 

    a. tidak bisa mengubah data secara realtime

    **b. tidak bisa mengubah data primitive**
    
    c. tidak bisa mengubah method secara realtime

    d. a dan c benar

21. Syntax yang benar untuk menampung objek di dalam reactive adalah

    a.  ``reactive(name: 'Yanie', number: '0932424')``
    
    b.  ``reactive([name: 'Yanie', number: '0932424'])``

    **c. ``reactive({name: 'Yanie', number: '0932424'})``**

    d. ``reactive((name: 'Yanie', number: '0932424'))``

## Manipulasi Data Dengan Computed Property

22. Cara menggunakan v-for untuk memanggil data names di dalam template adalah

    a. ``<div v-for="name in names" :key="name">{{ name }} </div>``

    b. ``<div v-for="names in name" :key="name">{{ name }} </div>``

    c. ``<div v-for="(name, index) in names" :key="index">{{ name }} </div>``

    **d. A dan C benar**

23. Fungsi untuk menampilkan nama sesuai dengan keyword yang kita ketikkan adalah

    a. filter

    b. search

    c. include

    **d. includes**

24. Berikut ini yang merupakan penggunaan computed di Composition API dengan benar adalah

    a. 
    ```
    computed(): {
        return names.value
    }
    ```

    b. ``const names = computed(() => return names) ``

    **c. 
    ```
    const resultSearch = computed(() => {
        return names.value
    })
    ```
    **

    d. 
    ```
    const resultSearch = computed(() => {
        return names
    })
    ```

## Memantau Perubahan Data Dengan Watch

25. Apa fungsi dari watch?
    
    **a. untuk memeriksa data yang dimiiki secara realtime** 
    
    b. untuk melakukan suatu perubahan pada data

    c. untuk memeriksa data dan fungsi

    d. B dan C benar

26. 
    ```
    watch(search, () => {
        console.log('fungsi berjalan')
    })
    ```

    fungsi tersebut akan berjalan pada saat...
    
    a. Halaman pertama kali dimuat

    b. Sebelum mengetikkan inputan search

    **c. Mengetikkan inputan search**

    d. Setelah mengetikkan inputan search

27. Perbedaan watch dengan watchEffect ialah
    
    a. watch berjalan satu kali saat data terjadi perubahan 
       sedangkan watchEffect berjalan terus dari awal componen di muat hingga akhir
    
    b. watch berjalan terus dari awal componen di muat hingga akhir 
       sedangkan watchEffect berjalan satu kali saat data terjadi perubahan 
    
    c. watch berjalan secara otomatis saat componen pertama kali di muat sedangkan watchEffect berjalan saat data terjadi perubahan
    
    **d. watch  berjalan saat data terjadi perubahan sedangkan watchEffect berjalan secara otomatis saat componen pertama kali di muat**

28. cara memberhentikan watch adalah
    
    a.  
    ```
    const stop = watch(search(), {
        console.log('fungsi watch berjalan')
    })

    const handleClick = () => {
        stop()
    }
    ```
    
    **b. 
    ```
    const stop = watch(search, () {
        console.log('fungsi watch berjalan')
    })

    const handleClick = () => {
        stop()
    }
    ```
    **

    c. 
    ```
    const stop = watch(search(), {
        console.log('fungsi watch berjalan')
    })

    const handleClick => ({
        stop()
    })
    ```

    d. 
    ```
    const stop = watch(search, () {
        console.log('fungsi watch berjalan')
    })

    const handleClick => ({
        stop()
    })
    ```

## Menggunakan Props Di Composition API

29. Cara menangkap data props adalah
    
    **a. ``props: ['posts']``**
    
    b. ``props = ['posts']``
    
    c. ``props: 'posts'``
    
    d. ``props = 'posts'``

30. Cara memanggil data props posts di dalam setup function adalah
    a. 
    ```
    setup() {
        console.log(props)
    }
    ```
    b. 
    ```
    setup(props) {
        console.log(props)
    }
    ```

    c. 
    ```
    setup() {
        console.log(props.posts)
    }
    ```

    **d. 
    ```
    setup(props) {
        console.log(props.posts)
    }
    ```
    **

31. Untuk memanipulasi data props perlu menggunakan fungsi

    a. methods

    b. substring

    **c. computed**

    d. mounted

32. untuk memotong string karakter kita dapat menggunakan fungsi

    a. methods

    **b. substring**

    c. computed

    d. mounted

## Implementasi Lifecycle Hooks Vue 3

33. onMounted berjalan saat...

    **a. component tersebut dimuat atau dijalankan**

    b. component tersebut dilepaskan

    c. component terjadi suatu perubahan 

    d. b dan c benar

34. onUpdated berjalan saat..

    a. component terjadi penambahan data

    b. componen terjadi perubahan data

    c. componen terjadi penghapusan data

    **d. a, b dan c benar**

35. Berikut yang bukan merupakan lifecycle hooks di dalam vue adalah 
    
    a. onMonted

    b. onUnMounted

    **c. onChange**

    d. onUpdated

## Membuat Fake REST API dan Mencoba Async Await

36. Apa itu json-server?
    
    a. Library yang digunakan untuk membuat rest api

    **b. Library yang digunakan untuk membuat fake rest api**

    c. Library yang digunakan untuk membuat server

    d. Library yang digunakan untuk membuat data json

37. Cara menginstall json-server adalah...

    a. npm install -i json-server

    b. npm install -d json-server

    **c. npm install -g json-server**

    d. npm install -f json-server

38. Cara menjalankan file db.json menggunakan json-server adalah...

    a. json-server -serve data/db.json

    b. json-server --serve data/db.json

    c. json-server -watch data/db.json

    **d. json-server --watch data/db.json**

39. Apa kegunaan async await?

    a. untuk menjalankan proses selanjutnya berjalan sebelum proses yang lainnya selesai

    b. untuk menjalankan proses selanjutnya tanpa menunggu proses yang lainnya selesai

    **c. untuk mencegah proses selanjutnya berjalan sebelum proses yang lainnya selesai**

    d. a dan b benar

40. Source code untuk get data posts dari json-server dan adalah
    
    a.
    ```
    const load = async() => {
        try{
            let data = fetch('http//localhost:3000/posts')
            if(! data.ok ) {
                throw Error('Tidak ada data')
            }
            posts.value = data.json()
        }catch(err){
            error.value = err.message
        }
    }
    ```
    
    b. 
    ```
    const load = async() => {
        try{
            let data = await fetch('http//localhost:3000/posts')
            if(! data.ok ) {
                throw Error('Tidak ada data')
            }
            posts.value = data.json()
        }catch(err){
            error.value = err.message
        }
    }
    ```
    
    c. 
    ```
    const load = async() => {
        try{
            let data = fetch('http//localhost:3000/posts')
            if(! data.ok ) {
                throw Error('Tidak ada data')
            }
            posts.value = await data.json()
        }catch(err){
            error.value = err.message
        }
    }
    ```

    **d. 
    ```
    const load = async() => {
        try{
            let data = await fetch('http//localhost:3000/posts')
            if(! data.ok ) {
                throw Error('Tidak ada data')
            }
            posts.value = await data.json()
        }catch(err){
            error.value = err.message
        }
    }
    ```
    **

## Membuat dan Memanggil Fungsi di Luar Component

41. Isi fungsi-fungsi yang dapat di panggil di component manapun biasa nya disebut
    
    a. composer

    b. composible

    **c. composable**

    d. composition

42. Agar data posts, error dan fungsi load dapat di panggil di fungsi getPosts maka kita perlu menuliskan source code...

    a. [ posts, error, load ]

    b. return post, error, load
    
    c. return [ post, error, load ]
    
    **d. return { post, error, load }**

43. Agar fungsi getPosts dapat dipanggil di componen lain kita perlu menuliskan source code
    
    a. import getPosts

    b. export getPosts

    **c. export default getPosts**

    d. export module getPosts

44. Cara memanggil posts, error dan load di dalam component adalah
    
    **a. const { posts, error, load } = getPosts()**
    
    b. const [ posts, error, load ] = getPosts()

    c. const { posts, error, load } = getPosts

    d. const [ posts, error, load ] = getPosts

## Membuat Fungsi untuk Memanggil Single Data Post

45. Cara menambahkan url parameter id pada posts untuk melihat detail adalah
    
    a. path: '/posts/id'
    
    b. path: '/posts/'+id

    **c. path: '/posts/:id'**

    d. path: '/posts/{id}'

46. Cara mengaktifkan props didalam url adalah....
    
    **a. props: true**
    
    b. props: false
    
    c. props: on
    
    d. A dan C benar

47. Cara memanggil satu data posts adalah
    
    a. let data = await fetch('localhost:3000/post/id')

    b. let data = await fetch('localhost:3000/posts/id')
    
    c. let data = await fetch('localhost:3000/posts' + id)

    **d. let data = await fetch('localhost:3000/posts/' + id)**

48. Perbedaan pemanggilan fungsi composable getPosts dan getPost adalah

    **a. 
    ```
       getPosts: const { posts, error, load } = getPosts(), 
       getPost: const { post, error, load } = getPost(props.id)
    ```
    **
    b. 
    ```
       getPosts: const { posts, error, load } = getPosts(), 
       getPost: const { post, error, load } = getPost(props.value.id)
    ```

    c. 
    ```
       getPosts: const { posts, error, load } = getPosts(props.id), 
       getPost: const { post, error, load } = getPost()
    ```

    d. 
    ```
       getPosts: const { posts, error, load } = getPosts(props.value.id), 
       getPost: const { post, error, load } = getPost()
    ```
    
## Mempelajari Promise Async Await untuk Menampilkan Loading

49. Berikut ini property css yang dapat membuat setengah lingkaran adalah
    
    a. margin: 30px auto;
    
    b. border: 3px solid transparent;

    **c. border-radius: 50%**
    
    d. width: 40px;

50. Cara membuat fungsi animasi di css adalah...

    a. 
    ```
    function spin(){
        to {}
    }
    ```
    
    b. 
    ```
    @keyFrames spin {
        to{}
    }
    ```
    
    **c. 
    ```
    @keyframes spin {
        to{}
    }
    ```
    **

    d. 
    ```
    @keyframes spin() {
        to{}
    }
    ```

51. Ada dua macam parameter dalam promise yaitu...

    a. solve dan eject

    b. solve dan reject

    c. resolve dan eject

    **d. resolve dan reject**

52. Cara menambahkan jeda selama 2 detik adalah

    a. setInterval(resolve, 2000)

    **b. setTimeout(resolve, 2000)**

    c. setInterval(resolve, 2)

    d. setTimeout(resolve, 2)

## Membuat Halaman Create Post dan Input Tags

53. Source code untuk melakukan event saat klik enter mencegah submit terjadi yaitu...

    a. @key.enter.prevent = "handleKeydown"

    **b. @keydown.enter.prevent = "handleKeydown"**

    c. @key.enter.event = "handleKeydown"

    d. @keydown.enter.event = "handleKeydown"

54. Source code untuk memasukkan beberapa data tag ke dalam tags adalah

    a. tags.push(tag)

    b. tags.pop(tag)

    **c. tags.value.push(tag.value)**

    d. tags.value.pop(tag.value)

55. Untuk menghapus nilai whitespace kita dapat menggunakan fungsi?
    
    a. push

    b. pop

    c. includes

    **d. replace**

56. Data apa saja yang perlu di inputkan dengan menggunakan directive v-model pada component Create.vue?
    
    a. title, body, tags, tag

    b. title, body, tags

    **c. title, body, tag**

    d. title, body

## Membuat Fungsi Create Post untuk Menambah Data Baru

57. Source code untuk menambahkan data posts dengan json-server adalah

    a.
    ```
    const handleSubmit = () => {
        const post = {
            title: title.value 
            body: body.value
            tags: tags.value
        }

        fetch('http://localhost:3000/posts/')
    }
    ```

    b.
    ```
    const handleSubmit = async () => {
        const post = {
            title: title.value 
            body: body.value
            tags: tags.value
        }

        await fetch('http://localhost:3000/posts/')   
    }
    ```

    c.
    ```
    const handleSubmit = () => {
        const post = {
            title: title.value 
            body: body.value
            tags: tags.value
        }

        fetch('http://localhost:3000/posts/', {
            method: 'POST',
            headers: { 'Content-Type': 'application/json' },
            body: JSON.stringify(post)
        })   
    }
    ```
    
    **d.
    ```
    const handleSubmit = async () => {
        const post = {
            title: title.value 
            body: body.value
            tags: tags.value
        }

        await fetch('http://localhost:3000/posts/', {
            method: 'POST',
            headers: { 'Content-Type': 'application/json' },
            body: JSON.stringify(post)
        })   
    }
    ```
    **

58. Salah satu perbedaan fetch get dan post adalah

    a. kalau get perlu menambahkan method sedangkan post tidak perlu menambahkan method

    b. kalau get tidak perlu menambahkan method sedangkan post perlu menambahkan method

    c. kalau get perlu menambahkan options sedangkan post tidak perlu menambahkan options

    **d. kalau get tidak perlu menambahkan options sedangkan post perlu menambahkan options**
 
59. Options apa saja yang perlu ditambahkan untuk menambahkan data posts?
    
    **a. methods, headers, body**

    b. methods, headers, title, body

    c. methods, headers, content, body

    d. methods, headers, type, body


60. Json.stringify(post) berfungsi untuk....
    
    a. menambahkan nilai key dan value dari objek post ke dalam json

    **b. mengubah nilai key dan value dari objek post ke dalam json**

    c. menambahkan nilai key dan value dari json ke dalam objek post

    d. mengubah nilai key dan value dari json ke dalam objek post


61. Source code untuk redirect halaman Home dengan router adalah

    a. router.push(name: 'Home')

    b. router.push(name: '/home')

    **c. router.push({name: 'Home'})**

    d. router.push({name: '/home'})

## Menginstall Library Pihak Ketiga Untuk Template Blog

62. Salah satu situs yang menyediakan template bootstrap gratis adalah

    a. starbootstrap.com

    **b. startbootstrap.com**

    c. bulmathemes.com

    d. tailwindtoolbox.com

63. Library yang dibutuhkan untuk menginstall bootstrap adalah
    
    a. jQuery dan ajax

    **b. jQuery dan popper.js**

    c. popper.js dan ajax

    d. font-awesome dan popper.js

64. Apa saja yang perlu di import untuk mengintegrasikan vue dengan bootstrap
    
    **a.
    ```    
    import 'bootstrap'
    import 'bootstrap/dist/boostrap.css'

    import jQuery from 'jquery'
    window.$ = jQuery
    ```
    
    **
    b.
    ```    
    import 'bootstrap'
    import 'bootstrap/dist/boostrap.js'

    import jQuery from 'jquery'
    window.$ = jQuery
    ```

    c. 
    ```    
    import 'bootstrap'
    import 'bootstrap/dist/boostrap.css'

    import jquery
    window.$ = jQuery
    ```

    d. 
    ```    
    import 'bootstrap'
    import 'bootstrap/dist/boostrap.js'

    import jQuery from 'jquery'
    window.$ = jquery
    ```

65. Apa maksud dari window.$ = jQuery ?

    a. memanggil objek jQuery sebagai window.$

    b. mendefinisikan window yang berisi jQuery

    **c. mendefinisikan window sebagai objek global dan $ untuk menampung jQuery**

    d. mendefinisikan $ sebagai objek global dan window untuk menampung jQuery

## Integrasi Vue dengan Template Bootstrap

66. Didalam vue untuk menyimpan file css dan javascript disimpan didalam direktori...

    a. public

    **b. src/assets**

    c. src/public

    d. src/public/assets

67. Didalam vue untuk menyimpan file image disimpan didalam direktori...

    **a. public**

    b. src/assets

    c. src/public

    d. src/public/assets

68. Cara menregistrasikan clean-blog.css dan clean-blog.js di dalam vue adalah

    a. 
    ```
    import /assets/css/clean-blog.css
    import /assets/js/clean-blog.js
    ```

    b. 
    ```
    import ./assets/css/clean-blog.css
    import ./assets/js/clean-blog.js
    ```

    c. 
    ```
    import ../assets/css/clean-blog.css
    import ../assets/js/clean-blog.js
    ```

    **d. 
    ```
    import @/assets/css/clean-blog.css
    import @/assets/js/clean-blog.js
    ```
    **


69. fa-2x artinya adalah

    a. font-awesome icon berbentuk lingkaran

    b. font-awesome icon berukuran lebih besar (33%)

    **c. font-awesome icon memperbesar ukuran 2x** 

    d. font-awesome icon memperkecil ukuran 2x


## Desain Halaman ShowPost

70. Dimana post title diletakan?
    
    **a. 
    ```
    <div class="post-heading"> 
        <h1> {{post.title}} </h1> 
    </div>
    ```
    **

    b. 
    ```
    <div class="subheading"> 
        <h1> {{post.title}} </h1> 
    </div>
    ```

    c.
    ```
    <span class="meta"> 
        <h1> {{post.title}} </h1> 
    </div>
    ```

    d. 
    ```
    <span class="meta-post"> 
        <h1> {{post.title}} </h1> 
    </div>
    ```

71. Bagaimana mengubah tag anchor ``<a class="nav-link" href="index.html">Home</a>`` menjadi router-link untuk meredirect ke halaman Home.vue?

    a. ``<router-link class="nav-link" href="Home.vue">Home</router-linke>``

    b. ``<router-link class="nav-link" to="Home.vue">Home</router-linke>``

    **c. ``<router-link class="nav-link" :to="{name: 'Home'}">Home</router-linke>``**

    d. ``<router-link class="nav-link" :to="{name: '/home'}">Home</router-linke>``

72. Agar saat post nya tidak ada tidak muncul halaman post nya tetapi halaman loading terlebih dahulu maka penutup ``</div>`` v-if="post" dan 
    ``<div else> <Loading /> </div>`` diletakan...

    a. sebelum tag horizontal line ``( <hr /> )``

    **b. setelah tag horizontal line ``( <hr /> )``**

    c. setelah tutup tag article ``( </article> )``

    d. setelah tutup tag header ``( </header> )``

73. Agar data tags dapat sejajar atau inline maka perlu menambahkan class...

    a. post-heading

    b. meta-heading

    **c. meta-post**

    d. meta

## Mempercantik Halaman Create Post

74. Source code untuk membuat inputan beberapa tags adalah

    a. 
    ```
        <input
            type="text"
            class="form-control"
            placeholder="input tags"
            required
            v-model="tags"
            @keydown.enter.prevent="handleKeyDown"
        >
    ```

    b. 
    ```
        <input
            type="text"
            class="form-control"
            placeholder="input tags"
            required
            v-model="tag"
            @keydown.enter.prevent="handleKeyDown"
        >
    ```

    c. 
    ```
        <input
            type="text"
            class="form-control"
            placeholder="input tags"
            v-model="tags"
            @keydown.enter.prevent="handleKeyDown"
        >
    ```

    **d. 
    ```
        <input
            type="text"
            class="form-control"
            placeholder="input tags"
            v-model="tag"
            @keydown.enter.prevent="handleKeyDown"
        >
    ```
    **

75. Pada template contact terdapat form dengan textarea message yang bisa kita manfaatkan untuk membuat...

    a. title

    **b. body**

    c. tags

    d. tag

76. Agar data tag muncul saat kita tekan enter maka perlu menambahkan syntax...

    **a. ``<span v-for="tag in tags" :key="tag"> #{{ tag }} </span>``**

    b. ``<span v-for="tag in tags" :key="tag"> #{{ tags }} </span>``

    c. ``<span v-for="tags in tag" :key="tag"> #{{ tag }} </span>``

    d. ``<span v-for="tags in tag" :key="tag"> #{{ tags }} </span>``

## Menampilkan Data Post Berdasarkan Tag

77. Cara mengimport PostList pada direktory views/posts/Tag.vue adalah

    a. import PostList from '../components/posts/PostList'

    b. import PostList from '../../components/posts/PostList'

    c. import PostList from '@/components/posts/PostList'

    **d. B dan C benar**

78. 
    a. 
    ```
    const postsWithTag = (() => {
        return posts.value.filter((p) => p.tags.includes(route.params.tag))
    })
    ```

    **b. 
    ```
    const postsWithTag = computed(() => {
        return posts.value.filter((p) => p.tags.includes(route.params.tag))
    })
    ```
    **

    c. 
    ```
    const postsWithTag = computed(() => {
        return posts.filter((p) => p.tags.includes(route.params.tag))
    })
    ```

    d. 
    ```
    const postsWithTag = computed(() => {
        return posts.value.includes((p) => p.tags.filter(route.params.tag))
    })
    ```

79. Agar kita bisa mengakses route.params maka kita perlu mengimport...
    
    a. import useRouter from 'vue-router'

    b. import useRoute from 'vue-router'

    c. import { useRoute } from 'vue'

    **d. import { useRoute } from 'vue-router'**

80. Source code agar kita klik salah satu tag kita dapat mencari posts yang memiliki tag tersebut adalah...

    a. 
    ```
    <span v-for="tag in post.tag" :key="tag" class="post-meta">
        <route-link :to="{name='Tag', params= {tag: tag}}">
            #{{tag}}
        </route-link>
    </span>
    ```

    **b. 
    ```
    <span v-for="tag in post.tag" :key="tag" class="post-meta">
        <router-link :to="{name='Tag', params= {tag: tag}}">
            #{{tag}}
        </router-link>
    </span>
    ```
    **

    c. 
    ```
    <span v-for="tag in post.tag" :key="tag" class="post-meta">
        <route-link params= {tag: tag}">
            #{{tag}}
        </route-link>
    </span>
    ```

    d. 
    ```
    <span v-for="tag in post.tag" :key="tag" class="post-meta">
        <router-link :to="params= {tag: tag}">
            #{{tag}}
        </router-link>
    </span>
    ```

## Membuat Project Layanan Firebase

81.

82.

83.

84.

## Konfigurasi Sdk Firebase Di Vue Cli

85.

86.

87.

88.

## Membuat Collection Di Firestore

89.

90.

91.

92.

## Menampilkan Seluruh Data Collection Firestore Dalam Vue

93.

94.

95.

96.

## Menampilkan Satu Data Collection Dalam Vue

97.

98.

99.

100.

## Menambah Data Collection Dari Vue

101.

102.

103.

104.

## Menghapus Collection Dari Vue

105.

106.

107.

108.