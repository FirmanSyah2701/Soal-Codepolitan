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

    **a. ``<link href="/assets/libs/bootstrap/css/bootstrap.min.css" rel="stylesheet">``**

    b. ``<link href="assets/libs/bootstrap/css" rel="stylesheet">``

    c. ``<link href="/assets/libs/bootstrap/css/bootstrap.min.css" integrity="stylesheet">``

    d. ``<link href="assets/libs/bootstrap/css" integrity="stylesheet">``

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

    **d.**
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

    **c.** 
    ```html
    <span class="float-right">
        Ututkan harga: <a href="#" class="badge badge-primary"> Termurah </a> | <a href="#" class="badge badge-primary"> Termahal
    </span>
    ```

    d. 
    ```html
    <span class="float-left">
        Ututkan harga: <a href="#" class="badge badge-primary"> Termurah </a> | <a href="#" class="badge badge-primary"> Termahal
    </span>
    ```

12. Source code untuk menggunakan image generator online sesuai ukuran adalah

    **a. ``<img src="placeholder.co/100x70" alt="" class="card-img-top">``**

    b. ``<img src="placeholder.co/100*70" alt="" class="card-img-top">``

    c. ``<img src="placeholder.co/100/70" alt="" class="card-img-top">``

    d. ``<img src="placeholder.co/width=100/height=70" alt="" class="card-img-top">``


## Membuat Halaman Keranjang Belanja

13. Syntax untuk membuat text berwarna putih adalah

    a. white-text

    **b. text-white**

    c. text-primary

    d. white

14. Source code untuk membuat button delete adalah...

    a. ``<button class="btn btn-danger" type="submit"><i class="fa fa-trash"></i></button>``

    **b. ``<button class="btn btn-danger" type="submit"><i class="fas fa-trash-alt"></i></button>``**

    c. ``<button class="btn btn-danger" type="submit"><i class="fas fa-check"></i></button>``

    d. ``<button class="btn btn-danger" type="submit"><i class="fas fa-angle-right"></i></button>``


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

    **d.**
    ```html
    <div class="form-group">
        <label for="">Alamat</label>
        <textarea name="address" id="" cols="30" rows="5" class="form-control"></textarea>
        <small class="form-text text-danger">Alamat harus diisi.</small>
    </div>
    ```

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

    **c.**
     ```html
    <ol>
        <li>Lakukan pembayaran pada rekening <strong>BCA 3209123123</strong> a/n PT. CIShop</li>
        <li>Sertakan keterangan dengan nomor order: <strong>0123456123</strong></li>
        <li>Total pembayaran: <strong>Rp300.000,-</strong></li>
    </ol>
    ```
    

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
    
    **b.**
    ```html 
    <td>
        <a href="order-detail.html">#12304123</a>
    </td>
    ```

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

    **b.**
    ```html 
    <td>
        <span class="badge badge-pill success">Dikirim</span>
    </td>
    ```

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

    **a. ``<a href="/order-confirm.html" class="btn btn-success">Konfirmasi Pembayaran</a>``**

    b. ``<a href="order-confirm" class="btn btn-success"></a>Konfirmasi Pembayaran``

    c. ``<a href="/order-confirm" class="btn btn-success">Konfirmasi Pembayaran</a>``

    d. ``<a href="order-confirm.html" class="btn btn-success"></a>Konfirmasi Pembayaran``

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
    

    **c.**
    ```html
    <div class="form-group">
        <label for="">Bukti Transfer</label> <br>
        <input type="file" name="image" id="">
    </div>
    ```
    
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

    **b.** 
    ```html
    <div class="card">
        <div class="card-body text-center">
            <img src="placeholder.co/150x200" alt="">
        </div>
    </div>
    ```

    c. 
    ```html
    <div class="card">
        <div class="card-body image-center">
            <img src="placeholder.co/150x200" alt="">
        </div>
    </div>
    ```

    d. 
    ```html
    <div class="card">
        <div class="card-body img-center">
            <img src="placeholder.co/150x200" alt="">
        </div>
    </div>
    ```

25. Syntax untuk membuat button edit saat klik akan redirect ke halaman profile update adalah...

    **a. ``<a href="/profil-update.html" class="btn btn-primary">Edit</a>``**

    b. ``<button href="/profil-update.html" class="btn btn-primary">Edit</button>``

    c. ``<a href="profil-update" class="btn btn-primary">Edit</a>``

    d. ``<button href="profil-update" class="btn btn-primary">Edit</button>``

## Membuat Halaman Update Profil

26. Pada halaman update profile syntax input password yang benar adalah...

    a. ``<input type="password" name="password" class="form-control" required autofocus>``

    b. ``<input type="password" name="password" class="form-control" required>``

    **c. ``<input type="password" name="password" class="form-control">``**

    d. ``<input type="text" name="password" class="form-control">``

## Membuat Halaman Admin Tabel Pengguna

27. Source code untuk membuat input cari beserta tombol untuk menghapus/reset keyword yang benar adalah...

    a. 
    ```html
    <div class="input-group">
        <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari">
        <div class="input-group-append">
            <a href="#" class="btn btn-info btn-sm">
                <i class="fas fa-search"></i>
            </a>
        </div>
        <a href="#" class="btn btn-info btn-sm">
            <i class="fas fa-eraser"></i>
        </a>
    </div>
    ```

    b. 
    ```html
    <div class="input-group">
        <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari">
        <div class="input-group-append">
            <button class="btn btn-info btn-sm" type="submit">
                <i class="fas fa-search"></i>
            </button>
        </div>
        <button class="btn btn-info btn-sm" type="submit">
            <i class="fas fa-eraser"></i>
        </button>
    </div>
    ```

    **c.**
    ```html
    <div class="input-group">
        <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari">
        <div class="input-group-append">
            <button class="btn btn-info btn-sm" type="submit">
                <i class="fas fa-search"></i>
            </button>
            <a href="#" class="btn btn-info btn-sm">
                <i class="fas fa-eraser"></i>
            </a>
        </div>
    </div>
    ```

    d. 
    ```html
    <div class="input-group">
        <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari">
        <div class="input-group-append">
            <button class="btn btn-info btn-sm" type="submit">
                <i class="fas fa-search"></i>
            </button>
            <button href="#" class="btn btn-info btn-sm">
                <i class="fas fa-eraser"></i>
            </button>
        </div>
    </div>
    ```

28. Source code untuk membuat button konfirmasi hapus adalah...

    **a.**
    ```html
    <button class="btn btn-sm" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </button>
    ```

    b.
    ```html
    <a class="btn btn-sm" href="#" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </a>
    ```

    c.
    ```html
    <button class="btn btn-sm" type="submit" confirm="Apakah yakin ingin menghapus?">
        <i class="fas fa-trash text-danger"></i>
    </button>
    ```

    d.
    ```html
    <a class="btn btn-sm" href="#" confirm="Apakah yakin ingin menghapus?">
        <i class="fas fa-trash text-danger"></i>
    </a>
    ```

29. Membantu ketidaksengajaan pengguna dalam menghapus suatu data adalah fungsi dari...

    **a. menambahkan onclick return confirm pada tombol hapus**

    b. menambahkan onclick return confirm pada form

    c. menambahkan onclick pada tombol hapus

    d. menambahkan onclick pada form

## Membuat Halaman Admin Formulir Pengguna

30. Source code untuk membuat dropdown role adalah...

    a.
    ```html
    <div class="form-group">
        <label for="">Role</label>
        <select name="role" id="" class="form-control">
            <option value="admin">Admin</option>
            <option value="member">Member</option>
        </select>
    </div>
    ```

    b.
    ```html
    <div class="form-group">
        <label for="">Role</label>
        <select name="role" id="" class="form-control">
            <option value="admin">Admin</option>
            <option value="member">Member</option>
        </select>
    </div>
    ```

    c.
    ```html
    <div class="form-group">
        <label for="">Role</label>
        <select name="role" id="" class="form-control">
            <option value="admin">Admin</option>
            <option value="member">Member</option>
        </select>
    </div>
    ```

    d.
    ```html
    <div class="form-group">
        <label for="">Role</label>
        <select name="role" id="" class="form-control">
            <option value="admin">Admin</option>
            <option value="member">Member</option>
        </select>
    </div>
    ```

31. Source code untuk membuat radio option status adalah...

    a.
    ```html
    <div class="form-group">
        <label for="">Status</label>
        <br>
        <div class="form-check form-check-inline">
            <label for="" class="form-check-label">Aktif</label>
            <input type="radio" name="status" class="form-check-input" value="1">
        </div>
        <div class="form-check form-check-inline">
            <label for="" class="form-check-label">Non-Aktif</label>
            <input type="radio" class="form-check-input" value="1">
        </div>
    </div>
    ```

    b.
    ```html
    <div class="form-group">
        <label for="">Status</label>
        <br>
        <div class="form-check form-check-inline">
            <label for="" class="form-check-label">Aktif</label>
            <input type="radio" name="1" class="form-check-input" value="status">
        </div>
        <div class="form-check form-check-inline">
            <label for="" class="form-check-label">Non-Aktif</label>
            <input type="radio" name="1" class="form-check-input" value="status">
        </div>
    </div>
    ```

    **c.**
    ```html
    <div class="form-group">
        <label for="">Status</label>
        <br>
        <div class="form-check form-check-inline">
            <input type="radio" name="status" class="form-check-input" value="1">
            <label for="" class="form-check-label">Aktif</label>
        </div>
        <div class="form-check form-check-inline">
            <input type="radio" name="status" class="form-check-input" value="1">
            <label for="" class="form-check-label">Non-Aktif</label>
        </div>
    </div>
    ```

    d.
    ```html
    <div class="form-group">
        <label for="">Status</label>
        <br>
        <div class="form-check form-check-inline">
            <input type="radio" class="form-check-input" value="status">
            <label for="" class="form-check-label">Aktif</label>
            <input type="radio" class="form-check-input" value="status">
            <label for="" class="form-check-label">Non-Aktif</label>
        </div>
    </div>
    ```

## Membuat Halaman Admin Tabel Kategori

32. Apa dimaksud dengan slug?

    a. Url title yang dipisahkan dengan spasi menjadi slash(/)

    **b. Url title yang dipisahkan dengan spasi menjadi dash(-)**

    c. Url title yang dipisahkan dengan spasi menjadi dot(.)

    d. Url title yang dipisahkan dengan spasi menjadi percent(%)

33. Berikut ini yang bukan merupakan sifat dari slug adalah...

    a. lowercase

    **b. uppercase**

    c. titik(.) akan dilewat

    d. spasi menjadi dash(-)

## Membuat Halaman Admin Formulir Kategori

34. Syntax javascript memindahkan value dari title kedalam slug adalah...

    a.
    ```javascript
    function createSlug() {
        let title = $('#title').val();
        $('#title').val(string_to_slug(title));
    }
    ```

    **b.**
    ```javascript
    function createSlug() {
        let title = $('#title').val();
        $('#slug').val(string_to_slug(title));
    }
    ```

    c.
    ```javascript
    function createSlug() {
        let title = $('.title').val();
        $('.slug').val(string_to_slug(title));
    }
    ```

    d.
    ```javascript
    function createSlug() {
        let title = $('#title').val();
        $('#slug').val(string_to_slug('#title'));
    }
    ```

35. Source code untuk membuat event dengan memanggil fungsi javascript createSlug yaitu...

    a. ``<input type="text" class="form-control" id="title" onclick="createSlug" required autofocus> ``

    b. ``<input type="text" class="form-control" id="title" onclick="createSlug()" required autofocus> ``

    c. ``<input type="text" class="form-control" id="title" onkeyup="createSlug" required autofocus> ``

    **d. ``<input type="text" class="form-control" id="title" onkeyup="createSlug()" required autofocus> ``**

## Membuat Halaman Admin Tabel Produk

## Membuat Halaman Admin Formulir Produk

36. Syntax untuk membuat input harga yang benar adalah...

    a.
    ```html
    <div class="form-group">
        <label for="">Harga</label>
        <input type="radio" class="form-control" required>
        <small class="form-text text-danger"> Harga Harus Diisi.</small>
    </div>
    ```

    b.
    ```html
    <div class="form-group">
        <label for="">Harga</label>
        <input type="checkbox" class="form-control" required>
        <small class="form-text text-danger"> Harga Harus Diisi.</small>
    </div>
    ```

    **c.**
    ```html
    <div class="form-group">
        <label for="">Harga</label>
        <input type="number" class="form-control" required>
        <small class="form-text text-danger"> Harga Harus Diisi.</small>
    </div>
    ```

    d.
    ```html
    <div class="form-group">
        <label for="">Harga</label>
        <input type="text" class="form-control" required>
        <small class="form-text text-danger"> Harga Harus Diisi.</small>
    </div>
    ```

## Membuat Halaman Admin Tabel Order

## Membuat Halaman Admin Detail Order

37. Source code yang benar untuk membuat drodown status order adalah...

    a. 
    ```html
    <form action="#">
        <div class="input-group">
            <select name="" id="" class="form-control">
                <option>Menunggu Pembayaran</option>
                <option>Dibayar</option>
                <option>Dikirim</option>
                <option>Batal</option>
            </select>
            <div class="input-group-append">
                <button class="btn btn-primary" type="submit">Simpan</button>
            </div>
        </div>
    </form>
    ```

    b. 
    ```html
    <form action="#">
        <div class="input-group">
            <select name="" id="" class="form-control">
                <option value="waiting">
                <option value="paid"> 
                <option value="delivered">
                <option value="cancel">
            </select>
            <div class="input-group-append">
                <button class="btn btn-primary" type="submit">Simpan</button>
            </div>
        </div>
    </form>
    ```

    **c.** 
    ```html
    <form action="#">
        <div class="input-group">
            <select name="" id="" class="form-control">
                <option value="waiting">Menunggu Pembayaran</option>
                <option value="paid">Dibayar</option>
                <option value="delivered">Dikirim</option>
                <option value="cancel">>Batal</option>
            </select>
            <div class="input-group-append">
                <button class="btn btn-primary" type="submit">Simpan</button>
            </div>
        </div>
    </form>
    ```

    d. 
    ```html
    <form action="#">
        <div class="input-group">
            <select name="" id="" class="form-control">
                <option name="waiting">Menunggu Pembayaran</option>
                <option name="paid">Dibayar</option>
                <option name="delivered">Dikirim</option>
                <option name="cancel">>Batal</option>
            </select>
            <div class="input-group-append">
                <button class="btn btn-primary" type="submit">Simpan</button>
            </div>
        </div>
    </form>
    ```

38. Untuk membuat status dalam database mysql sebaiknya menggunakan tipe data?

    a. array

    **b. enum**

    c. char 

    d. text

# Persiapan Framework CodeIgniter

## Cara Install Codeigniter dan Mempercantik URL

39. Saat menggunakan xampp setelah mendownload codeigniter sebaiknya folder codeigniter diletakan di directori

    a. Documents

    b. Downloads
    
    c. xampp

    **d. htdocs**

40. Synrax untuk membuat virtualhost dengan domain local cishop.test di httpd-vhosts.conf xampp adalah... 
    
    a. 
    ```xml
    <VirtualHost *:80>
        DocumentRoot "/Application/XAMPP/xamppfiles/htdocs/"
        Servername cishop.test
    </VirtualHost>
    ```

    b.
    ```xml
    <VirtualHost *:80>
        DocumentRoot "/Application/XAMPP/xamppfiles/htdocs/"
        Servername cishop.test
    </VirtualHost>

    <VirtualHost *:80>
        DocumentRoot "/Application/XAMPP/xamppfiles/htdocs/"
        Servername cishop.test
    </VirtualHost>
    ```

    **c.**
    ```xml
    <VirtualHost *:80>
        DocumentRoot "/Application/XAMPP/xamppfiles/htdocs/"
        Servername localhost
    </VirtualHost>

    <VirtualHost *:80>
        DocumentRoot "/Application/XAMPP/xamppfiles/htdocs/"
        Servername cishop.test
    </VirtualHost>
    ```

    d.
    ```xml
    <VirtualHost *:80>
        DocumentRoot "/Application/XAMPP/xamppfiles/htdocs/"
        Servername cishop.test
    </VirtualHost>

    <VirtualHost *:80>
        DocumentRoot "/Application/XAMPP/xamppfiles/htdocs/"
        Servername localhost
    </VirtualHost>
    ```

41. Cara menghapus url index.php dicodeigniter dengan adalah...

    **a. membuat .htaccess**

    b. merubah config base_url 

    c. mengosongkan config index_page

    d. b dan c benar

## Persiapan Autoload Libraries dan Helpers

42. Difile manakah untuk memuat/memasukan libraries dan helper?
    
    a. config.php

    **b. autoload.php**

    c. constants.php

    d. hooks.php

43. Apa saja yang perlu diisi untuk mengkoneksikan database?
    
    a. username dan password

    b. username dan password, database

    c.  username, database

    **d. b dan c benar**

44. Library yang diperlukan untuk bisa menggunakan fungsi base_url yang sudah dibuat pada file config.php adalah?

    a. form

    b. session

    **c. url**

    d. database

# Membuat Custom Model Controller dan Helper

## Membuat Core Class Controller Sendiri

45. Syntax untuk mendapatkan nama class dengan huruf kecil semua adalah...

    a. $model = strtoupper(get_class($this));

    **b. $model = strtolower(get_class($this));**

    c. $model = strtosmall(get_class($this));

    d. $model = strtolarge(get_class($this));

46. Maksud dari syntax dibawah ini adalah
    ```php
    if(file_exists(APPPATH . 'models/'. $model . '_model.php')) 
    ```

    a. mencari apakah ada file dengan nama class yang sama dan berextensi atau .php

    b. mencari apakah ada file pada folde model dengan nama model_model.php
    
    c. mencari apakah ada file pada folder model dengan nama class yang sama dan berextensi atau .php

    **d. mencari apakah ada file pada folder model dengan nama class yang sama dan dengan akhiran _model.php**

47. Syntax untuk meload data view yang benar pada custom class core adalah...

    a. 
    ```php
    public function view()
    {
        $this->load->view('layouts/app', $data);
    }
    ```

    **b.** 
    ```php
    public function view($data)
    {
        $this->load->view('layouts/app', $data);
    }
    ```

    c. 
    ```php
    public function view($data)
    {
        $this->load->data('layouts/app');
    }
    ```

    d. 
    ```php
    public function view($data)
    {
        $this->load->data('layouts/app', $data);
    }
    ```

## Membuat Fungsi Pemanggilan Nama Tabel Otomatis

48. Apa maksud dari enkapsulasi protected?

    a. Attribut tersebut bisa diubah dimana saja

    b. Attribut tersebut hanya bisa diubah didalam class parent itu sendiri

    **c. Attribut tersebut hanya bisa diubah didalam class parent dan child itu sendiri**

    d. Attribut tersebut konstant tidak dapat diubah-ubah

49. Syntax untuk mendapatkan nama tabel sesuai dengan nama model adalah...

    a. 
    ```php
    if(!$this->table){
        $this->table = strtolower(
            str_replace('_model', get_class($this));
        );
    }
    ```

    **b.** 
    ```php
    if(!$this->table){
        $this->table = strtolower(
            str_replace('_model', '', get_class($this));
        );
    }
    ```

    c. 
    ```php
    if(!$this->table){
        $this->table = strtolower(
            substr_replace('_model', get_class($this));
        );
    }
    ```

    d. 
    ```php
    if(!$this->table){
        $this->table = strtolower(
            substr_replace('_model', '', get_class($this));
        );
    }
    ```

## Membuat Fungsi Validasi Input

50. Nama library yang digunakan untuk membuat fungsi validasi adalah...

    a. validation

    b. validation_rules

    **c. form_validation**

    d. input_validation

51. Untuk membuat pesan error dengan library form_validation dapat menggunakan fungsi...

    a. getErrorValidation()

    b. set_rules()

    c. set_errors()

    **d. set_error_delimiters()**

## Membuat Fungsi Umum dari Query Database

52. Kegunaan dari query builder like adalah...

    a. untuk menampilkan seluruh data

    b. untuk menampilkan data awal
    
    **c. untuk mencari kolom tertentu dengan nilai/value yang mirip**

    d. untuk mengurutkan data berdasarkan kondisi yang ditentukan

53. Source code untuk membuat query builder urutan data dengan default ascending adalah...

    **a.**
    ```php
    public function orderBy($column, $order = 'asc')
    {
        $this->db->order_by($column, $order);
        return $this;
    }
    ```

    b.
    ```php
    public function orderBy($column, $order = 'desc')
    {
        $this->db->order_by($column, $order);
        return $this;
    }
    ```

    c.
    ```php
    public function orderBy($column, $order = 'asc')
    {
        $this->db->sort_by($column, $order);
        return $this;
    }
    ```

    d.
    ```php
    public function orderBy($column, $order = 'desc')
    {
        $this->db->sort_by($column, $order);
        return $this;
    }
    ```

54. Kegunaan dari query builder count adalah...

    **a. Dapat menampilkan jumlah data**

    b. Dapat menghitung data terbesar

    c. Dapat menghitung data terkecil

    d. b dan c benar

55. Source code untuk membuat query builder create yang benar adalah...

    a.
    ```php
    public function create($data)
    {
        $this->db->create($this->table, $data);
        return $this->db->create_id();
    }
    ```

    b.
    ```php
    public function create($data)
    {
        $this->db->create($this->table, $data);
        return $this->db->create_id($this->table);
    }
    ```

    **c.**
    ```php
    public function create($data)
    {
        $this->db->insert($this->table, $data);
        return $this->db->insert_id();
    }
    ```

    d.
    ```php
    public function create($data)
    {
        $this->db->insert($this->table, $data);
        return $this->db->insert_id($this->table);
    }
    ```

56. Source code untuk membuat query builder delete yang benar adalah...

    **a.**
    ```php
    public function delete($data)
    {
        $this->db->delete($this->table, $data);
        return $this->db->affected_rows();
    }
    ```

    b.
    ```php
    public function delete($data)
    {
        $this->db->delete($this->table, $data);
        return $this->db->affected_rows($this->table);
    }
    ```

    c.
    ```php
    public function delete($data)
    {
        $this->db->delete($data);
        return $this->db->affected_all_rows();
    }
    ```

    d.
    ```php
    public function delete($data)
    {
        $this->db->delete($data);
        return $this->db->affected_all_rows($this->table);
    }
    ```

57. Query builder untuk menggabungkan table yang berelasi yang memiliki foreign key adalah

    a. like()

    b. first()

    c. get()

    **d. join()**

## Membuat Fungsi Pagination

58. Kegunaan dari pagination yang benar adalah?

    a. Menampilkan sejumlah data dengan dibagi-bagi tanpa memuat semuanya

    b. Menampilkan sejumlah data agar tidak lambat atau crash 

    c. Menampilkan seluruh data pada suatu halaman

    **d. A dan B benar**

59. Source code untuk membuat nilai offset?

    a.
    ```php
    if (is_null($page) && empty($page)) {
			$offset = 0;
		} else {
			$offset = ($page - $this->perPage) * $this->perPage;
		}

		return $offset;
    }
    ```

    b.
    ```php
    if (is_null($page) || empty($page)) {
			$offset = 0;
		} else {
			$offset = ($page - $this->perPage) * $this->perPage;
		}

		return $offset;
    }
    ```

    c.
    ```php
    if (is_null($page) && empty($page)) {
			$offset = 0;
		} else {
			$offset = ($page * $this->perPage) - $this->perPage;
		}

		return $offset;
    }
    ```

    **d.**
    ```php
    if (is_null($page) || empty($page)) {
			$offset = 0;
		} else {
			$offset = ($page * $this->perPage) - $this->perPage;
		}

		return $offset;
    }
    ```

## Membuat Helper dan Konfigurasi Zona Waktu

60. Cara membuat enkripsi password dicodeigniter adalah...

    a.
    ```php
    function hashEncrypt($input){
        $hash = password_hash($input, PASSWORD_HASH);
        return $hash;
    }
    ```

    **b.**
    ```php
    function hashEncrypt($input){
        $hash = password_hash($input, PASSWORD_DEFAULT);
        return $hash;
    }
    ```

    c.
    ```php
    function hashEncrypt($input){
        $hash = password_default($input, PASSWORD_HASH);
        return $hash;
    }
    ```

    d.
    ```php
    function hashEncrypt($input){
        $hash = hash($input, PASSWORD_DEFAULT);
        return $hash;
    }
    ```

61. Source code untuk konfigurasi/menambahkan zona waktu adalah...

    a. 
    ```php
    date_timezone_set('Asia/Jakarta');
    ```

    b. 
    ```php
    timezone_set('Asia/Jakarta');
    ```

    c. 
    ```php
    datetime_set('Asia/Jakarta');
    ```

    **d.**
    ```php
    date_default_timezone_set('Asia/Jakarta');
    ```

# Menggabungkan Template dengan CodeIgniter

## Menggunakan Template pada Codeigniter

62. Source code untuk membuat controller Home untuk menampilkan halaman home adalah...

    a. 
    ```php
    <?php
        defined('BASEPATH') OR exit('No direct script access allowed');

        class Home extends CI_Controller 
        {
            public function index()
            {
                $data['title'] => 'Homepage';
                $data['page']  => 'pages/home/index';
                $this->view($data);
            }
        }
    ```

    b. 
    ```php
    <?php
        defined('BASEPATH') OR exit('No direct script access allowed');

        class Home extends Controller 
        {
            public function index()
            {
                $data['title'] => 'Homepage';
                $data['page']  => 'pages/home/index';
                $this->load->view($data);
            }
        }
    ```

    **c.**
    ```php
    <?php
        defined('BASEPATH') OR exit('No direct script access allowed');

        class Home extends MY_Controller 
        {
            public function index()
            {
                $data['title'] => 'Homepage';
                $data['page']  => 'pages/home/index';
                $this->view($data);
            }
        }
    ```

    d. 
    ```php
    <?php
        defined('BASEPATH') OR exit('No direct script access allowed');

        class Home extends Controller 
        {
            public function index()
            {
                $data['title'] => 'Homepage';
                $data['page'] => 'pages/home/index';
                $this->view($data);
            }
        }
    ```

63. Source code untuk membuat title dinamis yang benar adalah...

    a. ```php <?php isset($title) ? $title : 'CIShop' ?>```

    b. ```php <?php isset($title) ? 'CIShop' : $title  ?>```

    **c. ```php <?= isset($title) ? $title : 'CIShop' ?>```**

    d. ```php <?= isset($title) ? 'CIShop' : $title ?>```

## Membuat Element Alert untuk Notifikasi

64. Source code untuk membuat alert success, error dan warning...

    a.
    ```html
    <?php if ($success || $error || $warning): ?>
        <div class="row">
            <div class="col-md-12">
                <div class="alert <?php $alert_status ?> alert-dismissible fade show" role="alert">
                    <strong><?php $status ?></strong> <?php $message ?>
                    <button type="button" class="close" data-dismiss="alert" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>
            </div>
        </div>
    <?php endif ?>
    ```

    **b.**
    ```html
    <?php if ($success || $error || $warning): ?>
        <div class="row">
            <div class="col-md-12">
                <div class="alert <?= $alert_status ?> alert-dismissible fade show" role="alert">
                    <strong><?= $status ?></strong> <?= $message ?>
                    <button type="button" class="close" data-dismiss="alert" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>
            </div>
        </div>
    <?php endif ?>
    ```

    c.
    ```html
    <?php if ($success && $error && $warning): ?>
        <div class="row">
            <div class="col-md-12">
                <div class="alert <?php $alert_status ?> alert-dismissible fade show" role="alert">
                    <strong><?php $status ?></strong> <?php $message ?>
                    <button type="button" class="close" data-dismiss="alert" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>
            </div>
        </div>
    <?php endif ?>
    ```

    d.
    ```html
    <?php if ($success && $error && $warning): ?>
        <div class="row">
            <div class="col-md-12">
                <div class="alert <?= $alert_status ?> alert-dismissible fade show" role="alert">
                    <strong><?= $status ?></strong> <?= $message ?>
                    <button type="button" class="close" data-dismiss="alert" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>
            </div>
        </div>
    <?php endif ?>
    ```

65. Source untuk memanggil session flash data adalah...

    **a. ```php $this->session->flashdata('success')```**

    b. ```php $this->session->flashdata($this->success)```

    c. ```php session->flashdata('success')```

    d. ```php session->flashdata($this->success)```

# Membuat Modul Register

## Membuat Tabel User dan Model Register

66. Dibawah ini yang bukan merupakan rules validation dicodeigniter adalah...

    a. trim

    b. required

    **c. unique[]**

    d. min_length[]

67. Source code untuk membuat registrasi beserta session data di model adalah...

    a.
    ```php
    public function run($input)
    {
        $data		= [
			'name'		=> $input->name,
			'email'		=> strtolower($input->email),
			'password'	=> hashEncrypt($input->password),
			'role'		=> 'member'
		];

		$user		= $this->db->create($data);

		$sess_data	= [
			'id'		=> $user,
			'name'		=> $data['name'],
			'email'		=> $data['email'],
			'role'		=> $data['role'],
			'is_login'	=> true
		];

		$this->session->set_flashdata($sess_data);
		return true;
    }
    ```

    b.
    ```php
    public function run($input)
    {
        $data		= [
			'name'		=> $input->name,
			'email'		=> strtolower($input->email),
			'password'	=> hashEncrypt($input->password),
			'role'		=> 'member'
		];

		$user		= $this->db->insert_data($data);

		$sess_data	= [
			'id'		=> $user,
			'name'		=> $data['name'],
			'email'		=> $data['email'],
			'role'		=> $data['role'],
			'is_login'	=> true
		];

		$this->session->flashdata($sess_data);
		return true;
    }
    ```

    **c.**
    ```php
    public function run($input)
    {
        $data		= [
			'name'		=> $input->name,
			'email'		=> strtolower($input->email),
			'password'	=> hashEncrypt($input->password),
			'role'		=> 'member'
		];

		$user		= $this->create($data);

		$sess_data	= [
			'id'		=> $user,
			'name'		=> $data['name'],
			'email'		=> $data['email'],
			'role'		=> $data['role'],
			'is_login'	=> true
		];

		$this->session->set_userdata($sess_data);
		return true;
    }
    ```

    d.
    ```php
    public function run($input){
        $data		= [
			'name'		=> $input->name,
			'email'		=> strtolower($input->email),
			'password'	=> hashEncrypt($input->password),
			'role'		=> 'member'
		];

		$user		= $this->create($data);

		$sess_data	= [
			'id'		=> $user,
			'name'		=> $data['name'],
			'email'		=> $data['email'],
			'role'		=> $data['role'],
			'is_login'	=> true
		];

		$this->session->userdata($sess_data);
		return true;
    }
    ```

## Membuat Controller untuk Register

68. Source code untuk mencegah user ke halaman register apabila user sudah login

    a. 
    ```php 
    public function __construct()
    {
        parent::__construct();
        $is_login = $this->session->flashdata('is_login');

        if($is_login) {
            redirect(base_url());
            return;
        }
    }
    ```

    b. 
    ```php 
    public function __construct()
    {
        parent::__construct();
        $is_login = $this->session->flashdata('is_login');

        if(!$is_login) {
            redirect(base_url());
            return;
        }
    }
    ```
    
    **c.** 
    ```php 
    public function __construct()
    {
        parent::__construct();
        $is_login = $this->session->userdata('is_login');

        if($is_login) {
            redirect(base_url());
            return;
        }
    }
    ```

    d. 
    ```php 
    public function __construct()
    {
        parent::__construct();
        $is_login = $this->session->userdata('is_login');

        if(!$is_login) {
            redirect(base_url());
            return;
        }
    }
    ```

69. Maksud dari syntax berikut adalah ``if(!$this->register->validate())``

    a. merupakan kondisi apabila validasi berjalan

    **b. merupakan kondisi jika tidak ada proses validasi**

    c. merupakan kondisi untuk melakukan create data

    d. merupakan kondisi apabila proses create data gagal

## Membuat Halaman Register

70. Source code untuk membuat form action dan method menggunakan form helper yang benar adalah...

    a. ``<?php form_open('register', ['method' => 'POST']) { ?>``

    b. ``<?= form_open('register', ['method' => 'POST']) { ?>``

    c. ``<?php form_open('register', ['method' => 'POST']) ?>``

    **d. ``<?= form_open('register', ['method' => 'POST']) ?>``**

71. Source code untuk membuat input name dengan menggunakan form helper adalah...

    ``a. <?= form_input('name', '', ['class' => 'form_control', 'required' => true, 'autofocus' => true]) ?>``

    **``b. <?= form_input('name', $input->name, ['class' => 'form_control', 'required' => true, 'autofocus' => true]) ?>``**

    ``c. <?= form_input('name', '$input->name', ['class' => 'form_control', 'required' => 'true', 'autofocus' => 'true']) ?>``

    ``d. <?= form_input('name', '', ['class' => 'form_control', 'required', 'autofocus']) ?>``

# Membuat Modul Login dan Logout

## Membuat Model Login

72. Source code untuk mencari suatu user dengan email yang dinputkan beserta status is_active 1 adalah...

    **a. ``$this->where('email', strtolower($input->email))->where('is_active', 1)->first();``**

    b. ``$this->db->where('email', strtolower($input->email))->where('is_active', 1)->first();``

    c. ``$this->user->where('email', strtolower($input->email))->where('is_active', 1)->first();``

    d. ``$this->user('email', strtolower($input->email))->where('is_active', 1)->get();``

73. Source code untuk membuat kondisi jika query user tidak kosong dan input password sama dengan hasil enkripsi password dari query user adalah...

    a. ``if(empty($query) && hashEncryptVerify($input->password, $query->password)) {}``

    **b. ``if(!empty($query) && hashEncryptVerify($input->password, $query->password)) {}``**

    c. ``if(empty($query) || hashEncryptVerify($input->password, $query->password)) {}``

    d. ``if(!empty($query) || hashEncryptVerify($input->password, $query->password)) {}``

## Membuat Controller untuk Login

74. Source code untuk membuat kondisi jika gagal login adalah...

    a.
    ```php 
    if($this->login->run($input)){
        $this->session->set_flashdata('error', 'E-Mail atau Password salah atau akun Anda sedang tidak aktif!');
		redirect(base_url());
    }
    ```

    b.
    ```php 
    if(!$this->login->run($input)){
        $this->session->set_flashdata('error', 'E-Mail atau Password salah atau akun Anda sedang tidak aktif!');
		redirect(base_url());
    }
    ```

    c.
    ```php 
    if($this->login->run($input)){
        $this->session->set_flashdata('error', 'E-Mail atau Password salah atau akun Anda sedang tidak aktif!');
		redirect(base_url('login'));
    }
    ```

    **d.**
    ```php 
    if(!$this->login->run($input)){
        $this->session->set_flashdata('error', 'E-Mail atau Password salah atau akun Anda sedang tidak aktif!');
		redirect(base_url('login'));
    }
    ```

75.

## Membuat Halaman Login dan Perbaikan Helper

76. 

77.

## Membuat Fungsi Logout

78. Source code untuk membuat fungsi logout adalah...

    a.
    ```php
    public function index()
	{
		$sess_data = [
			'id', 'name', 'email', 'role', 'is_login'
		];

		$this->session->set_userdata($sess_data);
		$this->session->sess_delete();
		redirect(base_url());
	}
    ```

    b.
    ```php
    public function index()
	{
		$sess_data = [
			'id', 'name', 'email', 'role', 'is_login'
		];

		$this->session->unset_userdata($sess_data);
		$this->session->sess_delete();
		redirect(base_url());
	}
    ```

    c.
    ```php
    public function index()
	{
		$sess_data = [
			'id', 'name', 'email', 'role', 'is_login'
		];

		$this->session->set_userdata($sess_data);
		$this->session->sess_destroy();
		redirect(base_url());
	}
    ```

    **d.**
    ```php
    public function index()
	{
		$sess_data = [
			'id', 'name', 'email', 'role', 'is_login'
		];

		$this->session->unset_userdata($sess_data);
		$this->session->sess_destroy();
		redirect(base_url());
	}
    ```

79. Source code untuk menampilkan jika user belum login maka akan menampilkan menu login dan register jika sudah login maka akan menampilkan menu logout

    a.
    ```html
    <?php if ($this->session->userdata('is_login') === true) : ?>
    <li class="nav-item">
        <a href="<?= base_url('/login') ?>" class="nav-link">Login</a>
    </li>
    <li class="nav-item">
        <a href="<?= base_url('/register') ?>" class="nav-link">Register</a>
    </li>
    <?php else : ?>
    <li class="nav-item">
        <a href="<?= base_url('/logout') ?>" class="nav-link">Logout</a>
    </li>
	<?php endif ?>
    ```

    b.
    ```html
    <?php if ($this->session->userdata('is_login') == true) : ?>
    <li class="nav-item">
        <a href="<?= base_url('/login') ?>" class="nav-link">Login</a>
    </li>
    <li class="nav-item">
            <a href="<?= base_url('/register') ?>" class="nav-link">Register</a>
        </li>
    <?php else : ?>
    <li class="nav-item">
        <a href="<?= base_url('/logout') ?>" class="nav-link">Logout</a>
    </li>
	<?php endif ?>
    ```

    **c.**
    ```html
    <?php if (! $this->session->userdata('is_login')) : ?>
    <li class="nav-item">
        <a href="<?= base_url('/login') ?>" class="nav-link">Login</a>
    </li>
    <li class="nav-item">
        <a href="<?= base_url('/register') ?>" class="nav-link">Register</a>
    </li>
    <?php else : ?>
    <li class="nav-item">
        <a href="<?= base_url('/logout') ?>" class="nav-link">Logout</a>
    </li>
	<?php endif ?>
    ```

    d.
    ```html
    <?php if (! $this->session->userdata('is_login')) : ?>
        <li class="nav-item">
            <a href="<?= base_url('/logout') ?>" class="nav-link">Logout</a>
        </li>
    <?php else : ?>
        <li class="nav-item">
            <a href="<?= base_url('/login') ?>" class="nav-link">Login</a>
        </li>
        <li class="nav-item">
            <a href="<?= base_url('/register') ?>" class="nav-link">Register</a>
        </li>
	<?php endif ?>
    ```

# Membuat Modul Admin Kategori Produk

## Membuat Tabel dan Model Kategori

80. Field apa saja yang dibutuhkan untuk membuat tabel kategori...

    a. title, slug 

    b. id, title

    **c. id, title, slug**

    d. id, title, slug, name

## Membuat Controller Kategori dan Fungsi Index

81. Source code untuk get data kategori dengan pagination adalah...

    a.
    ```php 
    public function index($page)
    {
        $data['title']      = 'Admin: Categori';
        $data['content']    = $this->categori->paginate($page)->get();
        $data['total_rows'] = $this->categori->count();
        $data['pagination'] = $this->categori->makePagination(
            base_url('categori'), 2, $data['total_rows']
        );
        $data['pages']      = 'pages/category/index';

        $this->view($data);
    }
    ```

    **b.**
    ```php 
    public function index($page = null)
    {
        $data['title']      = 'Admin: Categori';
        $data['content']    = $this->categori->paginate($page)->get();
        $data['total_rows'] = $this->categori->count();
        $data['pagination'] = $this->categori->makePagination(
            base_url('categori'), 2, $data['total_rows']
        );
        $data['pages']      = 'pages/category/index';

        $this->view($data);
    }
    ```

    c.
    ```php 
    public function index($page = 1) 
    {
        $data['title']      = 'Admin: Categori';
        $data['content']    = $this->categori->paginate($page)->first();
        $data['total_rows'] = $this->categori->count();
        $data['pagination'] = $this->categori->makePagination(
            base_url('categori'), 2, $data['total_rows']
        );
        $data['pages']      = 'pages/category/index';

        $this->view($data);
    }
    ```

    d.
    ```php 
    public function index($page = null){
        $data['title']      = 'Admin: Categori';
        $data['content']    = $this->categori->paginate($page)->first();
        $data['total_rows'] = $this->categori->count();
        $data['pagination'] = $this->categori->makePagination(
            base_url('categori'), 2, $data['total_rows']
        );
        $data['pages']      = 'pages/category/index';

        $this->view($data);
    }
    ```

82. Source code untuk membuat route categori dengan page adalah

    a. `` $route['category/(:num)'] = 'category/index'; ``

    b. `` $route['category/(:num)'] = 'category/index/$num'; ``

    **c. `` $route['category/:num'] = 'category/index/$1'; ``**

    d. `` $route['category/:num'] = 'category/index/$num'; ``

## Menampilkan Data Kategori Menggunakan Pagination

83. Source code untuk menampilkan data kategori di views adalah

    a.
    ```html
    <?php $no = 0; foreach ($content as $row) :  $no+1;?>
    <tr>
        <td><?= $no ?></td>
        <td><?= $row->title ?></td>
        <td><?= $row->slug ?></td>
        <td>
            <a href="#" class="btn btn-sm">
                <i class="fas fa-edit text-info"></i>
            </a>
            <button class="btn btn-sm" type="submit">
                <i class="fas fa-trash text-danger"></i>
            </button>
        </td>
    </tr>
    <?php endforeach ?>
    ```

    b.
    ```html
    <?php $no = 1; foreach ($content as $row) :  $no+1;?>
    <tr>
        <td><?= $no ?></td>
        <td><?= $row->title ?></td>
        <td><?= $row->slug ?></td>
        <td>
            <a href="#" class="btn btn-sm">
                <i class="fas fa-edit text-info"></i>
            </a>
            <button class="btn btn-sm" type="submit">
                <i class="fas fa-trash text-danger"></i>
            </button>
        </td>
    </tr>
    <?php endforeach ?>
    ```

    **c.**
    ```html
    <?php $no = 0; foreach ($content as $row) :  $no++;?>
    <tr>
        <td><?= $no ?></td>
        <td><?= $row->title ?></td>
        <td><?= $row->slug ?></td>
        <td>
            <a href="#" class="btn btn-sm">
                <i class="fas fa-edit text-info"></i>
            </a>
            <button class="btn btn-sm" type="submit">
                <i class="fas fa-trash text-danger"></i>
            </button>
        </td>
    </tr>
    <?php endforeach ?>
    ```

    d.
    ```html
    <?php $no = 1; foreach ($content as $row) :  $no++;?>
    <tr>
        <td><?= $no ?></td>
        <td><?= $row->title ?></td>
        <td><?= $row->slug ?></td>
        <td>
            <a href="#" class="btn btn-sm">
                <i class="fas fa-edit text-info"></i>
            </a>
            <button class="btn btn-sm" type="submit">
                <i class="fas fa-trash text-danger"></i>
            </button>
        </td>
    </tr>
    <?php endforeach ?>
    ```

84. Source code untuk menampilkan pagination dengan bootstrap adalah...

    a. 
    ```html
    <nav aria-label="Page navigation example">
	    <?php $pagination ?>
	</nav>
    ```

    b. 
    ```html
    <nav aria-label="Page navigation example">
	    <?= echo $pagination ?>
	</nav>
    ```

    **c.**
    ```html
    <nav aria-label="Page navigation example">
	    <?= $pagination ?>
	</nav>
    ```

    d. 
    ```html
    <nav aria-label="Page navigation example">
	    <?= $pagination++ ?>
	</nav>
    ```

## Membuat Fungsi Tambah Kategori

85. Source code untuk create kategori jika validasi gagal adalah...

    a.
    ```php
    if (!$this->category->validate()) {
        $data['title']			= 'Tambah Kategori';
        $data['input']			= $input;
        $data['form_action']	= base_url('category/create');
        $data['page']			= 'pages/category/form';

        $this->view($data);
	}
    ```

    **b.**
    ```php
    if (!$this->category->validate()) {
        $data['title']			= 'Tambah Kategori';
        $data['input']			= $input;
        $data['form_action']	= base_url('category/create');
        $data['page']			= 'pages/category/form';

        $this->view($data);
        return;
	}
    ```

    c.
    ```php
    if ($this->category->validate()) {
        $data['title']			= 'Tambah Kategori';
        $data['input']			= $input;
        $data['form_action']	= base_url('category/create');
        $data['page']			= 'pages/category/form';

        $this->view($data);
	}
    ```

    d.
    ```php
    if ($this->category->validate()) {
        $data['title']			= 'Tambah Kategori';
        $data['input']			= $input;
        $data['form_action']	= base_url('category/create');
        $data['page']			= 'pages/category/form';

        $this->view($data);
        return;
	}
    ```

86. Source code untuk menvalidasi apakah berhasil melakukan insert/create kategori adalah...

    a.
    ```php
    if ($this->category->run()) {
		$this->session->set_flashdata('success', 'Data berhasil disimpan!');
	} else {
		$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
	}
    
    redirect(base_url('category'));
    ```

    b.
    ```php
    if ($this->category->run($input)) {
		$this->session->set_flashdata('success', 'Data berhasil disimpan!');
	} else {
		$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
	}

    redirect(base_url('category'));
    ```

    c.
    ```php
    if ($this->category->create()) {
		$this->session->set_flashdata('success', 'Data berhasil disimpan!');
	} else {
		$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
	}

    redirect(base_url('category'));
    ```

    **d.**
    ```php
    if ($this->category->create($input)) {
		$this->session->set_flashdata('success', 'Data berhasil disimpan!');
	} else {
		$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
	}

    redirect(base_url('category'));
    ```

## Membuat Halaman Formulir dan Fungsi Validasi

87. Source code untuk menambahkan form hidden id adalah... 

    a.
    ```php
    <?php isset($input->id) ? form_hidden('id', $input->id) : '' ?>
    ```

    **b.**
    ```php
    <?= isset($input->id) ? form_hidden('id', $input->id) : '' ?>
    ```

    c.
    ```php
    <?php isset($input->id) ? '' : form_hidden('id', $input->id) ?>
    ```

    d.
    ```php
    <?= isset($input->id) ? '' : form_hidden('id', $input->id) ?>
    ```

88. Souce code untuk membuat unique slug adalah...

    a. 
    ```php
    public function unique_slug()
	{
		$slug		= $this->input->post('slug');
		$id			= $this->input->post('id');
		$category	= $this->category->where('slug', $slug)->get();

		if ($category) {
			if ($id == $category->id) {
				return true;
			}
			$this->load->library('form_validation');
			$this->form_validation->set_message('callback_unique_slug', '%s sudah digunakan!');
			return false;
		}

		return true;
	}
    ```

    b. 
    ```php
    public function unique_slug()
	{
		$slug		= $this->input->post('slug');
		$id			= $this->input->post('id');
		$category	= $this->category->where('slug', $slug)->get();

		if ($category) {
			if ($id != $category->id) {
				return true;
			}
			$this->load->library('form_validation');
			$this->form_validation->set_message('callback_unique_slug', '%s sudah digunakan!');
			return false;
		}

		return true;
	}
    ```

    **c.** 
    ```php
    public function unique_slug()
	{
		$slug		= $this->input->post('slug');
		$id			= $this->input->post('id');
		$category	= $this->category->where('slug', $slug)->first();

		if ($category) {
			if ($id == $category->id) {
				return true;
			}
			$this->load->library('form_validation');
			$this->form_validation->set_message('unique_slug', '%s sudah digunakan!');
			return false;
		}

		return true;
	}
    ```

    d. 
    ```php
    public function unique_slug()
	{
		$slug		= $this->input->post('slug');
		$id			= $this->input->post('id');
		$category	= $this->category->where('slug', $slug)->first();

		if ($category) {
			if ($id != $category->id) {
				return true;
			}
			$this->load->library('form_validation');
			$this->form_validation->set_message('unique_slug', '%s sudah digunakan!');
			return false;
		}

		return true;
	}
    ```

## Membuat Fungsi Ubah Kategori dan Perbaikan Validasi

89. Source code untuk update kategori adalah...

    a.
    ```php
    $this->category->update($data['input']);
    ```

    **b.**
    ```php
    $this->category->where('id', $id)->update($data['input'])
    ```

    c.
    ```php
    $this->category->update($data['content']);
    ```

    d.
    ```php
    $this->category->->where('id', $id)->update($data['content']);
    ```

90. Source code form action category yang benar adalah...

    a. 
    ```php 
    $data['form_action']	= base_url("category/edit");
    ```

    b. 
    ```php 
    $data['form_action']	= base_url("category/edit" + $id);
    ```

    **c.** 
    ```php 
    $data['form_action']	= base_url("category/edit/$id");
    ```

    d. 
    ```php 
    $data['form_action']	= base_url("category/edit" . $id);
    ```

## Membuat Fungsi Hapus Kategori

91. Source code untuk membuat fungsi hapus kategori adalah...

    a. 
    ```php
    public function delete()
	{
        if (!$_POST) {
			redirect(base_url('category'));
		}

		if (! $this->category->where('id', $id)->first()) {
			$this->session->set_flashdata('warning', 'Maaf! Data tidak ditemukan.');
			redirect(base_url('category'));
		}

		if ($this->category->where('id', $id)->delete()) {
			$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan.');
		}

		redirect(base_url('category'));
    }
    ```

    b. 
    ```php
    public function delete()
	{
        if (!$_POST) {
			redirect(base_url('category'));
		}

		if (! $this->category->where('id', $id)->get()) {
			$this->session->set_flashdata('warning', 'Maaf! Data tidak ditemukan.');
			redirect(base_url('category'));
		}

		if ($this->category->where('id', $id)->delete()) {
			$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan.');
		}

		redirect(base_url('category'));
    }
    ```

    c. 
    ```php
    public function delete($id)
	{
        if (!$_POST) {
			redirect(base_url('category'));
		}

		if (! $this->category->where('id', $id)->first()) {
			$this->session->set_flashdata('warning', 'Maaf! Data tidak ditemukan.');
			redirect(base_url('category'));
		}

		if ($this->category->where('id', $id)->delete($id)) {
			$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan.');
		}

		redirect(base_url('category'));
    }
    ```

    **d.** 
    ```php
    public function delete($id)
	{
        if (!$_POST) {
			redirect(base_url('category'));
		}

		if (! $this->category->where('id', $id)->first()) {
			$this->session->set_flashdata('warning', 'Maaf! Data tidak ditemukan.');
			redirect(base_url('category'));
		}

		if ($this->category->where('id', $id)->delete()) {
			$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan.');
		}

		redirect(base_url('category'));
    }
    ```

92. Source code untuk button hapus kategori adalah...

    a.
    ```php
    <?= form_open("category/delete", ['method' => 'POST']) ?>
    <?= form_hidden('id', $row->id) ?>
    <button class="btn btn-sm" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </button>
	<?= form_close() ?>
    ```

    **b.**
    ```php
    <?= form_open("category/delete/$row->id", ['method' => 'POST']) ?>
    <?= form_hidden('id', $row->id) ?>
    <button class="btn btn-sm" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </button>
	<?= form_close() ?>
    ```

    c.
    ```php
    <?= form_open("category/delete" + $row->id, ['method' => 'POST']) ?>
    <?= form_hidden('id', $row->id) ?>
    <button class="btn btn-sm" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </button>
	<?= form_close() ?>
    ```

    d.
    ```php
    <?= form_open("category/delete" . $row->id, ['method' => 'POST']) ?>
    <?= form_hidden('id', $row->id) ?>
    <button class="btn btn-sm" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </button>
	<?= form_close() ?>
    ```

## Membuat Fungsi Pencarian Kategori

93. Source code untuk pencarian kategori adalah...

    a. 
    ```php
    public function search($page = null)
	{
		if (!isset($_POST['keyword'])) {
			$this->session->set_userdata('keyword', $this->input->post('keyword'));
		} else {
			redirect(base_url('category'));
		}

		$keyword	= $this->session->userdata('keyword');
		$data['title']		= 'Admin: Category';
		$data['content']	= $this->category->where('title', $keyword)->paginate($page)->get();
		$data['total_rows']	= $this->category->where('title', $keyword)->count();
		$data['pagination']	= $this->category->makePagination(
			base_url('category/search'), 3, $data['total_rows']
		);
		$data['page']		= 'pages/category/index';
		
		$this->view($data);
	}
    ```

    b. 
    ```php
    public function search($page = null)
	{
		if (isset($_POST['keyword'])) {
			$this->session->set_userdata('keyword', $this->input->post('keyword'));
		} else {
			redirect(base_url('category'));
		}

		$keyword	= $this->session->userdata('keyword');
		$data['title']		= 'Admin: Category';
		$data['content']	= $this->category->where('title', $keyword)->paginate($page)->get();
		$data['total_rows']	= $this->category->where('title', $keyword)->count();
		$data['pagination']	= $this->category->makePagination(
			base_url('category/search'), 3, $data['total_rows']
		);
		$data['page']		= 'pages/category/index';
		
		$this->view($data);
	}
    ```

    c. 
    ```php
    public function search($page = null)
	{
		if (!isset($_POST['keyword'])) {
			$this->session->set_userdata('keyword', $this->input->post('keyword'));
		} else {
			redirect(base_url('category'));
		}

		$keyword	= $this->session->userdata('keyword');
		$data['title']		= 'Admin: Category';
		$data['content']	= $this->category->like('title', $keyword)->paginate($page)->get();
		$data['total_rows']	= $this->category->like('title', $keyword)->count();
		$data['pagination']	= $this->category->makePagination(
			base_url('category/search'), 3, $data['total_rows']
		);
		$data['page']		= 'pages/category/index';
		
		$this->view($data);
	}
    ```

    **d.** 
    ```php
    public function search($page = null)
	{
		if (isset($_POST['keyword'])) {
			$this->session->set_userdata('keyword', $this->input->post('keyword'));
		} else {
			redirect(base_url('category'));
		}

		$keyword	= $this->session->userdata('keyword');
		$data['title']		= 'Admin: Category';
		$data['content']	= $this->category->like('title', $keyword)->paginate($page)->get();
		$data['total_rows']	= $this->category->like('title', $keyword)->count();
		$data['pagination']	= $this->category->makePagination(
			base_url('category/search'), 3, $data['total_rows']
		);
		$data['page']		= 'pages/category/index';
		
		$this->view($data);
	}
    ```

94. Source code untuk membuat reset/hapus session dari keyword yang benar adalah...

    **a.** 
    ```php
    public function reset()
	{
		$this->session->unset_userdata('keyword');
		redirect(base_url('category'));
	}
    ```

    b. 
    ```php
    public function reset($keyword)
	{
		$this->session->unset_userdata('keyword', $keyword);
		redirect(base_url('category'));
	}
    ```

    c. 
    ```php
    public function reset()
	{
		$this->session->sess_destroy('keyword');
		redirect(base_url('category'));
	}
    ```

    d. 
    ```php
    public function reset($keyword)
	{
		$this->session->sess_destroy('keyword', $keyword);
		redirect(base_url('category'));
	}
    ```

95. Source code untuk membuat form/input cari kategori adalah...

    a.
    ```html
    <?= form_open(base_url('category/search'), ['method' => 'POST']) ?>
        <div class="input-group">
            <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari" value="<?= $this->session->set_userdata('keyword') ?>">
            <div class="input-group-append">
                <button class="btn btn-info btn-sm" type="submit">
                    <i class="fas fa-search"></i>
                </button>
                <a href="<?= base_url('category/reset') ?>" class="btn btn-info btn-sm">
                    <i class="fas fa-eraser"></i>
                </a>
            </div>
        </div>
    <?= form_close() ?>
    ```

    **b.**
    ```html
    <?= form_open(base_url('category/search'), ['method' => 'POST']) ?>
        <div class="input-group">
            <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari" value="<?= $this->session->userdata('keyword') ?>">
            <div class="input-group-append">
                <button class="btn btn-info btn-sm" type="submit">
                    <i class="fas fa-search"></i>
                </button>
                <a href="<?= base_url('category/reset') ?>" class="btn btn-info btn-sm">
                    <i class="fas fa-eraser"></i>
                </a>
            </div>
        </div>
    <?= form_close() ?>
    ```

    c.
    ```html
    <?= form_open(base_url('category/search'), ['method' => 'POST']) ?>
        <div class="input-group">
            <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari" value="<?= $this->session('keyword') ?>">
            <div class="input-group-append">
                <button class="btn btn-info btn-sm" type="submit">
                    <i class="fas fa-search"></i>
                </button>
                <a href="<?= base_url('category/reset') ?>" class="btn btn-info btn-sm">
                    <i class="fas fa-eraser"></i>
                </a>
            </div>
        </div>
    <?= form_close() ?>
    ```

    d.
    ```html
    <?= form_open(base_url('category/search'), ['method' => 'POST']) ?>
        <div class="input-group">
            <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari" value="<?= $this->session->unset_userdata('keyword') ?>">
            <div class="input-group-append">
                <button class="btn btn-info btn-sm" type="submit">
                    <i class="fas fa-search"></i>
                </button>
                <a href="<?= base_url('category/reset') ?>" class="btn btn-info btn-sm">
                    <i class="fas fa-eraser"></i>
                </a>
            </div>
        </div>
    <?= form_close() ?>
    ```

# Membuat Modul Admin Produk

## Membuat Tabel dan Model Produk

96. Apa saja isi field/colum dari tabel product

    a. id, id_category, slug, title, description, price

    a. id, id_category, slug, title, description, price, is_available
    
    c. id, id_category, slug, title, description, price, image
    
    **d. id, id_category, slug, title, description, price, is_available, image**

97. Apa saja isi rules untuk attribute/column price...

    a. 'rules' => 'trim|required'

    b. 'rules' => 'trim|required|number'

    **c. 'rules' => 'trim|required|numeric'**

    d. 'rules' => 'trim|number'

## Membuat Controller Produk dan Fungsi Index

98. Source code untuk membuat fungsi index produk adalah...

    a.
    ```php
    public function index($page = null)
	{
		$data['title']		= 'Admin: Produk';
		$data['content']	= $this->product->select(
				[
					'product.id', 'product_title', 'product.image', 
					'product.price', 'product.is_available',
					'category.title'
				]
			)
			->join('category')
			->paginate($page)
			->get();
		$data['total_rows']	= $this->product->count();
		$data['pagination']	= $this->product->makePagination(
			base_url('product'), 2, $data['total_rows']
		);
		$data['page']		= 'pages/product/index';

		$this->view($data);
	}
    ```

    **b.**
    ```php
    public function index($page = null)
	{
		$data['title']		= 'Admin: Produk';
		$data['content']	= $this->product->select(
				[
					'product.id', 'product.title AS product_title', 'product.image', 
					'product.price', 'product.is_available',
					'category.title AS category_title'
				]
			)
			->join('category')
			->paginate($page)
			->get();
		$data['total_rows']	= $this->product->count();
		$data['pagination']	= $this->product->makePagination(
			base_url('product'), 2, $data['total_rows']
		);
		$data['page']		= 'pages/product/index';

		$this->view($data);
	}
    ```

    c.
    ```php
    public function index($page = null)
	{
		$data['title']		= 'Admin: Produk';
		$data['content']	= $this->product->select(
				[
					'product.id', 'product.title AS product_title', 'product.image', 
					'product.price', 'product.is_available',
					'category.title AS category_title'
				]
			)
			->where('category', 'category.id', 'product.id_category')
			->paginate($page)
			->get();
		$data['total_rows']	= $this->product->count();
		$data['pagination']	= $this->product->makePagination(
			base_url('product'), 2, $data['total_rows']
		);
		$data['page']		= 'pages/product/index';

		$this->view($data);
	}
    ```

    d.
    ```php
    public function index($page = null)
	{
		$data['title']		= 'Admin: Produk';
		$data['content']	= $this->product->select(
				[
					'product.id', 'product.title AS product_title', 'product.image', 
					'product.price', 'product.is_available',
					'category.title AS category_title'
				]
			)
            ->where('category', 'category.id', 'product.id_category')
			->paginate($page)
			->get();
		$data['total_rows']	= $this->product->count();
		$data['pagination']	= $this->product->makePagination(
			base_url('product'), 2, $data['total_rows']
		);
		$data['page']		= 'pages/product/index';

		$this->view($data);
	}
    ```

99. Source code product join category dengan type right adalah...

    a.
    ```php
    $this->product->select(
        [
            'product.id', 'product.title AS product_title', 'product.image', 
            'product.price', 'product.is_available',
            'category.title AS category_title'
        ]
	)
	->join('category')
    ```

    **b.**
    ```php
    $this->product->select(
        [
            'product.id', 'product.title AS product_title', 'product.image', 
            'product.price', 'product.is_available',
            'category.title AS category_title'
        ]
	)
	->join('category', 'right')
    ```

    c.
    ```php
    $this->product->select(
        [
            'product.id', 'product.title AS product_title', 'product.image', 
            'product.price', 'product.is_available',
            'category.title AS category_title'
        ]
	)
	->join('right', 'category')
    ```

    d.
    ```php
    $this->product->select(
        [
            'product.id', 'product.title AS product_title', 'product.image', 
            'product.price', 'product.is_available',
            'category.title AS category_title'
        ]
	)
	->join('category', 'type', 'right')
    ```

## Menampilkan Data Produk dengan Pagination

100. Source code untuk menampilkan data product adalah...

    a.
    ```html
    <?php $no = 0; foreach ($content as $row): $no+1; ?>
    <tr>
        <td><?= $no ?></td>
        <td>
            <p>
                <img src="<?= $row->image ?>" alt="" height="50">
                <?= $row->product_title ?>
            </p>
        </td>
        <td>
            <span class="badge badge-primary"><i class="fas fa-tags"></i> <?= $row->category_title ?></span>
        </td>
        <td>Rp<?= number_format($row->price, 0, ',', '.') ?>,-</td>
        <td><?= $row->is_available ?></td>
        <td>
            <a href="#" class="btn btn-sm">
                <i class="fas fa-edit text-info"></i>
            </a>
            <button class="btn btn-sm" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
                <i class="fas fa-trash text-danger"></i>
            </button>
        </td>
    </tr>
    <?php endforeach ?>
    ```

    b.
    ```html
    <?php $no = 1; foreach ($content as $row): $no+1; ?>
    <tr>
        <td><?= $no ?></td>
        <td>
            <p>
                <img src="<?= $row->image ? base_url('images/product/$row->image') : base_url('images/product/default.png') ?>" alt="" height="50">
                <?= $row->product_title ?>
            </p>
        </td>
        <td>
            <span class="badge badge-primary"><i class="fas fa-tags"></i> <?= $row->category_title ?></span>
        </td>
        <td>Rp<?= number_format($row->price, 0, ',', '.') ?>,-</td>
        <td><?= $row->is_available ? 'Tersedia' : 'Kosong' ?></td>
        <td>
            <a href="#" class="btn btn-sm">
                <i class="fas fa-edit text-info"></i>
            </a>
            <button class="btn btn-sm" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
                <i class="fas fa-trash text-danger"></i>
            </button>
        </td>
    </tr>
    <?php endforeach ?>
    ```

    **c.**
    ```html
    <?php $no = 0; foreach ($content as $row): $no++; ?>
    <tr>
        <td><?= $no ?></td>
        <td>
            <p>
                <img src="<?= $row->image ? base_url('images/product/$row->image') : base_url('images/product/default.png') ?>" alt="" height="50">
                <?= $row->product_title ?>
            </p>
        </td>
        <td>
            <span class="badge badge-primary"><i class="fas fa-tags"></i> <?= $row->category_title ?></span>
        </td>
        <td>Rp<?= number_format($row->price, 0, ',', '.') ?>,-</td>
        <td><?= $row->is_available ? 'Tersedia' : 'Kosong' ?></td>
        <td>
            <a href="#" class="btn btn-sm">
                <i class="fas fa-edit text-info"></i>
            </a>
            <button class="btn btn-sm" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
                <i class="fas fa-trash text-danger"></i>
            </button>
        </td>
    </tr>
    <?php endforeach ?>
    ```

    d.
    ```html
    <?php $no = 1; foreach ($content as $row): $no++; ?>
    <tr>
        <td><?= $no ?></td>
        <td>
            <p>
                <img src="<?= $row->image ?>" alt="" height="50">
                <?= $row->product_title ?>
            </p>
        </td>
        <td>
            <span class="badge badge-primary"><i class="fas fa-tags"></i> <?= $row->category_title ?></span>
        </td>
        <td>Rp<?= number_format($row->price, 0, ',', '.') ?>,-</td>
        <td><?= $row->is_available ?></td>
        <td>
            <a href="#" class="btn btn-sm">
                <i class="fas fa-edit text-info"></i>
            </a>
            <button class="btn btn-sm" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
                <i class="fas fa-trash text-danger"></i>
            </button>
        </td>
    </tr>
    <?php endforeach ?>
    ```

101. source code untuk merubah format integer/number price menjadi rupiah adalah

    a. 
    ```php 
    Rp<?= number_format($row->price, 0, '.') ?>,-
    ```

    b. 
    ```php 
    Rp<?= number_format($row->price, 0, ',') ?>,-
    ```

    **c.** 
    ```php 
    Rp<?= number_format($row->price, 0, ',', '.') ?>,-
    ```

    d. 
    ```php 
    Rp<?= number_format($row->price, 0, ',', ',') ?>,-
    ```

## Membuat Fungsi Unggah File dan Tambah Produk

102. Source untuk membuat fungsi upload image produk adalah...
    
    a.
    ```php
    public function uploadImage($fieldName, $fileName)
	{
		$config	= [
			'upload_path'		=> './images/product',
			'file_name'			=> $fileName,
			'allowed_types'		=> 'jpg|gif|png|jpeg|JPG|PNG',
			'max_size'			=> 1024,
			'max_width'			=> 0,
			'max_height'		=> 0,
			'overwrite'			=> true,
			'file_ext_tolower'	=> true
		];

		if ($this->config->do_upload($fieldName)) {
			return $this->upload->data();
		} else {
			$this->session->set_flashdata('image_error', $this->upload->display_errors('', ''));
			return false;
		}
	}
    ```

    b.
    ```php
    public function uploadImage($fieldName, $fileName)
	{
		$config	= [
			'upload_path'		=> './images/product',
			'file_name'			=> $fileName,
			'allowed_types'		=> 'jpg|gif|png|jpeg|JPG|PNG',
			'max_size'			=> 1024,
			'max_width'			=> 0,
			'max_height'		=> 0,
			'overwrite'			=> true,
			'file_ext_tolower'	=> true
		];

		if ($this->config->do_upload($fieldName)) {
			$this->session->set_flashdata('image_error', $this->upload->display_errors('', ''));
			return false;
		} else {
			return $this->upload->data();
		}
	}
    ```

    **c.**
    ```php
    public function uploadImage($fieldName, $fileName)
	{
		$config	= [
			'upload_path'		=> './images/product',
			'file_name'			=> $fileName,
			'allowed_types'		=> 'jpg|gif|png|jpeg|JPG|PNG',
			'max_size'			=> 1024,
			'max_width'			=> 0,
			'max_height'		=> 0,
			'overwrite'			=> true,
			'file_ext_tolower'	=> true
		];

		$this->load->library('upload', $config);

		if ($this->upload->do_upload($fieldName)) {
			return $this->upload->data();
		} else {
			$this->session->set_flashdata('image_error', $this->upload->display_errors('', ''));
			return false;
		}
	}
    ```

    d.
    ```php
    public function uploadImage($fieldName, $fileName)
	{
		$config	= [
			'upload_path'		=> './images/product',
			'file_name'			=> $fileName,
			'allowed_types'		=> 'jpg|gif|png|jpeg|JPG|PNG',
			'max_size'			=> 1024,
			'max_width'			=> 0,
			'max_height'		=> 0,
			'overwrite'			=> true,
			'file_ext_tolower'	=> true
		];

		$this->load->library('upload', $config);

		if ($this->upload->do_upload($fieldName)) {
			$this->session->set_flashdata('image_error', $this->upload->display_errors('', ''));
			return false;
		} else {
			return $this->upload->data();
		}
	}
    ```

103. Source code untuk membuat create data produk adalah...

    **a.**
    ```php
    if (!$_POST) {
			$input	= (object) $this->product->getDefaultValues();
		} else {
			$input	= (object) $this->input->post(null, true);
		}

		if (!empty($_FILES) && $_FILES['image']['name'] !== '') {
			$imageName	= url_title($input->title, '-', true) . '-' . date('YmdHis');
			$upload		= $this->product->uploadImage('image', $imageName);
			if ($upload) {
				$input->image	= $upload['file_name'];
			} else {
				redirect(base_url('product/create'));
			}
		}

		if (!$this->product->validate()) {
			$data['title']			= 'Tambah Produk';
			$data['input']			= $input;
			$data['form_action']	= base_url('product/create');
			$data['page']			= 'pages/product/form';

			$this->view($data);
			return;
		}

		if ($this->product->create($input)) {
			$this->session->set_flashdata('success', 'Data berhasil disimpan!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
		}

		redirect(base_url('product'));
    ```

    b.
    ```php
    if (!$_POST) {
			$input	= (object) $this->product->getDefaultValues();
		} else {
			$input	= (object) $this->input->post(null, true);
		}

		if (empty($_FILES) && $_FILES['image']['name'] == '') {
			$imageName	= url_title($input->title, '-', true) . '-' . date('YmdHis');
			$upload		= $this->product->uploadImage('image', $imageName);
			if ($upload) {
				$input->image	= $upload['file_name'];
			} else {
				redirect(base_url('product/create'));
			}
		}

		if (!$this->product->validate()) {
			$data['title']			= 'Tambah Produk';
			$data['input']			= $input;
			$data['form_action']	= base_url('product/create');
			$data['page']			= 'pages/product/form';

			$this->view($data);
			return;
		}

		if ($this->product->create($input)) {
			$this->session->set_flashdata('success', 'Data berhasil disimpan!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
		}

		redirect(base_url('product'));
    ```

    c.
    ```php
    if (!$_POST) {
			$input	= (object) $this->product->getDefaultValues();
		} else {
			$input	= (object) $this->input->post(null, true);
		}

		if (!empty($_FILES) && $_FILES['image']['name'] == '') {
			$imageName	= url_title($input->title, '-', true) . '-' . date('YmdHis');
			$upload		= $this->product->uploadImage('image', $imageName);
			if ($upload) {
				$input->image	= $upload['file_name'];
			} else {
				redirect(base_url('product/create'));
			}
		}

		if (!$this->product->validate()) {
			$data['title']			= 'Tambah Produk';
			$data['input']			= $input;
			$data['form_action']	= base_url('product/create');
			$data['page']			= 'pages/product/form';

			$this->view($data);
			return;
		}

		if ($this->product->create($input)) {
			$this->session->set_flashdata('success', 'Data berhasil disimpan!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
		}

		redirect(base_url('product'));
    ```

    d.
    ```php
    if (!$_POST) {
			$input	= (object) $this->product->getDefaultValues();
		} else {
			$input	= (object) $this->input->post(null, true);
		}

		if (empty($_FILES) && $_FILES['image']['name'] !== '') {
			$imageName	= url_title($input->title, '-', true) . '-' . date('YmdHis');
			$upload		= $this->product->uploadImage('image', $imageName);
			if ($upload) {
				$input->image	= $upload['file_name'];
			} else {
				redirect(base_url('product/create'));
			}
		}

		if (!$this->product->validate()) {
			$data['title']			= 'Tambah Produk';
			$data['input']			= $input;
			$data['form_action']	= base_url('product/create');
			$data['page']			= 'pages/product/form';

			$this->view($data);
			return;
		}

		if ($this->product->create($input)) {
			$this->session->set_flashdata('success', 'Data berhasil disimpan!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
		}

		redirect(base_url('product'));
    ```

## Membuat Halaman Formulir dan Validasi

104. Source code form helper yang digunakan untuk upload file adalah...

    a.
    ```php
    <?= form_open($form_action, ['method' => 'POST']) ?>
    ```

    b.
    ```php
    <?= form_open_enctype('multipart',$form_action, ['method' => 'POST']) ?>
    ```

    **c.**
    ```php
    <?= form_open_multipart($form_action, ['method' => 'POST']) ?>
    ```

    d.
    ```php
    <?= form_open($form_action, ['method' => 'POST', 'enctype' => 'multipart']) ?>
    ```


105. Type input form untuk deskripsi produk yang benar adalah...

    a. text

    b. number

    c. file

    **d. textarea**

## Membuat Fungsi Hapus File dan Ubah Data

106. Source code untuk menghapus image adalah...

    **a.** 
    ```php
    public function deleteImage($filename)
    {
        if(file_exists("./images/product/$filename")){
            unlink("./images/product/$filename");
        }
    }
    ```

    b. 
    ```php
    public function deleteImage($filename)
    {
        if(!file_exists("./images/product/$filename")){
            unlink("./images/product/$filename");
        }
    }
    ```

    c. 
    ```php
    public function deleteImage($filename)
    {
        if(file_exists("./images/product/$filename")){
            unset("./images/product/$filename");
        }
    }
    ```

    d. 
    ```php
    public function deleteImage($filename)
    {
        if(!file_exists("./images/product/$filename")){
            unset("./images/product/$filename");
        }
    }
    ```

107. Kondisi yang benar saat mengedit produk dengan menginputkan/mengubah file adalah...

    a. 
    ```php
    $data['content'] = $this->product->where('id', $id)->first();

    if ($data['content']->image === '') {
        $this->product->deleteImage($data['content']->image);
    }
    
    $data['input']->image = $upload['file_name'];
    ```

    **b.** 
    ```php
    $data['content'] = $this->product->where('id', $id)->first();

    if ($data['content']->image !== '') {
        $this->product->deleteImage($data['content']->image);
    }
    
    $data['input']->image = $upload['file_name'];
    ```

    c. 
    ```php
    $data['content'] = $this->product->where('id', $id)->first();

    if ($data['content']->image === '') {
        $this->product->deleteImage($data['content']->image);
        $data['input']->image = $upload['file_name'];
    }
    
    ```

    d. 
    ```php
    $data['content'] = $this->product->where('id', $id)->first();

    if ($data['content']->image !== '') {
        $this->product->deleteImage($data['content']->image);
        $data['input']->image = $upload['file_name'];
    }
    
    ```

## Membuat Fungsi Hapus Produk

108. Source code untuk menghapus data produk beserta file gambar nya ialah...

    **a.** 
    ```php
    $product = $this->product->where('id', $id)->first();
    if ($this->product->where('id', $id)->delete()) {
		$this->product->deleteImage($product->image);
		$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
	} else {
		$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan!');
	}
    ```

    b. 
    ```php
    $product = $this->product->where('id', $id)->first();
    if (!$this->product->where('id', $id)->delete()) {
		$this->product->deleteImage($product->image);
		$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
	} else {
		$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan!');
	}
    ```

    c. 
    ```php
    $product = $this->product->where('id', $id)->first();
    if ($product->where('id', $id)->delete()) {
		$this->product->deleteImage($product->image);
		$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
	} else {
		$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan!');
	}
    ```

    d. 
    ```php
    $product = $this->product->where('id', $id)->first();
    if (!$product->where('id', $id)->delete()) {
		$this->product->deleteImage($product->image);
		$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
	} else {
		$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan!');
	}
    ```

109. Source code untuk membuat form hapus produk adalah...

    a. 
    ```html
    <?= form_open(base_url("/product/delete/$row->id"), ['method' => 'POST']) ?>
	<?= form_hidden('id', $row->id) ?>
									
    <a class="btn btn-sm" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </a>
	<?= form_close() ?>
    ```

    b. 
    ```html
    <?= form_open(base_url("/product/delete/$row->id"), ['method' => 'POST']) ?>
	<?= form_hidden('id', $row->id) ?>
									
    <button class="btn btn-sm" type="reset" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </button>
	<?= form_close() ?>
    ```

    c. 
    ```html
    <?= form_open(base_url("/product/delete/$row->id"), ['method' => 'POST']) ?>
	<?= form_hidden('id', $row->id) ?>
									
    <button class="btn btn-sm" type="button" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </button>
	<?= form_close() ?>
    ```

    **d.** 
    ```html
    <?= form_open(base_url("/product/delete/$row->id"), ['method' => 'POST']) ?>
	<?= form_hidden('id', $row->id) ?>
									
    <button class="btn btn-sm" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </button>
	<?= form_close() ?>
    ```

## Membuat Fungsi Pencarian Produk

110. Source code untuk mencari produk berdasarkan title atau deskripsi ialah...

    a.
    ```php
    $data['content'] = $this->product->select(
            [
                'product.id', 'product.title AS product_title', 'product.image', 
                'product.price', 'product.is_available',
                'category.title AS category_title'
            ]
        )
        ->join('category')
        ->like('product.title', $keyword)
        ->like('description', $keyword)
        ->paginate($page)
        ->get();
    ```

    b.
    ```php
    $data['content'] = $this->product->select(
            [
                'product.id', 'product.title AS product_title', 'product.image', 
                'product.price', 'product.is_available',
                'category.title AS category_title'
            ]
        )
        ->join('category')
        ->like('product.title', $keyword)
        ->andLike('description', $keyword)
        ->paginate($page)
        ->get();
    ```

    **c.**
    ```php
    $data['content'] = $this->product->select(
            [
                'product.id', 'product.title AS product_title', 'product.image', 
                'product.price', 'product.is_available',
                'category.title AS category_title'
            ]
        )
        ->join('category')
        ->like('product.title', $keyword)
        ->orLike('description', $keyword)
        ->paginate($page)
        ->get();
    ```

    d.
    ```php
    $data['content'] = $this->product->select(
            [
                'product.id', 'product.title AS product_title', 'product.image', 
                'product.price', 'product.is_available',
                'category.title AS category_title'
            ]
        )
        ->join('category')
        ->like('product.title', 'description', $keyword)
        ->paginate($page)
        ->get();
    ```

111. Source code untuk mendaptkan total baris yang didaptkan dengan pencarian produk ialah

    a.
    ```php
    $data['total_rows']	= $this->product->like('product.title', $keyword)->like('description', $keyword)->count();
    ```

    b.
    ```php
    $data['total_rows']	= $this->product->like('product.title', $keyword)->andLike('description', $keyword)->count();
    ```

    c.
    ```php
    $data['total_rows']	= $this->product->like('product.title', $keyword)->orLike('description', $keyword)->all_rows();
    ```

    **d.**
    ```php
    $data['total_rows']	= $this->product->like('product.title', $keyword)->orLike('description', $keyword)->count();
    ```

# Membuat Modul Admin Pengguna

## Menampilkan Data Pengguna dengan Pagination

112. Source code yang benar untuk membuat pagination pada data pengguna adalah...

    **a.** 
    ```php
    $data['pagination']	= $this->user->makePagination(
		base_url('user'), 2, $data['total_rows']
	);
    ```

    b. 
    ```php
    $data['pagination']	= $this->user->makePagination(
		base_url('user'), 3, $data['total_rows']
	);
    ```

    c. 
    ```php
    $data['pagination']	= $this->user->makePagination(
		base_url('user'), 1, $data['total_rows']
	);
    ```

    d. a dan b benar

113. Source code untuk menampilkan gambar jika dalam user terdapat gambar dan jika tidak maka akan menampilkan gambar avatar adalah...
    
    a.
    ```html
    <img src="<?= $row->image ? base_url("images/user/$row->image") : base_url("images/user/avatar.png") ?>" alt="" height="50">
    ```

    **b.**
    ```html
    <img src="<?= $row->image ? base_url('images/user/$row->image') : base_url('images/user/avatar.png') ?>" alt="" height="50">
    ```

    c.
    ```html
    <img src="<?= $row->image ? base_url('images/user/avatar.png') : base_url('images/user/$row->image') ?>" alt="" height="50">
    ```

    d.
    ```html
    <img src="<?= empty($row->image) ? base_url('images/user/$row->image') : base_url('images/user/avatar.png') ?>" alt="" height="50">
    ```

## Membuat Fungsi Tambah Pengguna

114. Source code yang benar untuk membuat fungsi validasi unique email adalah...

    **a.**
    ```php
    public function unique_email()
    {
        $email		= $this->input->post('email');
		$id			= $this->input->post('id');
		$user		= $this->user->where('email', $email)->first();

		if ($user) {
			if ($id == $user->id) {
				return true;
			}
			$this->load->library('form_validation');
			$this->form_validation->set_message('unique_email', '%s sudah digunakan!');
			return false;
		}

		return true;
    }
    ```

    b.
    ```php
    public function unique_email()
    {
        $email		= $this->input->post('email');
		$id			= $this->input->post('id');
		$user		= $this->user->where('email', $email)->first();

		if ($user) {
			if ($id == $user->id) {
				return false;
			}
			$this->load->library('form_validation');
			$this->form_validation->set_message('unique_email', '%s sudah digunakan!');
			return true;
		}

		return true;
    }
    ```

    c.
    ```php
    public function unique_email()
    {
        $email		= $this->input->post('email');
		$id			= $this->input->post('id');
		$user		= $this->user->where('email', $email)->first();

		if ($user) {
			if ($id == $user->id) {
				return false;
			}
			$this->load->library('form_validation');
			$this->form_validation->set_message('unique_email', '%s sudah digunakan!');
			return false;
		}

		return false;
    }
    ```

    d.
    ```php
    public function unique_email()
    {
        $email		= $this->input->post('email');
		$id			= $this->input->post('id');
		$user		= $this->user->where('email', $email)->first();

		if ($user) {
			if ($id == $user->id) {
				return true;
			}
			$this->load->library('form_validation');
			$this->form_validation->set_message('unique_email', '%s sudah digunakan!');
			return false;
		}

		return false;
    }
    ```

115. Source code untuk membuat validasi password pada saat create data adalah...

    a.
    ```php
    $this->load->library('form_validation');
	$this->form_validation->set_rules('password', 'required|min_length[8]');
    ```

    **b.**
    ```php
    $this->load->library('form_validation');
	$this->form_validation->set_rules('password', 'Password', 'required|min_length[8]');
    ```

    c.
    ```php
    $this->load->library('form_validation');
	$this->form_validation->set_message('password', 'required|min_length[8]');
    ```

    d.
    ```php
    $this->load->library('form_validation');
	$this->form_validation->set_message('password', 'Password', 'required|min_length[8]');
    ```

## Membuat Fungsi Ubah Pengguna

116. Source code ubah password pengguna yang benar adalah...

    a.
    ```php
    $data['input']	= (object) $this->input->post(null, true);
    if (!empty($data['input']->password)) {
        $data['input']->password = hashEncrypt($data['input']->password);
    } else {
        $data['input']->password = $data['content']->password;
    }
    ```

    b.
    ```php
    $data['input']	= (object) $this->input->post(null, true);
    if ($data['input']->password !== '') {
        $data['input']->password = $data['input']->password;
    } else {
        $data['input']->password = $data['content']->password;
    }
    ```

    **c.**
    ```php
    $data['input']	= (object) $this->input->post(null, true);
    if ($data['input']->password !== '') {
        $data['input']->password = hashEncrypt($data['input']->password);
    } else {
        $data['input']->password = $data['content']->password;
    }
    ```

    d.
    ```php
    $data['input']	= (object) $this->input->post(null, true);
    if ($data['input']->password !== '') {
        $data['input']->password = $data['content']->password;
    } else {
        $data['input']->password = hashEncrypt($data['input']->password);
    }
    ```

117. Source code untuk membuat radio button pada status, aktif sesuai dengan data yang ada didatabase adalah...
    
    a.
    ```html
    <div class="form-check form-check-inline">
        <?= form_radio(['name' => 'is_active', 'value' => 1, 'checked' => $input->is_active == 1 ? 0 : 1, 'form-check-input']) ?>
        <label for="" class="form-check-label">Aktif</label>
    </div>
    <div class="form-check form-check-inline">
        <?= form_radio(['name' => 'is_active', 'value' => 0, 'checked' => $input->is_active == 0 ? 0 : 1, 'form-check-input']) ?>
        <label for="" class="form-check-label">Tidak Aktif</label>
    </div>
    ```

    **b.**
    ```html
    <div class="form-check form-check-inline">
        <?= form_radio(['name' => 'is_active', 'value' => 1, 'checked' => $input->is_active == 1 ? true : false, 'form-check-input']) ?>
        <label for="" class="form-check-label">Aktif</label>
    </div>
    <div class="form-check form-check-inline">
        <?= form_radio(['name' => 'is_active', 'value' => 0, 'checked' => $input->is_active == 0 ? true : false, 'form-check-input']) ?>
        <label for="" class="form-check-label">Tidak Aktif</label>
    </div>
    ```

    c.
    ```html
    <div class="form-check form-check-inline">
        <?= form_radio(['name' => 'is_active', 'value' => 1, 'selected' => $input->is_active != 1 ? true : false, 'form-check-input']) ?>
        <label for="" class="form-check-label">Aktif</label>
    </div>
    <div class="form-check form-check-inline">
        <?= form_radio(['name' => 'is_active', 'value' => 0, 'selected' => $input->is_active != 0 ? true : false, 'form-check-input']) ?>
        <label for="" class="form-check-label">Tidak Aktif</label>
    </div>
    ```

    d.
    ```html
    <div class="form-check form-check-inline">
        <?= form_radio(['name' => 'is_active', 'value' => 1, 'selected' => $input->is_active == 1 ? false : true, 'form-check-input']) ?>
        <label for="" class="form-check-label">Aktif</label>
    </div>
    <div class="form-check form-check-inline">
        <?= form_radio(['name' => 'is_active', 'value' => 0, 'selected' => $input->is_active == 0 ? false : true, 'form-check-input']) ?>
        <label for="" class="form-check-label">Tidak Aktif</label>
    </div>
    ```

## Membuat Fungsi Hapus Pengguna

118. Source code untuk membuat fungsi hapus pengguna adalah...

    a.
    ```php
    public function delete($id)
    {
        $user = $this->user->where('id', $id)->first();

		if ($user) {
			$this->session->set_flashdata('warning', 'Maaf, data tidak dapat ditemukan');
			redirect(base_url('user'));
		}

		if (!$this->user->where('id', $id)->delete()) {
			$this->user->deleteImage($user->image);
			$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan!');
		}
    }
    ```

    b.
    ```php
    public function delete($id)
    {
        $user = $this->user->where('id', $id)->first();

		if (!$user) {
			$this->session->set_flashdata('warning', 'Maaf, data tidak dapat ditemukan');
			redirect(base_url('user'));
		}

		if ($this->user->where('id', $id)->delete()) {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan!');
		} else {
			$this->user->deleteImage($user->image);
			$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
		}
    }
    ```

    c.
    ```php
    public function delete($id)
    {
        $user = $this->user->where('id', $id)->first();

		if (!$user) {
			$this->session->set_flashdata('warning', 'Maaf, data tidak dapat ditemukan');
			redirect(base_url('user'));
		}

		if ($this->user->where('id', $id)->delete($id)) {
			$this->user->deleteImage($user->image);
			$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan!');
		}
    }
    ```

    **d.**
    ```php
    public function delete($id)
    {
        $user = $this->user->where('id', $id)->first();

		if (!$user) {
			$this->session->set_flashdata('warning', 'Maaf, data tidak dapat ditemukan');
			redirect(base_url('user'));
		}

		if ($this->user->where('id', $id)->delete()) {
			$this->user->deleteImage($user->image);
			$this->session->set_flashdata('success', 'Data sudah berhasil dihapus!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan!');
		}
    }
    ```

119. Source code untuk membuat form hapus pengguna adalah...

    a. 
    ```html
    <?= form_open(base_url("/user/delete/$row->id"), ['method' => 'POST']) ?>
	<?= form_hidden('id', $row->id) ?>
									
    <a class="btn btn-sm" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </a>
	<?= form_close() ?>
    ```

    b. 
    ```html
    <?= form_open(base_url("/user/delete/$row->id"), ['method' => 'POST']) ?>
	<?= form_hidden('id', $row->id) ?>
									
    <button class="btn btn-sm" type="reset" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </button>
	<?= form_close() ?>
    ```
    
    **c.** 
    ```html
    <?= form_open(base_url("/user/delete/$row->id"), ['method' => 'POST']) ?>
	<?= form_hidden('id', $row->id) ?>
									
    <button class="btn btn-sm" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </button>
	<?= form_close() ?>
    ```

    d. 
    ```html
    <?= form_open(base_url("/user/delete/$row->id"), ['method' => 'POST']) ?>
	<?= form_hidden('id', $row->id) ?>
									
    <button class="btn btn-sm" type="button" onclick="return confirm('Apakah yakin ingin menghapus?')">
        <i class="fas fa-trash text-danger"></i>
    </button>
	<?= form_close() ?>
    ```

# Membuat Validasi Peran Pengguna

## Mengaktifkan Validasi Peran Pengguna dan Perbaikan

120. Source code untuk mengecek apakah user yang login adalah admin jika iya maka diperbolehkan akses jika bukan maka akan diarahkan kehalaman utama...

    a.
    ```php
    public function __construct()
	{
		parent::__construct();
		$role = $this->session->userdata('role');
		if (isset($role == 'admin')) {
			redirect(base_url('/'));
			return;
		}
	}
    ```

    b.
    ```php
    public function __construct()
	{
		parent::__construct();
		$role = $this->session->userdata('role');
		if ($role === 'admin') {
			redirect(base_url('/'));
			return;
		}
	}
    ```

    **c.**
    ```php
    public function __construct()
	{
		parent::__construct();
		$role = $this->session->userdata('role');
		if ($role != 'admin') {
			redirect(base_url('/'));
			return;
		}
	}
    ```

    d.
    ```php
    public function __construct()
	{
		parent::__construct();
		$role = $this->session->userdata('role');
		if ($role != 'member') {
			redirect(base_url('/'));
			return;
		}
	}
    ```

121. Source code untuk menambahkan route user agar menggantikan user/index menjadi sesuai dengan pagination adalah...

    **a. `` $route['user/:num'] = 'user/index/$1'; ``**

    b. `` $route['user/:num'] = 'user/index/$num'; ``

    c. `` $route['user/(:num)'] = 'user/index'; ``

    d. `` $route['user/(:num)'] = 'user/index/$num'; ``

# Membuat Modul Profil Pengguna

## Menampilkan Data Pengguna

122. Source code untuk melakukan pengecekan apakah user sudah login pada fitur profile adalah...

    a.
    ```php
    private $id;
    public function __construct()
    {
        $is_login = $this->session->userdata('is_login');
        $id       = $this->session->userdata('id');

        if($is_login) {
            redirect(base_url());
            return;
        }
    }
    ```

    b.
    ```php
    private $id;
    public function __construct()
    {
        $is_login = $this->session->userdata('is_login');
        $this->id = $this->session->userdata('id');

        if($is_login) {
            redirect(base_url());
            return;
        }
    }
    ```

    c.
    ```php
    private $id;
    public function __construct()
    {
        $is_login = $this->session->userdata('is_login');
        $id = $this->session->userdata('id');

        if(! $is_login) {
            redirect(base_url());
            return;
        }
    }
    ```

    **d.**
    ```php
    private $id;
    public function __construct()
    {
        $is_login = $this->session->userdata('is_login');
        $this->id = $this->session->userdata('id');

        if(! $is_login) {
            redirect(base_url());
            return;
        }
    }
    ```

123. Source code yang benar untuk menampilkan data profile adalah...

    a. ``$data['content'] = $this->profile->where('id', $id)->first();``

    **b. ``$data['content'] = $this->profile->where('id', $this->id)->first();``**

    c. ``$data['content'] = $this->profile->where('id', $id)->get();``

    d. ``$data['content'] = $this->profile->where('id', $this->id)->get();``

## Membuat Fungsi Ubah Data Pengguna

124. Source code untuk ubah data pengguna yang benar adalah...

    a.
    ```php
    public function update($id)
    {
        if ($this->profile->where('id', $this->id)->update($input)) {
            $this->session->set_flashdata('success', 'Data berhasil disimpan!');
        } else {
            $this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
        }    
    }
    ```

    **b.**
    ```php
    public function update($id)
    {
        if ($this->profile->where('id', $id)->update($data['input'])) {
            $this->session->set_flashdata('success', 'Data berhasil disimpan!');
        } else {
            $this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
        }    
    }
    ```

    c.
    ```php
    public function update($id)
    {
        if (!$this->profile->where('id', $id)->update($data['input'])) {
            $this->session->set_flashdata('success', 'Data berhasil disimpan!');
        } else {
            $this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
        }    
    }
    ```

    d.
    ```php
    public function update($id)
    {
        if ($this->profile->where('id', $this->id)->update($input)) {
            $this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
        } else {
            $this->session->set_flashdata('success', 'Data berhasil disimpan!');
        }    
    }
    ```

125. Source code untuk menampilkan form profile pengguna adalah...

    a.
    ```php
    if ($this->profile->validate()) {
        $data['title']			= 'Ubah Data Profile';
        $data['form_action']	= base_url("profile/update" + $id);
        $data['page']			= 'pages/profile/form';

        $this->view($data);
        return;
	}
    ```

    b.
    ```php
    if (!$this->profile->validate()) {
        $data['title']			= 'Ubah Data Profile';
        $data['form_action']	= base_url("profile/update" + $id);
        $data['page']			= 'pages/profile/form';

        $this->view($data);
        return;
	}
    ```

    c.
    ```php
    if ($this->profile->validate()) {
        $data['title']			= 'Ubah Data Profile';
        $data['form_action']	= base_url("profile/update/$id");
        $data['page']			= 'pages/profile/form';

        $this->view($data);
        return;
	}
    ```

    **d.**
    ```php
    if (!$this->profile->validate()) {
        $data['title']			= 'Ubah Data Profile';
        $data['form_action']	= base_url("profile/update/$id");
        $data['page']			= 'pages/profile/form';

        $this->view($data);
        return;
	}
    ```
    

# Membuat Halaman Beranda dan Produk

## Menampilkan Data Produk di Beranda

126. Source code yang benar untuk menampilkan data produk yang tersedia adalah...

    a. 
    ```php
    $data['content']	= $this->home->select(
				[
					'product.id', 'product.title AS product_title', 
					'product.description', 'product.image', 
					'product.price', 'product.is_available',
					'category.title AS category_title', 'category.slug AS category_slug'
				]
			)
			->join('category')
			->where('product.is_available', 0)
			->paginate($page)
			->get();
    ```

    **b.** 
    ```php
    $data['content']	= $this->home->select(
				[
					'product.id', 'product.title AS product_title', 
					'product.description', 'product.image', 
					'product.price', 'product.is_available',
					'category.title AS category_title', 'category.slug AS category_slug'
				]
			)
			->join('category')
			->where('product.is_available', 1)
			->paginate($page)
			->get();
    ```

    c. 
    ```php
    $data['content']	= $this->home->select(
				[
					'product.id', 'product.title AS product_title', 
					'product.description', 'product.image', 
					'product.price', 'product.is_available',
					'category.title AS category_title', 'category.slug AS category_slug'
				]
			)
			->join('category')
			->like('product.is_available', 0)
			->paginate($page)
			->get();
    ```

    d. 
    ```php
    $data['content']	= $this->home->select(
				[
					'product.id', 'product.title AS product_title', 
					'product.description', 'product.image', 
					'product.price', 'product.is_available',
					'category.title AS category_title', 'category.slug AS category_slug'
				]
			)
			->join('category')
			->like('product.is_available', 1)
			->paginate($page)
			->get();
    ```

127. Source code untuk menambahkan route home agar menggantikan user/index menjadi sesuai dengan pagination adalah...

    a. `` $route['home/:num'] = 'home/index/$num'; ``
    
    **b. `` $route['home/:num'] = 'home/index/$1'; ``**

    c. `` $route['home/(:num)'] = 'home/index'; ``

    d. `` $route['home/(:num)'] = 'home/index/$num'; ``

## Menampilkan Produk Berdasarkan Harga

128. Dibawah ini merupakan pengertian tipe pengurutan yang benar adalah...

    a. ascending adalah pengurutan dari yang terkecil ke yang terbesar.

    b. descending adalah pengurutan yang terbesar ke yang terkecil.

    c. ascending adalah pengurutan dari yang terbesar ke yang terkecil.

    **d. a dan b benar**

129. Source code yang benar untuk mengurutkan produk berdasarkan harga adalah...

    a. 
    ```php
    public function sortby($sort, $page = null)
    {
         $data['content']	= $this->home->select(
				[
					'product.id', 'product.title AS product_title', 
					'product.description', 'product.image', 
					'product.price', 'product.is_available',
					'category.title AS category_title', 'category.slug AS category_slug'
				]
			)
			->join('category')
			->where('product.is_available', 1)
            ->where('product.price', $sort)
			->paginate($page)
			->get();
    }
    ```

    b. 
    ```php
    public function sortby($sort, $page = null)
    {
         $data['content']	= $this->home->select(
				[
					'product.id', 'product.title AS product_title', 
					'product.description', 'product.image', 
					'product.price', 'product.is_available',
					'category.title AS category_title', 'category.slug AS category_slug'
				]
			)
			->join('category')
			->where('product.is_available', 1)
            ->like('product.price', $sort)
			->paginate($page)
			->get();
    }
    ```

    **c.** 
    ```php
    public function sortby($sort, $page = null)
    {
         $data['content']	= $this->home->select(
				[
					'product.id', 'product.title AS product_title', 
					'product.description', 'product.image', 
					'product.price', 'product.is_available',
					'category.title AS category_title', 'category.slug AS category_slug'
				]
			)
			->join('category')
			->where('product.is_available', 1)
            ->orderBy('product.price', $sort)
			->paginate($page)
			->get();
    }
    ```

    d. 
    ```php
    public function sortby($sort, $page = null)
    {
         $data['content']	= $this->home->select(
				[
					'product.id', 'product.title AS product_title', 
					'product.description', 'product.image', 
					'product.price', 'product.is_available',
					'category.title AS category_title', 'category.slug AS category_slug'
				]
			)
			->join('category')
			->where('product.is_available', 1)
            ->sortBy('product.price', $sort)
			->paginate($page)
			->get();
    }
    ```

130. Source code untuk menampilkan data produk yang termurah adalah...

    **a.**
    ```html
    <span class="float-right">
        Urutkan Harga: <a href="<?= base_url('/shop/sortby/asc') ?>" class="badge badge-primary">
    </span>
    ```

    b.
    ```html
    <span class="float-right">
        Urutkan Harga: <a href="<?= base_url('/shop/sortby/desc') ?>" class="badge badge-primary">
    </span>
    ```

    c.
    ```html
    <span class="float-right">
        Urutkan Harga: <a href="<?= base_url('/shop/sortby/ascend') ?>" class="badge badge-primary">
    </span>
    ```

    d.
    ```html
    <span class="float-right">
        Urutkan Harga: <a href="<?= base_url('/shop/sortby/descend') ?>" class="badge badge-primary">
    </span>
    ```

131. Source code untuk menampilkan data produk yang termahal adalah...

    a.
    ```html
    <span class="float-right">
        Urutkan Harga: <a href="<?= base_url('/shop/sortby/asc') ?>" class="badge badge-primary">
    </span>
    ```

    **b.**
    ```html
    <span class="float-right">
        Urutkan Harga: <a href="<?= base_url('/shop/sortby/desc') ?>" class="badge badge-primary">
    </span>
    ```

    c.
    ```html
    <span class="float-right">
        Urutkan Harga: <a href="<?= base_url('/shop/sortby/ascend') ?>" class="badge badge-primary">
    </span>
    ```

    d.
    ```html
    <span class="float-right">
        Urutkan Harga: <a href="<?= base_url('/shop/sortby/descend') ?>" class="badge badge-primary">
    </span>
    ```

## Menampilkan Produk Berdasarkan Kategori

132. Source code menampilkan data produk berdasarkan kategori adalah...

    a.
    ```php
    $data['content']	= $this->shop->select(
            [
                'product.id', 'product.title AS product_title', 
                'product.description', 'product.image', 
                'product.price', 'product.is_available',
                'category.title AS category_title', 'category.slug AS category_slug'
            ]
        )
        ->join('category')
        ->where('product.is_available', 1)
        ->orWhere('category.slug', $category)
        ->paginate($page)
        ->get();
    ```

    b.
    ```php
    $data['content']	= $this->shop->select(
            [
                'product.id', 'product.title AS product_title', 
                'product.description', 'product.image', 
                'product.price', 'product.is_available',
                'category.title AS category_title', 'category.slug AS category_slug'
            ]
        )
        ->join('category')
        ->where('product.is_available', 1)
        ->like('category.slug', $category)
        ->paginate($page)
        ->get();
    ```

    **c.**
    ```php
    $data['content']	= $this->shop->select(
            [
                'product.id', 'product.title AS product_title', 
                'product.description', 'product.image', 
                'product.price', 'product.is_available',
                'category.title AS category_title', 'category.slug AS category_slug'
            ]
        )
        ->join('category')
        ->where('product.is_available', 1)
        ->where('category.slug', $category)
        ->paginate($page)
        ->get();
    ```

    d.
    ```php
    $data['content']	= $this->shop->select(
            [
                'product.id', 'product.title AS product_title', 
                'product.description', 'product.image', 
                'product.price', 'product.is_available',
                'category.title AS category_title', 'category.slug AS category_slug'
            ]
        )
        ->join('category')
        ->where('product.is_available', 1)
        ->orLike('category.slug', $category)
        ->paginate($page)
        ->get();
    ```

133. Fungsi yang dapat membuat huruf kapital diawal adalah

    a. str_replace()

    b. ucfirst()

    **c. ucwords()**

    d. strlen()

134. Source code untuk mengubah slug dari kategori dash(-) menjadi spasi adalah...

    a. str_replace('', $category);

    b. str_replace('', '-', $category);

    c. str_replace('-', $category);

    **d. str_replace('-', '', $category);**

## Menampilkan Produk Berdasarkan Pencarian

# Membuat Modul Keranjang Belanja

## Membuat Fungsi Tambah Produk dalam Keranjang

135. Field atau column untuk membuat cart atau keranjang yang benar adalah...

    a. id, id_user, qty, price

    b. id, id_user, qty, subtotal

    c. id, id_user, qty, total

    **d. id, id_user, qty, subtotal, id_product**

136. Source code yang benar untuk menambahkan produk kedalam keranjang adalah...

    **a.** 
    ```php
    $data = [
        'id_user'		=> $this->id,
        'id_product'	=> $input->id_product,
        'qty' 			=> $input->qty,
        'subtotal'		=> $subtotal
    ];

    if ($this->cart->create($data)) {
        $this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
    } else {
        $this->session->set_flashdata('error', 'Oops! Terjadi kesalahan.');
    }
    ```

    b. 
    ```php
    $data = [
        'id_user'		=> $this->id,
        'id_product'	=> $input->id_product,
        'qty' 			=> $input->qty,
        'subtotal'		=> $subtotal
    ];

    if ($this->cart->update($data)) {
        $this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
    } else {
        $this->session->set_flashdata('error', 'Oops! Terjadi kesalahan.');
    }
    ```

    c. 
    ```php
    $data = [
        'id_user'		=> $this->id,
        'id_product'	=> $input->id_product,
        'qty' 			=> $input->qty,
        'subtotal'		=> $subtotal
    ];

    if ($this->cart->delte()) {
        $this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
    } else {
        $this->session->set_flashdata('error', 'Oops! Terjadi kesalahan.');
    }
    ```

    d. 
    ```php
    $data = [
        'id_user'		=> $this->id,
        'qty' 			=> $input->qty,
        'subtotal'		=> $subtotal
    ];

    if ($this->cart->create($data)) {
        $this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
    } else {
        $this->session->set_flashdata('error', 'Oops! Terjadi kesalahan.');
    }
    ```

137. Source code yang benar untuk menambahkan produk kedalam keranjang jika keranjang sudah ada adalah...

    a.
    ```php

    $this->cart->table	= 'product';
    $product			= $this->cart->where('id', $input->id_product)->first();

    $subtotal			= $product->price * $input->qty;

    $this->cart->table	= 'cart';
    $cart = $this->cart->where('id_user', $this->id)->where('id_product', $input->id_product)->first();
					
    if ($cart) {
        $data = [
            'qty' 		=> $cart->qty + $input->qty,
            'subtotal'	=> $cart->subtotal + $subtotal
        ];

        if ($this->cart->update($data)) {
            $this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
        } else {
            $this->session->set_flashdata('error', 'Oops! Terjadi kesalahan.');
        }

        redirect(base_url(''));
    }
    ```

    b.
    ```php
    
    $this->cart->table	= 'product';
    $product			= $this->cart->where('id', $input->id_product)->first();

    $subtotal			= $product->price * $input->qty;

    $this->cart->table	= 'cart';
    $cart = $this->cart->where('id_user', $this->id)->where('id_product', $input->id_product)->first();
					
    if ($cart) {
        $data = [
            'qty' 		=> $cart->qty + $input->qty,
            'subtotal'	=> $cart->subtotal + $subtotal
        ];

        if ($this->cart->where('id', $product->id)->update($data)) {
            $this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
        } else {
            $this->session->set_flashdata('error', 'Oops! Terjadi kesalahan.');
        }

        redirect(base_url(''));
    }
    ```
    
    **c.**
    ```php
    
    $this->cart->table	= 'product';
    $product			= $this->cart->where('id', $input->id_product)->first();

    $subtotal			= $product->price * $input->qty;

    $this->cart->table	= 'cart';
    $cart = $this->cart->where('id_user', $this->id)->where('id_product', $input->id_product)->first();
					
    if ($cart) {
        $data = [
            'qty' 		=> $cart->qty + $input->qty,
            'subtotal'	=> $cart->subtotal + $subtotal
        ];

        if ($this->cart->where('id', $cart->id)->update($data)) {
            $this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
        } else {
            $this->session->set_flashdata('error', 'Oops! Terjadi kesalahan.');
        }

        redirect(base_url(''));
    }
    ```

    d.
    ```php
    
    $this->cart->table	= 'product';
    $product			= $this->cart->where('id', $input->id_product)->first();

    $subtotal			= $product->price * $input->qty;

    $this->cart->table	= 'cart';
    $cart = $this->cart->where('id_user', $this->id)->where('id_product', $input->id_product)->first();
					
    if ($cart) {
        $data = [
            'qty' 		=> $cart->qty + $input->qty,
            'subtotal'	=> $cart->subtotal + $subtotal
        ];

        if ($this->cart->where('id', $cart->id)->create($data)) {
            $this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
        } else {
            $this->session->set_flashdata('error', 'Oops! Terjadi kesalahan.');
        }

        redirect(base_url(''));
    }
    ```
    

## Implementasi Formulir Tambah Produk dalam Keranjang

138. Source code form tambah produk kedalam keranjang yang benar adalah...

    a. 
    ```html
    <form action="<?= base_url('/cart/add') ?>" method="POST">
    <input type="hidden" name="id" value="<?= $row->id ?>"
    ```

    b. 
    ```html
    <form action="<?= base_url('/cart/add') ?>" method="POST">
    <input type="text" name="id_cart" value="<?= $row->id ?>"
    ```

    **c.**
    ```html
    <form action="<?= base_url('/cart/add') ?>" method="POST">
    <input type="hidden" name="id_product" value="<?= $row->id ?>"
    ```

    d. 
    ```html
    <form action="<?= base_url('/cart/add') ?>" method="POST">
    <input type="text" name="id_product" value="<?= $row->id ?>"
    ```

## Menampilkan Produk dalam Keranjang Belanja

139. Source code untuk menampilkan produk dalam keranjang belanja yang benar adalah...

    a.
    ```php
    public function index()
	{
		$data['title']		= 'Keranjang Belanja';
		$data['content']	= $this->cart->select([
				'cart.id', 'cart.qty', 'cart.subtotal',
				'product.title', 'product.image', 'product.price'
			])
			->where('cart.id_user', $this->id)
			->get();
		$data['page']		= 'pages/cart/index';

		return $this->view($data);
	}
    ```

    b.
    ```php
    public function index()
	{
		$data['title']		= 'Keranjang Belanja';
		$data['content']	= $this->cart->select([
				'cart.id', 'cart.qty', 'cart.subtotal',
				'product.title', 'product.image', 'product.price'
			])
			->where('product.id', 'cart.id_product')
			->where('cart.id_user', $this->id)
			->get();
		$data['page']		= 'pages/cart/index';

		return $this->view($data);
	}
    ```

    **c.**
    ```php
    public function index()
	{
		$data['title']		= 'Keranjang Belanja';
		$data['content']	= $this->cart->select([
				'cart.id', 'cart.qty', 'cart.subtotal',
				'product.title', 'product.image', 'product.price'
			])
			->join('product')
			->where('cart.id_user', $this->id)
			->get();
		$data['page']		= 'pages/cart/index';

		return $this->view($data);
	}
    ```

    d.
    ```php
    public function index()
	{
		$data['title']		= 'Keranjang Belanja';
		$data['content']	= $this->cart->select([
				'cart.id', 'cart.qty', 'cart.subtotal',
				'product.title', 'product.image', 'product.price'
			])
			->join('product')
			->where('cart.id_user', $this->id);

		$data['page']		= 'pages/cart/index';

		return $this->view($data);
	}
    ```

140. Source code untuk menghitung total dari subtotal adalah...

    a.
    ```html
    <td class="text-center"><strong>Rp<?= number_format(sum(array_column($content, 'subtotal')), 0, ',', '.') ?>,-</strong></td>
    ```

    b.
    ```html
    <td class="text-center"><strong>Rp<?= number_format(array_count(array_column($content, 'subtotal')), 0, ',', '.') ?>,-</strong></td>
    ```

    c.
    ```html
    <td class="text-center"><strong>Rp<?= number_format(count(array_column($content, 'subtotal')), 0, ',', '.') ?>,-</strong></td>
    ```

    **d.**
    ```html
    <td class="text-center"><strong>Rp<?= number_format(array_sum(array_column($content, 'subtotal')), 0, ',', '.') ?>,-</strong></td>
    ```

## Membuat Fungsi Ubah Produk dalam Keranjang

141. Source code untuk membuat fungsi ubah produk adalah...

    a.
    ```php
    public function update($id)
    {

		$data['input']		= (object) $this->input->post(null, true);
		$this->cart->table	= 'cart';
		$product			= $this->cart->where('id', $data['content']->id_product)->first();
		$subtotal			= $data['input']->qty * $product->price;
		$cart				= [
			'qty'		=> $data['input']->qty,
			'subtotal'	=> $subtotal
		];

		$this->cart->table	= 'product';
		if ($this->cart->where('id', $id)->update($cart)) {
			$this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
		} 
    }
    ```

    b.
    ```php
    public function update($id)
    {

		$data['input']		= (object) $this->input->post(null, true);
		$this->cart->table	= 'product';
		$product			= $this->cart->where('id', $data['content']->id_product)->first();
		$subtotal			= $data['input']->qty * $product->qty;
		$cart				= [
			'qty'		=> $data['input']->qty,
			'subtotal'	=> $subtotal
		];

		$this->cart->table	= 'cart';
		if ($this->cart->where('id', $id)->update($cart)) {
			$this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
		} 
    }
    ```

    **c.**
    ```php
    public function update($id)
    {

		$data['input']		= (object) $this->input->post(null, true);
		$this->cart->table	= 'product';
		$product			= $this->cart->where('id', $data['content']->id_product)->first();
		$subtotal			= $data['input']->qty * $product->price;
		$cart				= [
			'qty'		=> $data['input']->qty,
			'subtotal'	=> $subtotal
		];

		$this->cart->table	= 'cart';
		if ($this->cart->where('id', $id)->update($cart)) {
			$this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
		} 
    }
    ```

    d.
    ```php
    public function update($id)
    {

		$data['input']		= (object) $this->input->post(null, true);
		$this->cart->table	= 'product';
		$product			= $this->cart->where('id', $data['content']->id_product)->first();
		$subtotal			= $data['input']->qty * $product->price;
		$cart				= [
			'qty'		=> $data['input']->qty,
			'subtotal'	=> $subtotal
		];

		$this->cart->table	= 'cart';
		if ($this->cart->where('id', $id)->update($product)) {
			$this->session->set_flashdata('success', 'Produk berhasil ditambahkan!');
		} 
    }
    ```

142. Source code untuk mencegah user agar tidak membeli produk dengan jumlah pembelian kurang dari satu adalah...

    a. 
    ```php
    if ($this->input->post('qty') < 1) {
        $this->session->set_flashdata('error', 'Kuantitas produk tidak boleh kosong!');
        redirect(base_url('cart/index'));
	} 
    ```

    b. 
    ```php
    if ($this->input->post('qty') <= 0) {
        $this->session->set_flashdata('error', 'Kuantitas produk tidak boleh kosong!');
        redirect(base_url('cart/index'));
	} 
    ```

    c.
    ```php
    if ($this->input->post('qty') < 0) {
        $this->session->set_flashdata('error', 'Kuantitas produk tidak boleh kosong!');
        redirect(base_url('cart/index'));
	} 
    ```

    **d.  a dan b benar**

## Implementasi Fungsi Ubah Produk dalam Keranjang

143. Source code form ubah produk kedalam keranjang yang benar adalah...

    a. 
    ```html
    <form action="<?= base_url('/cart/update') ?>" method="POST">
        <input type="hidden" name="id" value="<?= $row->id ?>">
    </form>
    ```

    b. 
    ```html
    <form action="<?= base_url('/cart/update') ?>" method="POST">
        <input type="hidden" name="id_product" value="<?= $row->id ?>">
    </form>

    ```

    **c.** 
    ```php
    <form action="<?= base_url('/cart/update/$row->id') ?>" method="POST">
        <input type="hidden" name="id" value="<?= $row->id ?>">
    </form>
    ```

    d. 
    ```html
    <form action="<?= base_url('/cart/update/$row->id') ?>" method="POST">
        <input type="hidden" name="id_product" value="<?= $row->id ?>">
    </form>
    ```

144. Source code untuk menambahkan input qty di dalam form keranjang yang benar adalah...

    a. ``<input type="number" name="qty" class="form-control text-center" value="$row->qty">``

    **b. ``<input type="number" name="qty" class="form-control text-center" value="<?= $row->qty ?>">``**

    c. ``<input type="text" name="qty" class="form-control text-center" value="$row->qty">``

    d. ``<input type="text" name="qty" class="form-control text-center" value="<?= $row->qty ?>">``
    
## Membuat Fungsi Hapus Produk dalam Keranjang

145. Source code untuk membuat fungsi hapus produk dalam keranjang yang benar adalah...

    a. `` $this->cart->delete($id); ``

    **b. `` $this->cart->where('id', $id)->delete(); ``**

    c. `` $this->cart->where('id_product', $id_product)->delete(); ``

    d. `` $this->cart->delete($id_product); ``

146. Source code untuk membuat form hapus data produk dalam keranjang adalah...

    a. 
    ```html
   <form action="<?= base_url("cart/delete/") ?>" method="POST">
        <input type="hidden" name="id" value="<?= $row->id ?>">
        <button class="btn btn-danger" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
            <i class="fas fa-trash-alt"></i>
        </button>
    </form>
    ```

    **b.** 
    ```html
   <form action="<?= base_url("cart/delete/$row->id") ?>" method="POST">
        <input type="hidden" name="id" value="<?= $row->id ?>">
        <button class="btn btn-danger" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
            <i class="fas fa-trash-alt"></i>
        </button>
    </form>
    ```

    c. 
    ```html
   <form action="<?= base_url("cart/delete" + $row->id) ?>" method="POST">
        <input type="hidden" name="id" value="<?= $row->id ?>">
        <button class="btn btn-danger" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
            <i class="fas fa-trash-alt"></i>
        </button>
    </form>
    ```

    d. 
    ```html
   <form action="<?= base_url("cart/delete" .$row->id) ?>" method="POST">
        <input type="hidden" name="id" value="<?= $row->id ?>">
        <button class="btn btn-danger" type="submit" onclick="return confirm('Apakah yakin ingin menghapus?')">
            <i class="fas fa-trash-alt"></i>
        </button>
    </form>
    ```

# Membuat Modul Checkout

## Membuat Tabel, Model dan Controller Checkout

147. Apa saja field/column yang dibutuhkan untuk membuat table orders?

    **a. id, id_user, date, total, invoice, name, address, phone, status**

    b. id, id_user, id_product, date, total, invoice, name, address, phone, status

    c. id, id_product, date, total, invoice, name, address, phone, status

    d. id, id_cart, date, total, invoice, name, address, phone, status

148. Source code untuk mencegah user ke halaman checkout apabila user belum login...

    a. 
    ```php
    private $id; 
    public function __construct()
    {
        parent::__construct();
        $is_login = $this->session->flashdata('is_login');
        $id = $this->session->flashdata('id');

        if($is_login) {
            redirect(base_url());
            return;
        }
    }
    ```

    b. 
    ```php 
    private $id;
    public function __construct()
    {
        parent::__construct();
        $is_login = $this->session->flashdata('is_login');
        $this->id = $this->session->flashdata('id');
        if(!$is_login) {
            redirect(base_url());
            return;
        }
    }
    ```
    
    **c.** 
    ```php 
    private $id;
    public function __construct()
    {
        parent::__construct();
        $is_login = $this->session->userdata('is_login');
        $this->id = $this->session->flashdata('id');
        if($is_login) {
            redirect(base_url());
            return;
        }
    }
    ```

    d. 
    ```php 
    private $id;
    public function __construct()
    {
        parent::__construct();
        $is_login = $this->session->userdata('is_login');
        $id = $this->session->flashdata('id');
        if(!$is_login) {
            redirect(base_url());
            return;
        }
    }
    ```

## Menampilkan Halaman Checkout dan Data Keranjang

149. Source code untuk menampilkan data keranjang pada halaman checkout adalah...

    a. 
    ```php
    $this->checkout->table = 'cart';

    $data['cart']	= $this->checkout->select([
            'cart.id', 'cart.qty', 'cart.subtotal',
            'product.title', 'product.image', 'product.price'
        ])
        ->join('product')
        ->where('cart.id', $this->id)
        ->get();
    ```

    b. 
    ```php
    $this->checkout->table = 'cart';

    $data['cart']	= $this->checkout->select([
            'cart.id', 'cart.qty', 'cart.subtotal',
            'product.title', 'product.image', 'product.price'
        ])
        ->join('product')
        ->where('cart.user.id', $this->id)
        ->get();
    ```

    c. 
    ```php
    $this->checkout->table = 'cart';

    $data['cart']	= $this->checkout->select([
            'cart.id', 'cart.qty', 'cart.subtotal',
            'product.title', 'product.image', 'product.price'
        ])
        ->join('product')
        ->where('cart.user.id_user', $this->id)
        ->get();
    ```

    **d.**
    ```php
    $this->checkout->table = 'cart';

    $data['cart']	= $this->checkout->select([
            'cart.id', 'cart.qty', 'cart.subtotal',
            'product.title', 'product.image', 'product.price'
        ])
        ->join('product')
        ->where('cart.id_user', $this->id)
        ->get();
    ```

150. Source code untuk validasi jika cart/keranjang kosong adalah...

    a.
    ```php
    if ($data['cart']) {
		$this->session->set_flashdata('warning', 'Tidak ada produk di dalam keranjang.');
		redirect(base_url('/'));
	}
    ```

    a.
    ```php
    if ($data['cart'] !=== null) {
		$this->session->set_flashdata('warning', 'Tidak ada produk di dalam keranjang.');
		redirect(base_url('/'));
	}
    ```

    c.
    ```php
    if (! $data['cart'] !== '') {
		$this->session->set_flashdata('warning', 'Tidak ada produk di dalam keranjang.');
		redirect(base_url('/'));
	}
    ```

    **d.**
    ```php
    if (! $data['cart']) {
		$this->session->set_flashdata('warning', 'Tidak ada produk di dalam keranjang.');
		redirect(base_url('/'));
	}
    ```

## Membuat Fungsi Tambah Order

151. Source code query untuk menjumlahkan subtotal dalam cart yang benar adalah...

    a. 
    ```php
    $this->db->sum('subtotal')
                ->where('id_user', $this->id)
                ->get('cart')
                ->row()
                ->subtotal;
    ```

    **b.**
    ```php
    $this->db->select_sum('subtotal')
                ->where('id_user', $this->id)
                ->get('cart')
                ->row()
                ->subtotal;
    ```

    c. 
    ```php
    $this->db->count('subtotal')
                ->where('id_user', $this->id)
                ->get('cart')
                ->row()
                ->subtotal;
    ```

    d. 
    ```php
    $this->db->select_count('subtotal')
                ->where('id_user', $this->id)
                ->get('cart')
                ->row()
                ->subtotal;
    ```

152. Source code untuk mendapatkan tanggal sekarang adalah...

    a. 'date' => date(y-m-d);

    b. 'date' => date(Y-M-D);

    c. 'date' => date(Y-M-d);

    **d. 'date' => date(Y-m-d);**

## Implementasi Tambah Order dan Menampilkan Halaman Success

153. Source code untuk membuat form checkout adalah...

    **a.**
    ```html
    <form action="<?= base_url("/checkout/create") ?>" method="POST">
        <div class="form-group">
            <label for="">Nama</label>
            <input type="text" class="form-control" name="name" placeholder="Masukkan nama penerima" value="<?= $input->name ?>">
            <?= form_error('name') ?>
        </div>
        <div class="form-group">
            <label for="">Alamat</label>
            <textarea name="address" id="" cols="30" rows="5" class="form-control"><?= $input->address ?></textarea>
            <?= form_error('address') ?>
        </div>
        <div class="form-group">
            <label for="">Telepon</label>
            <input type="text" class="form-control" name="phone" placeholder="Masukkan nomor telepon penerima" value="<?= $input->phone ?>">
            <?= form_error('phone') ?>
        </div>
        <button class="btn btn-primary" type="submit">Simpan</button>
    </form>
    ```

    b.
    ```html
    <form action="<?= base_url("/checkout/create"/$input->id) ?>" method="POST">
        <div class="form-group">
            <label for="">Nama</label>
            <input type="text" class="form-control" name="name" placeholder="Masukkan nama penerima" value="<?= $input->name ?>">
            <?= form_error('name') ?>
        </div>
        <div class="form-group">
            <label for="">Alamat</label>
            <textarea name="address" id="" cols="30" rows="5" class="form-control"><?= $input->address ?></textarea>
            <?= form_error('address') ?>
        </div>
        <div class="form-group">
            <label for="">Telepon</label>
            <input type="text" class="form-control" name="phone" placeholder="Masukkan nomor telepon penerima" value="<?= $input->phone ?>">
            <?= form_error('phone') ?>
        </div>
        <button class="btn btn-primary" type="submit">Simpan</button>
    </form>
    ```

    c.
    ```html
    <form action="<?= base_url("/checkout/create") ?>" method="POST">
        <div class="form-group">
            <label for="">Nama</label>
            <input type="text" class="form-control" name="name" placeholder="Masukkan nama penerima" value="<?= $input->name ?>">
            <?= form_error('name') ?>
        </div>
        <div class="form-group">
            <label for="">Alamat</label>
            <textarea name="address" id="" cols="30" rows="5" class="form-control"><?= $input->address ?></textarea>
            <?= form_error('address') ?>
        </div>
        <div class="form-group">
            <label for="">Telepon</label>
            <input type="text" class="form-control" name="phone" placeholder="Masukkan nomor telepon penerima" value="<?= $input->phone ?>">
            <?= form_error('phone') ?>
        </div>
        <button class="btn btn-primary" type="reset">Simpan</button>
    </form>
    ```

    d.
    ```html
    <form action="<?= base_url("/checkout/create/$input->id") ?>" method="POST">
        <div class="form-group">
            <label for="">Nama</label>
            <input type="text" class="form-control" name="name" placeholder="Masukkan nama penerima" value="<?= $input->name ?>">
            <?= form_error('name') ?>
        </div>
        <div class="form-group">
            <label for="">Alamat</label>
            <textarea name="address" id="" cols="30" rows="5" class="form-control"><?= $input->address ?></textarea>
            <?= form_error('address') ?>
        </div>
        <div class="form-group">
            <label for="">Telepon</label>
            <input type="text" class="form-control" name="phone" placeholder="Masukkan nomor telepon penerima" value="<?= $input->phone ?>">
            <?= form_error('phone') ?>
        </div>
        <button class="btn btn-primary" type="reset">Simpan</button>
    </form>
    ```

154. Source code untuk redirect kehalaman utama adalah...

    a. redirect('');

    b. redirect(base_url(''));

    **c. redirect(base_url('/'));**

    d. redirect(base_url('./'));

# Membuat Modul My Order dan Konfirmasi

## Menampilkan Halaman Order Pengguna

155. Source code untuk menampilkan data order pengguna dengan pengurutan dari yang terbaru sampai yang terlama adalah...

    a.
    ```php
	public function index()
	{
		$data['title']		= 'Daftar Order';
		$data['content']	= $this->myorder->where('id_user', $this->id)->orderBy('ASC', 'date')->get();
		$data['page']		= 'pages/myorder/index';

		$this->view($data);
	}
    ```

    b.
    ```php
	public function index()
	{
		$data['title']		= 'Daftar Order';
		$data['content']	= $this->myorder->where('id_user', $this->id)->orderBy('DESC', 'date')->get();
		$data['page']		= 'pages/myorder/index';

		$this->view($data);
	}
    ```

    c.
    ```php
	public function index()
	{
		$data['title']		= 'Daftar Order';
		$data['content']	= $this->myorder->where('id_user', $this->id)->orderBy('date', 'ASC')->get();
		$data['page']		= 'pages/myorder/index';

		$this->view($data);
	}
    ```

    **d.**
    ```php
	public function index()
	{
		$data['title']		= 'Daftar Order';
		$data['content']	= $this->myorder->where('id_user', $this->id)->orderBy('date', 'DESC')->get();
		$data['page']		= 'pages/myorder/index';

		$this->view($data);
	}
    ```

156. Source code untuk menset Myorder_model dengan tabel orders adalah...

    a. 
    ```php
    <?php

    defined('BASEPATH') OR exit('No direct script access allowed');

    class Myorder_model extends MY_Model 
    {
        private $table = 'orders';
    }
    ```

    b. 
    ```php
    <?php

    defined('BASEPATH') OR exit('No direct script access allowed');

    class Myorder_model extends MY_Model 
    {
        private $this->table = 'orders';
    }
    ```

    **c.** 
    ```php
    <?php

    defined('BASEPATH') OR exit('No direct script access allowed');

    class Myorder_model extends MY_Model 
    {
        protected $table = 'orders';
    }
    ```

    d. 
    ```php
    <?php

    defined('BASEPATH') OR exit('No direct script access allowed');

    class Myorder_model extends MY_Model 
    {
        protected $this->table = 'orders';
    }
    ```

## Menampilkan Data Order pada Halaman My Order

157. Source code untuk membuat menu badge status waiting atau paid adalah...

    **a.**
    ```php
    <?php 
    if ($status == 'waiting') {
        $badge_status	= 'badge-primary';
        $status			= 'Menunggu Pembayaran';
    }

    if ($status == 'paid') {
        $badge_status	= 'badge-secondary';
        $status			= 'Dibayar';
    }

    ?>

    <?php if ($status) : ?>
    <span class="badge badge-pill <?= $badge_status ?>"><?= $status ?></span>
    <?php endif ?>
    ```

    b.
    ```php
    <?php 
    if ($status == 'waiting') {
        $badge_status	= 'badge-primary';
        $status			= 'Menunggu Pembayaran';
    }

    if ($status == 'paid') {
        $badge_status	= 'badge-secondary';
        $status			= 'Dibayar';
    }

    ?>

    <span class="badge badge-pill <?= $badge_status ?>"><?= $status ?></span>
    ```

    c.
    ```php
    <?php 
    if ($status == 'waiting') {
        $badge_status	= 'badge-primary';
        $status			= 'Menunggu Pembayaran';
    }

    if ($status == 'paid') {
        $badge_status	= 'badge-secondary';
        $status			= 'Dibayar';
    }

    ?>

    <?php if (!$status) : ?>
    <span class="badge badge-pill <?= $badge_status ?>"><?= $status ?></span>
    <?php endif ?>
    ```

    d.
    ```php
    <?php 
    if ($status != 'waiting') {
        $badge_status	= 'badge-primary';
        $status			= 'Menunggu Pembayaran';
    }

    if ($status != 'paid') {
        $badge_status	= 'badge-secondary';
        $status			= 'Dibayar';
    }

    ?>

    <?php if ($status) : ?>
    <span class="badge badge-pill <?= $badge_status ?>"><?= $status ?></span>
    <?php endif ?>
    ```

158. Source code untuk mengubah format tanggal dari Ymd menjadi dmY adalah...

    a. ``<?= str_replace('-', '/', date('d-m-Y', $row-date)) ?>``

    **b. ``<?= str_replace('-', '/', date('d-m-Y', strtotime($row-date))) ?>``**

    c. ``<?= str_replace('/', '-', date('d-m-Y', $row-date)) ?>``

    d. ``<?= str_replace('/', '-', date('d-m-Y', strtotime($row-date))) ?>``

## Menampilkan Data Detail Order

159. Source code untuk menampilkan detail order adalah...

    a.
    ```php
    public function detail($invoice)
	{
		$data['order']	= $this->myorder->where('invoice', $invoice)->first();
		
		$this->myorder->table	= 'orders_detail';
		$data['order_detail']	= $this->myorder->select([
				'orders_detail.id_orders', 'orders_detail.id_product', 'orders_detail.qty',
				'orders_detail.subtotal', 'product.title', 'product.image', 'product.price'
			])
			->join('product')
			->where('orders_detail.id_orders', $data['order']->id)
			->get();
	}
    ```

160. Source code untuk redirect kehalama detail order yang benar adalah...

    **a. <a href="<?= base_url('/myorder/detail/$row->invoice') ?>">**

    b. <a href="<?= redirect(base_url('/myorder/detail/$row->invoice')) ?>">

    c. <a href="<?= base_url('./myorder/detail/$row->invoice') ?>">

    d. <a href="<?= base_url('/myorder/detail') ?>">

## Membuat Tabel dan Model Konfirmasi Order

161. Apa saja isi field/column dari table orders_confirm?

    **a. id, id_orders, account_name, account_number, nominal, note, image**

    b. id, id_orders_detail, account_name, account_number, nominal, , note

    c. id, id_user, account_name, account_number, nominal, note

    d. id, id_oders, id_user, account_name, account_number, nominal, note

162. Source code untuk membuat validasi maximal 50 character adalah...

    a. 'rules' => 'max[50]'
    
    **b. 'rules' => 'max_length[50]'**

    c. 'rules' => 'min[50]'
    
    d. 'rules' => 'min_length[50]'

## Membuat Fungsi Konfirmasi

163. Source code untuk membuat fungsi konfirmasi order adalah...

    a.
    ```php
    public function confirm($invoice)
	{
		if ($this->myorder->create($data['input'])) {
			$this->myorder->where('id', $data['input']->id_orders)->update('status' = 'paid');
			$this->session->set_flashdata('success', 'Data berhasil disimpan!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
		}

		redirect(base_url("myorder/detail/$invoice"));
    }
    ```

    **b.**
    ```php
    public function confirm($invoice)
	{
        $this->myorder->table = 'orders_confirm';

		if ($this->myorder->create($data['input'])) {
			$this->myorder->table = 'orders';
			$this->myorder->where('id', $data['input']->id_orders)->update(['status' => 'paid']);
			$this->session->set_flashdata('success', 'Data berhasil disimpan!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
		}

		redirect(base_url("myorder/detail/$invoice"));
    }
    ```

    c.
    ```php
    public function confirm($invoice)
	{
        
        $this->myorder->table = 'orders_confirm';

		if ($this->myorder->create($data['input'])) {
			$this->myorder->where('id_orders', $data['input']->id_orders)->update['status' => 'paid');
			$this->session->set_flashdata('success', 'Data berhasil disimpan!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
		}

		redirect(base_url("myorder/detail/$invoice"));
    }
    ```

    d.
    ```php
    public function confirm($invoice)
	{
        
        $this->myorder->table = 'orders_confirm';

		if ($this->myorder->create($data['input'])) {
			$this->myorder->table = 'orders';
			$this->myorder->where('id_orders', $data['input']->id_orders)->update(['status' = 'paid']);
			$this->session->set_flashdata('success', 'Data berhasil disimpan!');
		} else {
			$this->session->set_flashdata('error', 'Oops! Terjadi suatu kesalahan');
		}

		redirect(base_url("myorder/detail/$invoice"));
    }
    ```

164. Source code untuk melakukan pengecekan jika data order bukan lah berstatus waiting maka dikembalikan dihalaman detail order...

    a.
    ```php
    $data['order']	= $this->myorder->where('invoice', $invoice)->first();
    
    if ($data['order'] !== 'waiting') {
        $this->session->set_flashdata('warning', 'Bukti transfer sudah dikiirm.');
        redirect(base_url("myorder/detail/$invoice"));
    }
    ```

    **b.**
    ```php
    $data['order']	= $this->myorder->where('invoice', $invoice)->first();
    
    if ($data['order']->status !== 'waiting') {
        $this->session->set_flashdata('warning', 'Bukti transfer sudah dikiirm.');
        redirect(base_url("myorder/detail/$invoice"));
    }
    ```

    c.
    ```php
    $data['order']	= $this->myorder->where('invoice', $invoice)->first();
    
    if ($data['order'] === 'waiting') {
        $this->session->set_flashdata('warning', 'Bukti transfer sudah dikiirm.');
        redirect(base_url("myorder/detail/$invoice"));
    }
    ```

    d.
    ```php
    $data['order']	= $this->myorder->where('invoice', $invoice)->first();
    
    if ($data['order']->status === 'waiting') {
        $this->session->set_flashdata('warning', 'Bukti transfer sudah dikiirm.');
        redirect(base_url("myorder/detail/$invoice"));
    }
    ```

## Membuat Halaman Formulir Konfirmasi

165. Source code untuk membuat validasi image_required yang benar adalah...

    a.
    ```php
    public function image_required()
	{
		if (empty($_FILES) || $_FILES['image']['name'] !== '') {
			$this->session->set_flashdata('image_error', 'Bukti transfer tidak boleh kosong!');
			return false;
		}
		return true;
	}
    ```

    b.
    ```php
    public function image_required()
	{
		if (!empty($_FILES) && $_FILES['image']['name'] !== '') {
			$this->session->set_flashdata('image_error', 'Bukti transfer tidak boleh kosong!');
			return false;
		}
		return true;
	}
    ```

    c.
    ```php
    public function image_required()
	{
		if (!empty($_FILES) || $_FILES['image']['name'] === '') {
			$this->session->set_flashdata('image_error', 'Bukti transfer tidak boleh kosong!');
			return false;
		}
		return true;
	}
    ```

    **d.**
    ```php
    public function image_required()
	{
		if (empty($_FILES) || $_FILES['image']['name'] === '') {
			$this->session->set_flashdata('image_error', 'Bukti transfer tidak boleh kosong!');
			return false;
		}
		return true;
	}
    ```

166. Source code untuk membuat form error image adalah...

    a.
    ```html
    <div class="form-group">
        <label for="">Bukti Transfer</label> <br>
        <input type="file" name="image" id="">
        <?php if ($this->session->flashdata('image_error')) { ?>
            <small class="form-text text-danger"><?php $this->session->flashdata('image_error') ?></small>
        <?php endif ?>
    </div>
    ```

    b.
    ```html
    <div class="form-group">
        <label for="">Bukti Transfer</label> <br>
        <input type="file" name="image" id="">
        <?php if ($this->session->flashdata('image_error')) : ?>
            <small class="form-text text-danger"><?php $this->session->flashdata('image_error') ?></small>
        <?php endif ?>
    </div>
    ```

    **c.**
    ```html
    <div class="form-group">
        <label for="">Bukti Transfer</label> <br>
        <input type="file" name="image" id="">
        <?php if ($this->session->flashdata('image_error')) : ?>
            <small class="form-text text-danger"><?= $this->session->flashdata('image_error') ?></small>
        <?php endif ?>
    </div>
    ```

    d.
    ```html
    <div class="form-group">
        <label for="">Bukti Transfer</label> <br>
        <input type="file" name="image" id="">
        <?php if ($this->session->flashdata('image_error')) { ?>
            <small class="form-text text-danger"><?= $this->session->flashdata('image_error') ?></small>
        <?php endif ?>
    </div>
    ```

## Menampilkan Data Konfirmasi Order

167. Source code untuk validasi jika detail order tidak berstatus waiting maka menampilkan data order confirm adalah...

    a. 
    ```php
    public function detail($invoice)
	{
		$data['order']	= $this->myorder->where('invoice', $invoice)->first();
        if ($data['order']->status !== 'waiting') {
            $data['order_confirm']	= $this->myorder->where('id_orders', $data['order']->id)->first();
        }
    }
    ```

    b. 
    ```php
    public function detail($invoice)
	{
		$data['order']	= $this->myorder->where('invoice', $invoice)->first();
        if ($data['order']->status !== 'waiting') {
            $this->myorder->table = 'orders_detail';
            $data['order_confirm']	= $this->myorder->where('id_orders', $data['order']->id)->first();
        }
    }
    ```

    **c.** 
    ```php
    public function detail($invoice)
	{
		$data['order']	= $this->myorder->where('invoice', $invoice)->first();
        if ($data['order']->status !== 'waiting') {
            $this->myorder->table = 'orders_confirm';
            $data['order_confirm']	= $this->myorder->where('id_orders', $data['order']->id)->first();
        }
    }
    ```

    d. 
    ```php
    public function detail($invoice)
	{
		$data['order']	= $this->myorder->where('invoice', $invoice)->first();
        if ($data['order']->status !== 'waiting') {
            $this->myorder->table = 'orders';
            $data['order_confirm']	= $this->myorder->where('id_orders', $data['order']->id)->first();
        }
    }
    ```

168. Source code untuk mengecek jika order berstatus waiting maka menampilkan tombol konfirmasi pembayaran adalah...

    **a.**
    ```html
    <?php if ($order->status == 'waiting') : ?>
        <div class="card-footer">
            <a href="<?= base_url("/myorder/confirm/$order->invoice") ?>" class="btn btn-success">Konfirmasi Pembayaran</a>
        </div>
    <?php endif ?>
    ```

    b.
    ```html
    <?php if ($order->status == 'waiting') { ?>
        <div class="card-footer">
            <a href="<?= base_url("/myorder/confirm/$order->invoice") ?>" class="btn btn-success">Konfirmasi Pembayaran</a>
        </div>
    <?php endif ?>
    ```

    c.
    ```html
    <?php if ($order['status'] == 'waiting') : ?>
        <div class="card-footer">
            <a href="<?= base_url("/myorder/confirm/$order->invoice") ?>" class="btn btn-success">Konfirmasi Pembayaran</a>
        </div>
    <?php endif ?>
    ```

    d.
    ```html
    <?php if ($order->status !== 'waiting') : ?>
        <div class="card-footer">
            <a href="<?= base_url("/myorder/confirm/$order->invoice") ?>" class="btn btn-success">Konfirmasi Pembayaran</a>
        </div>
    <?php endif ?>
    ```

# Membuat Modul Admin Order

## Menampilkan Data Order

## Menampilkan Data Detail Order

169. Source code untuk menampilkan data detail order adalah...

    a.
    ```php
    public function detail($id)
	{
		$data['order']			= $this->order->where('id', $id)->first();
		
		$this->order->table	= 'orders_detail';
		$data['order_detail']	= $this->order->select([
				'orders_detail.id_orders', 'orders_detail.id_product', 'orders_detail.qty',
				'orders_detail.subtotal', 'product.title', 'product.image', 'product.price'
			])
			->join('product')
			->where('orders_detail.id', $id)
			->get();
	}
    
    ```

    b.
    ```php
    public function detail($id)
	{
		$data['order']			= $this->order->where('id', $id)->first();
		
		$data['order_detail']	= $this->order->select([
				'orders_detail.id_orders', 'orders_detail.id_product', 'orders_detail.qty',
				'orders_detail.subtotal', 'product.title', 'product.image', 'product.price'
			])
			->join('product')
			->where('orders.id_orders', $id)
			->get();
	}
    ```

    **c.**
    ```php
    public function detail($id)
	{
		$data['order']			= $this->order->where('id', $id)->first();
		
		$this->order->table	= 'orders_detail';
		$data['order_detail']	= $this->order->select([
				'orders_detail.id_orders', 'orders_detail.id_product', 'orders_detail.qty',
				'orders_detail.subtotal', 'product.title', 'product.image', 'product.price'
			])
			->join('product')
			->where('orders_detail.id_orders', $id)
			->get();
	}
    ```

    d.
    ```php
    public function detail($id)
	{
		$data['order']			= $this->order->where('id', $id)->first();
	
		$data['order_detail']	= $this->order->select([
				'orders_detail.id_orders', 'orders_detail.id_product', 'orders_detail.qty',
				'orders_detail.subtotal', 'product.title', 'product.image', 'product.price'
			])
			->join('product')
			->where('orders_detail.id_orders', $id)
			->get();
	}

170. Source code untuk mengecek data order confirm ada atau kosong adalah...

    a. <?php if(isset($order_confirm)) : ?>

    b. <?php if(!empty($order_confirm)) : ?>

    c. <?php if(empty($order_confirm)) : ?>

    **d. a dan b benar**

## Membuat Fungsi Update Status Order

171. Source code untuk ubah status order adalah...

    a. ``$this->order->where('id', $id)->update('status' = $this->input->post('status'));``

    **b. ``$this->order->where('id', $id)->update(['status' => $this->input->post('status')]);``**

    c. ``$this->order->where('id', $id)->update(['status' = $this->input->post('status')]);``

    d. ``$this->order->where('id', $id)->update('status' => $this->input->post('status'));``

172. Source code yang benar untuk membuat form update status order adalah

    a.
    ```html
    <form action="<?= base_url("order/update/$order->id") ?>" method="POST">
        <input type="hidden" name="id" value="<?= $order->id ?>">
        <div class="input-group">
            <select name="status" id="" class="form-control">
                <option value="waiting" <?= $order->status == waiting ? 'selected' : '' ?> >Menunggu Pembayaran</option>
                <option value="paid" <?= $order->status == paid ? 'selected' : '' ?>>Dibayar</option>
                <option value="delivered" <?= $order->status == delivered ? 'selected' : '' ?>>Dikirim</option>
                <option value="cancel" <?= $order->status == cancel ? 'selected' : '' ?>>Batal</option>
            </select>
            <div class="input-group-append">
                <button class="btn btn-primary" type="submit">Simpan</button>
            </div>
        </div>
    </form>
    ```

    b.
    ```html
    <form action="<?= base_url("order/update/$order->id_order") ?>" method="POST">
        <input type="hidden" name="id" value="<?= $order->id ?>">
        <div class="input-group">
            <select name="status" id="" class="form-control">
                <option value="waiting" <?= $order->status == 'waiting' ? 'selected' : '' ?> >Menunggu Pembayaran</option>
                <option value="paid" <?= $order->status == 'paid' ? 'selected' : '' ?>>Dibayar</option>
                <option value="delivered" <?= $order->status == 'delivered' ? 'selected' : '' ?>>Dikirim</option>
                <option value="cancel" <?= $order->status == 'cancel' ? 'selected' : '' ?>>Batal</option>
            </select>
            <div class="input-group-append">
                <button class="btn btn-primary" type="submit">Simpan</button>
            </div>
        </div>
    </form>
    ```

    **c.**
    ```html
    <form action="<?= base_url("order/update/$order->id") ?>" method="POST">
        <input type="hidden" name="id" value="<?= $order->id ?>">
        <div class="input-group">
            <select name="status" id="" class="form-control">
                <option value="waiting" <?= $order->status == 'waiting' ? 'selected' : '' ?> >Menunggu Pembayaran</option>
                <option value="paid" <?= $order->status == 'paid' ? 'selected' : '' ?>>Dibayar</option>
                <option value="delivered" <?= $order->status == 'delivered' ? 'selected' : '' ?>>Dikirim</option>
                <option value="cancel" <?= $order->status == 'cancel' ? 'selected' : '' ?>>Batal</option>
            </select>
            <div class="input-group-append">
                <button class="btn btn-primary" type="submit">Simpan</button>
            </div>
        </div>
    </form>
    ```


    d.
    ```html
    <form action="<?= base_url("order/update/$order->id_order") ?>" method="POST">
        <input type="hidden" name="id" value="<?= $order->id ?>">
        <div class="input-group">
            <select name="status" id="" class="form-control">
                <option value="waiting" <?= $order->status == waiting ? 'selected' : '' ?> >Menunggu Pembayaran</option>
                <option value="paid" <?= $order->status == paid ? 'selected' : '' ?>>Dibayar</option>
                <option value="delivered" <?= $order->status == delivered ? 'selected' : '' ?>>Dikirim</option>
                <option value="cancel" <?= $order->status == cancel ? 'selected' : '' ?>>Batal</option>
            </select>
            <div class="input-group-append">
                <button class="btn btn-primary" type="submit">Simpan</button>
            </div>
        </div>
    </form>
    ```

## Membuat Fungsi Pencarian Data Order

173. Source code untuk membuat fungsi pencarian data order adalah...

    a.
    ```php
    public function search()
	{
		$keyword	        = $this->session->userdata('keyword');
		$data['title']		= 'Admin: Order';
		$data['content']	= $this->order->like('invoice', $keyword)
								->orderBy('date', 'DESC')
								->paginate($page)->get();
		$data['total_rows']	= $this->order->like('invoice', $keyword)->count();
		$data['pagination']	= $this->order->makePagination(
			base_url('order/search'), 3, $data['total_rows']
		);
		$data['page']		= 'pages/order/index';
		
		$this->view($data);
	}
    ```

    b.
    ```php
    public function search()
	{
		$keyword	        = $this->session->userdata('keyword');
		$data['title']		= 'Admin: Order';
		$data['content']	= $this->order->orLike('invoice', $keyword)
								->orderBy('date', 'DESC')
								->paginate($page)->get();
		$data['total_rows']	= $this->order->orLike('invoice', $keyword)->count();
		$data['pagination']	= $this->order->makePagination(
			base_url('order/search'), 3, $data['total_rows']
		);
		$data['page']		= 'pages/order/index';
		
		$this->view($data);
	}
    ```

    **c.**
    ```php
    public function search($page = null)
	{
		$keyword	        = $this->session->userdata('keyword');
		$data['title']		= 'Admin: Order';
		$data['content']	= $this->order->like('invoice', $keyword)
								->orderBy('date', 'DESC')
								->paginate($page)->get();
		$data['total_rows']	= $this->order->like('invoice', $keyword)->count();
		$data['pagination']	= $this->order->makePagination(
			base_url('order/search'), 3, $data['total_rows']
		);
		$data['page']		= 'pages/order/index';
		
		$this->view($data);
	}
    ```

    d.
    ```php
    public function search($page = null)
	{
		$keyword	        = $this->session->flashdata('keyword');
		$data['title']		= 'Admin: Order';
		$data['content']	= $this->order->like('invoice', $keyword)
								->orderBy('date', 'DESC')
								->paginate($page)->get();
		$data['total_rows']	= $this->order->like('invoice', $keyword)->count();
		$data['pagination']	= $this->order->makePagination(
			base_url('order/search'), 3, $data['total_rows']
		);
		$data['page']		= 'pages/order/index';
		
		$this->view($data);
	}
    ```

174. Source code untuk membuat form pencarian order adalah...

    **a.**
    ```html
    <?= form_open(base_url('order/search'), ['method' => 'POST']) ?>
        <div class="input-group">
            <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari" value="<?= $this->session->userdata('keyword') ?>">
            <div class="input-group-append">
                <button class="btn btn-info btn-sm" type="submit">
                    <i class="fas fa-search"></i>
                </button>
                <a href="<?= base_url('order/reset') ?>" class="btn btn-info btn-sm">
                    <i class="fas fa-eraser"></i>
                </a>
            </div>
        </div>
    <?= form_close() ?>
    ```

    b.
    ```html
    <?= form_open(base_url('order/search'), ['method' => 'POST']) ?>
        <div class="input-group">
            <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari" value="<?= $this->session->set_data('keyword') ?>">
            <div class="input-group-append">
                <button class="btn btn-info btn-sm" type="submit">
                    <i class="fas fa-search"></i>
                </button>
                <a href="<?= base_url('order/reset') ?>" class="btn btn-info btn-sm">
                    <i class="fas fa-eraser"></i>
                </a>
            </div>
        </div>
    <?= form_close() ?>
    ```

    c.
    ```html
    <?= form_open(base_url('order/search'), ['method' => 'POST']) ?>
        <div class="input-group">
            <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari" value="<?= $this->session->flashdata('keyword') ?>">
            <div class="input-group-append">
                <button class="btn btn-info btn-sm" type="submit">
                    <i class="fas fa-search"></i>
                </button>
                <a href="<?= base_url('order/reset') ?>" class="btn btn-info btn-sm">
                    <i class="fas fa-eraser"></i>
                </a>
            </div>
        </div>
    <?= form_close() ?>
    ```

    d.
    ```html
    <?= form_open(base_url('order/search'), ['method' => 'POST']) ?>
        <div class="input-group">
            <input type="text" name="keyword" class="form-control form-control-sm text-center" placeholder="Cari" value="<?= $this->session->keyword ?>">
            <div class="input-group-append">
                <button class="btn btn-info btn-sm" type="submit">
                    <i class="fas fa-search"></i>
                </button>
                <a href="<?= base_url('order/reset') ?>" class="btn btn-info btn-sm">
                    <i class="fas fa-eraser"></i>
                </a>
            </div>
        </div>
    <?= form_close() ?>
    ```