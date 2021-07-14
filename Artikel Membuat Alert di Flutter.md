# Membuat Alert di Flutter

Halo, teman-teman pada artikel kali ini kita akan membahas bagaimana cara untuk membuat alert di flutter Pertama-tama siapkan Text Editor atau IDE teman-teman disini saya menggunakan Text Editor Visual Studio Code dan buat project baru flutter dan beri nama project dengan alert.

Setelah selesai membuat project arahkan ke direktori lib kemudian buka file main.dart kemudian masukkan source code berikut:

```
import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        appBar: AppBar(title: Text("Tutorial Membuat Alert")),
        body: LoginPage(),
      ),
    );
  }
}
```

Kemudian pada baris selanjutnya kita akan membuat class baru dengan nama LoginPage untuk membuat user interface halaman login

```
class LoginPage extends StatefulWidget {
  @override
  _LoginPageState createState() => _LoginPageState();
}

class _LoginPageState extends State<LoginPage> {
  TextEditingController _emailController = TextEditingController();
  TextEditingController _passwordController = TextEditingController();

  @override
  Widget build(BuildContext context) {
    return Center(
      child: Padding(
        padding: const EdgeInsets.all(20),
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            TextFormField(
              controller: _emailController,
              maxLines: 1,
              keyboardType: TextInputType.emailAddress,
              decoration: InputDecoration(
                labelText: "Email",
                hintText: "Masukkan Email",
                prefixIcon: Icon(Icons.mail),
                border: OutlineInputBorder(
                  borderRadius: BorderRadius.circular(8.0),
                ),
              ),
            ),
            SizedBox(height: 20),
            TextFormField(
              controller: _passwordController,
              maxLines: 1,
              keyboardType: TextInputType.visiblePassword,
              decoration: InputDecoration(
                labelText: "Password",
                hintText: "Masukkan Password",
                prefixIcon: Icon(Icons.lock),
                border: OutlineInputBorder(
                  borderRadius: BorderRadius.circular(8.0),
                ),
              ),
            ),
            SizedBox(height: 25),
            ElevatedButton(
              onPressed: () => submit(
                context,
                _emailController.text,
                _passwordController.text,
              ), */
              child: Text("Login"),
            )
          ],
        ),
      ),
    );
  }
```

kemudian kita buat method baru dengan nama submit bertipe data void

```
void submit(BuildContext context, String email, String password) {
    if (email.isEmpty || password.isEmpty) {
      final snackBar = SnackBar(
        duration: const Duration(seconds: 5),
        content: Text("Email dan password harus diisi"),
        backgroundColor: Colors.red,
      );

      ScaffoldMessenger.of(context).showSnackBar(snackBar);
      return;
    }

    AlertDialog alert = AlertDialog(
      title: Text("Login Berhasil"),
      content: Container(
        child: Text("Selamat Anda Berhasil login"),
      ),
      actions: [
        TextButton(
          child: Text('Ok'),
          onPressed: () => Navigator.of(context).pop(),
        ),
      ],
    );

    showDialog(context: context, builder: (context) => alert);
    return;
  }
}
```

Di dalam isi method tersebut di dalam if terdapat Snackbar sedangkan di luar if terdapat AlertDialog nah biasa nya untuk membuat alert/pesan bisa menggunakan SnackBar maupun Alert. Setelah itu kita coba run dan hasilnya akan menjadi seperti ini untuk yang Snackbar
![Screenshot_20210714_132151](https://user-images.githubusercontent.com/32627090/125595859-e5b93a78-2421-4314-b93f-8a6c94740a3f.jpg)

Dan untuk yang AlertDialog hasilnya akan menjadi seperti ini
![Screenshot_20210714_141007](https://user-images.githubusercontent.com/32627090/125595900-b659a127-8870-496f-811c-87d9aa70914a.jpg)

Lalu selanjutnya kita akan membuat alert seperti SweatAlert dengan cara menambahkan plugin rflutter_alert, cara menambahkan nya cari file bernama pubspec.yaml 

```
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.2
  rflutter_alert: ^2.0.2
```

Cari dependecies dan masukan rflutter_alert beserta versi nya sejajar dengan plugin cupertino_icons
kemudian kita save setelah itu kita import rflutter di main.dart dengan cara masukkan setelah plugin material seperti ini

```
import 'package:flutter/material.dart';
import 'package:rflutter_alert/rflutter_alert.dart';

Jika terjadi error saat memasukan pluh rflutter_alert teman-teman bisa buka terminal lalu ketikkan perintan flutter pub get. Setelah itu kita buat method baru bernama sweatAlert bertipe data void method ini dimasukan setelah method submit

void sweatAlert(BuildContext context) {
  Alert(
    context: context,
    type: AlertType.success,
    title: "Login berhasil",
    desc: "Selamat anda berhasil login",
    buttons: [
      DialogButton(
        child: Text(
          "Selanjutnya",
          style: TextStyle(color: Colors.white, fontSize: 14),
        ),
        onPressed: () => Navigator.pop(context),
      )
    ],
  ).show();
  return;
}
```

Kemudian kita ganti method pada button dari submit menjadi sweatAlert

```
ElevatedButton(
	onPressed: () => sweatAlert(context),
    child: Text("Login"),
 )
```

Setelah itu kita run dan hasil nya akan menjadi seperti ini
![Screenshot_20210714_141321](https://user-images.githubusercontent.com/32627090/125595928-9227289d-03a1-4c39-b650-47d31b145e98.jpg)

Selamat mencoba
