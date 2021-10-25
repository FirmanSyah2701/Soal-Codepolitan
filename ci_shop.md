# Membangun Website Toko Online Berbasis CodeIgniter

# Membangun Template Dengan Bootstrap

## Contoh Template dan Persiapan Awal

1. Assets-assets yang dibutuhkan dalam membangun aplikasi toko online adalah
    
    a. bootstrap, font awesome
    
    b. jquery, font awesome
    
    **c. bootstrap, jquery, font awesome**
    
    d. bootstrap, jquery, google font

2. Assets yang digunakan untuk menggunakan icon adalah

    a. material icon

    **b. font Awesome**

    c. jquery

    d. bootstrap

## Membuat Kerangka HTML dan Navigasi Menggunakan Bootstrap

3. Kegunaan dari extension Live Server pada vscode adalah...

    a. Extension untuk html menampilkan perubahan secara langsung

    b. Extension untuk menampilkan di browser tanpa harus meload secara manual
    
    c. Extension untuk html menampilkan perubahan secara langsung dan menampilkan perubahakn

    **d. Extension vscode untuk membuat tampilann html secara realtime ditampilkan di browser dan saat berubah akan langsung menampilkan perubahan**

4. Syntax untuk meload file bootstrap css adalah...

    **a. <link href="/assets/libs/bootstrap/css/bootstrap.min.css" rel="stylesheet">**

    b. <link href="assets/libs/bootstrap/css" rel="stylesheet">

    c. <link href="/assets/libs/bootstrap/css/bootstrap.min.css" integrity="stylesheet">

    d. <link href="assets/libs/bootstrap/css" integrity="stylesheet">

## Membuat Halaman Login

5. Untuk membuat beberapa column pada bootstrap dapat dibaca pada bagian...

    a. layout

    b. content

    **c. grid**

    d. components

6. Apa saja isi dari form group untuk membuat input email?

    a. input

    b. label, input

    **c. label, input, small text**

    d. label, input, small text, button

## Membuat Halaman Register

7. Kegunaan dari konfirmasi password pada regiser adalah

    **a. untuk memastikan pengguna mengingat password nya**

    b. untuk memastikan pengguna benar mengetik password nya

    c. untuk menyimpan password

    d. a dan c benar

8. Untuk merubah title dari card dapat diubah dibagian...

    a. card-title

    **b. card-header**

    c. card-body

    d. card-footer

## Membuat Tampilan Beranda Bagian 1

9. Total kesuluruhan column adalah

    a. 9

    b. 10

    c. 11

    **d. 12**

10. Source code untuk membuat card dengan bebarap list item adalah

    a. 
    ```html
    <div class="row">
        <div class="col-md-12">
            <div class="card mb-3">
                <div class="card-header">
                    Kategori
                </div>
                <ul class="list-group list-group-flush">
                    <li class="list-group-item">Semuaa Kategori</li>
                    <li class="list-group-item">Kategori 1</li>
                    <li class="list-group-item">Kategori 2</li>
                </ul>
            </div>
        </div>
    </div>
    ```

    b. 
    ```html
    <div class="col-md-12">
        <div class="row">
            <div class="card mb-3">
                <div class="card-header">
                    Kategori
                </div>
                <div class="card-body">
                    <ul class="list-group list-group-flush">
                        <li class="list-group-item">Semuaa Kategori</li>
                        <li class="list-group-item">Kategori 1</li>
                        <li class="list-group-item">Kategori 2</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    ```

    c. 
    ```html
    <div class="row-md-12">
        <div class="col">
            <div class="card mt-3">
                <div class="card-header">
                    Kategori
                </div>
                <div class="card-body">
                    <ul class="list-group list-group-flush">
                        <li class="list-group-item">Semuaa Kategori</li>
                        <li class="list-group-item">Kategori 1</li>
                        <li class="list-group-item">Kategori 2</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    ```

    **d. 
    ```html
    <div class="row">
        <div class="col-md-12">
            <div class="card mb-3">
                <div class="card-header">
                    Kategori
                </div>
                <div class="card-body">
                    <ul class="list-group list-group-flush">
                        <li class="list-group-item">Semuaa Kategori</li>
                        <li class="list-group-item">Kategori 1</li>
                        <li class="list-group-item">Kategori 2</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    ```
    **

## Membuat Tampilan Beranda Bagian 2

11. source code untuk membuat badge dengan tata letak di kanan adalah...

    a. 
    ```html
    <span class="float">
        Ututkan harga: <a href="#" class="badge badge-primary"> Termurah </a> | <a href="#" class="badge badge-primary"> Termahal
    </span>
    ```

    b. 
    ```html
    <span class="right">
        Ututkan harga: <a href="#" class="badge badge-primary"> Termurah </a> | <a href="#" class="badge badge-primary"> Termahal
    </span>
    ```

    **c. 
    ```html
    <span class="float-right">
        Ututkan harga: <a href="#" class="badge badge-primary"> Termurah </a> | <a href="#" class="badge badge-primary"> Termahal
    </span>
    ```
    **

    d. 
    ```html
    <span class="float-left">
        Ututkan harga: <a href="#" class="badge badge-primary"> Termurah </a> | <a href="#" class="badge badge-primary"> Termahal
    </span>
    ```

12. Source code untuk menggunakan image generator online sesuai ukuran adalah

    **a. <img src="placeholder.co/100x70" alt="" class="card-img-top">**

    b. <img src="placeholder.co/100*70" alt="" class="card-img-top">

    c. <img src="placeholder.co/100/70" alt="" class="card-img-top">

    d. <img src="placeholder.co/width=100/height=70" alt="" class="card-img-top">


## Membuat Halaman Keranjang Belanja

13. Syntax untuk membuat text berwarna putih adalah

    a. white-text

    **b. text-white**

    c. text-primary

    d. white

14. Source code untuk membuat button delete adalah...

    a. <button class="btn btn-danger" type="submit"><i class="fa fa-trash"></i></button>

    **b. <button class="btn btn-danger" type="submit"><i class="fas fa-trash-alt"></i></button>**

    c. <button class="btn btn-danger" type="submit"><i class="fas fa-check"></i></button>

    d. <button class="btn btn-danger" type="submit"><i class="fas fa-angle-right"></i></button>


## Membuat Halaman Checkout

15. Source code untuk membuat input form alamat pengiriman adalah...

    a.
    ```html
    <div class="form-group">
        <label for="">Alamat</label>
        <input type="address" name="address" id="" cols="30" rows="5" class="form-control">
        <small class="form-text text-danger">Alamat harus diisi.</small>
    </div>
    ```

    b.
    ```html
    <div class="form-group">
        <label for="">Alamat</label>
        <input type="textarea" name="address" id="" cols="30" rows="5" class="form-control">
        <small class="form-text text-danger">Alamat harus diisi.</small>
    </div>
    ```

    c.
    ```html
    <div class="form-group">
        <label for="">Alamat</label>
        <input type="text" id="" cols="30" rows="5" class="form-control">
        <small class="form-text text-danger">Alamat harus diisi.</small>
    </div>
    ```

    **d.
    ```html
    <div class="form-group">
        <label for="">Alamat</label>
        <textarea name="address" id="" cols="30" rows="5" class="form-control"></textarea>
        <small class="form-text text-danger">Alamat harus diisi.</small>
    </div>
    ```
    **

16. Agar subtotal atau total berada di harga tanpa harus mengisi qty maka perlu menambahkan syntax...

    a. rowspan="2"

    **b. colspan="2"**

    c. row="2"

    d. col="2"

## Membuat Halaman Checkout Berhasil

17. Apa saja isi dari halaman checkout berhasil?

    a. nomor order
    
    b. tata cara pembayaran

    c. halaman konfirmasi bukti pembayaran

    **d. semua benar**

18. Untuk membuat list tata cara pembayaran dengan menggunakan nomer seperti 1,2,3 adalah...

    a.
    ```html
    <ul>
        <li>Lakukan pembayaran pada rekening <strong>BCA 3209123123</strong> a/n PT. CIShop</li>
        <li>Sertakan keterangan dengan nomor order: <strong>0123456123</strong></li>
        <li>Total pembayaran: <strong>Rp300.000,-</strong></li>
    </ul>
    ```

    b.
     ```html
    <ul type="I">
        <li>Lakukan pembayaran pada rekening <strong>BCA 3209123123</strong> a/n PT. CIShop</li>
        <li>Sertakan keterangan dengan nomor order: <strong>0123456123</strong></li>
        <li>Total pembayaran: <strong>Rp300.000,-</strong></li>
    </ul>
    ```

    **c.
     ```html
    <ol>
        <li>Lakukan pembayaran pada rekening <strong>BCA 3209123123</strong> a/n PT. CIShop</li>
        <li>Sertakan keterangan dengan nomor order: <strong>0123456123</strong></li>
        <li>Total pembayaran: <strong>Rp300.000,-</strong></li>
    </ol>
    ```
    **

    d.
     ```html
    <ul type="I">
        <li>Lakukan pembayaran pada rekening <strong>BCA 3209123123</strong> a/n PT. CIShop</li>
        <li>Sertakan keterangan dengan nomor order: <strong>0123456123</strong></li>
        <li>Total pembayaran: <strong>Rp300.000,-</strong></li>
    </ol>
    ```

## Membuat Halaman My Order

19. Source code agar nomer order dapat me-redirect ke halaman order detail adalah...

    a.
    ```html 
    <td>
        <a href="order-detail">#12304123</a>
    </td>
    ```
    
    **b.
    ```html 
    <td>
        <a href="order-detail.html">#12304123</a>
    </td>
    ```
    **

    c.
    ```html 
    <td>
        <a href="order-detail"></a>#12304123
    </td>
    ```

    d.
    ```html 
    <td>
        <a href="order-detail.html"></a>#12304123
    </td>
    ```

20. Source code untuk membuat status order dikirm yang benar adalah

    a.
    ```html 
    <td>
        <span class="badge badge-pill badge-success">Dikirim</span>
    </td>
    ```

    **b.
    ```html 
    <td>
        <span class="badge badge-pill success">Dikirim</span>
    </td>
    ```
    **

    c.
    ```html 
    <td>
        <span class="badge badge-pill badge-success"></span>Dikirim
    </td>
    ```

    d.
    ```html 
    <td>
        <span class="badge badge-pill success"></span>Dikirim
    </td>
    ```

## Membuat Halaman My Order Detail

21. Syntax untuk membuat button konfirmasi pembayaran saat klik maka akan redirect kehalaman konfirmasi pembayaran adalah...

    **a. <a href="/order-confirm.html" class="btn btn-success">Konfirmasi Pembayaran</a>**

    b. <a href="order-confirm" class="btn btn-success"></a>Konfirmasi Pembayaran

    c. <a href="/order-confirm" class="btn btn-success">Konfirmasi Pembayaran</a>

    d. <a href="order-confirm.html" class="btn btn-success"></a>Konfirmasi Pembayaran

## Membuat Halaman My Order Confirm

22. Atribut pada tag input agar field inputan tersebut tidak bisa diubah adalah...
    
    a. require

    b. required

    **c. readonly**

    d. a dan b benar

23. Source code untuk membuat upload file bukti pembayaran adalah

    a.
    ```html
    <div class="form-group">
        <label for="">Bukti Transfer</label> <br>
        <input type="img" name="image" id="">
    </div>
    ```

    b.
    ```html
    <div class="form-group">
        <label for="">Bukti Transfer</label> <br>
        <input type="image" name="image" id="">
    </div>
    ```
    

    **c.
    ```html
    <div class="form-group">
        <label for="">Bukti Transfer</label> <br>
        <input type="file" name="image" id="">
    </div>
    ```
    **
    
    d.
    ```html
    <div class="form-group">
        <label for="">Bukti Transfer</label> <br>
        <img type="file" name="image" id="">
    </div>
    ```

## Membuat Halaman Profil

24. Source code agar gambar pada card body berada di tengah adalah...

    a. 
    ```html
    <div class="card">
        <div class="card-body center">
            <img src="placeholder.co/150x200" alt="">
        </div>
    </div>
    ```

    **b. 
    ```html
    <div class="card">
        <div class="card-body text-center">
            <img src="placeholder.co/150x200" alt="">
        </div>
    </div>
    ```
    **

    a. 
    ```html
    <div class="card">
        <div class="card-body image-center">
            <img src="placeholder.co/150x200" alt="">
        </div>
    </div>
    ```

    a. 
    ```html
    <div class="card">
        <div class="card-body img-center">
            <img src="placeholder.co/150x200" alt="">
        </div>
    </div>
    ```

25. Syntax untuk membuat button edit saat klik akan redirect ke halaman profile update adalah...

    **a. <a href="/profil-update.html" class="btn btn-primary">Edit</a>**

    b. <button href="/profil-update.html" class="btn btn-primary">Edit</button>

    c. <a href="profil-update" class="btn btn-primary">Edit</a>

    d. <button href="profil-update" class="btn btn-primary">Edit</button>
