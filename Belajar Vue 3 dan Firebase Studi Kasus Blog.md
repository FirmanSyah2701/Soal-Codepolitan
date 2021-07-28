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

26. ```
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

29. cara memberhentikan watch adalah
    
    a.  
        ```
        const stop = watch(search(), {
            console.log('fungsi watch berjalan')
        })

        const handleClick = () => {
            stop();
        }
        ```
    
    **b. 
        ```
        const stop = watch(search, () {
            console.log('fungsi watch berjalan')
        })

        const handleClick = () => {
            stop();
        }
        ```
    **

    c. 
        ```
        const stop = watch(search(), {
            console.log('fungsi watch berjalan')
        })

        const handleClick => ({
            stop();
        })
        ```

    d. 
        ```
        const stop = watch(search, () {
            console.log('fungsi watch berjalan')
        })

        const handleClick => ({
            stop();
        })
        ```

## Menggunakan Props Di Composition API

30. Cara menangkap data props adalah
    
    **a. ``props: ['posts']``**
    
    b. ``props = ['posts']``
    
    c. ``props: 'posts'``
    
    d. ``props = 'posts'``

31. Cara memanggil data props posts di dalam setup function adalah
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

32. Untuk memanipulasi data props perlu menggunakan fungsi

    a. methods

    b. substring

    **c. computed**

    d. mounted

33. untuk memotong string karakter kita dapat menggunakan fungsi

    a. methods

    **b. substring**

    c. computed

    d. mounted

## Implementasi Lifecycle Hooks Vue 3

34. onMounted berjalan saat...

    **a. component tersebut dimuat atau dijalankan**

    b. component tersebut dilepaskan

    c. component terjadi suatu perubahan 

    d. b dan c benar

35. onUpdated berjalan saat..

    a. component terjadi penambahan data

    b. componen terjadi perubahan data

    c. componen terjadi penghapusan data

    **d. a, b dan c benar**

36. Berikut yang bukan merupakan lifecycle hooks di dalam vue adalah 
    
    a. onMonted

    b. onUnMounted

    **c. onChange**

    d. onUpdated

## Membuat Fake REST API dan Mencoba Async Await