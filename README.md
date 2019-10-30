# bima_html_js
## Basic of HTML and JavaScript

### Project Pertama
Code Javascript pertama kamu
Sebagai contoh kita akan mencoba menampilkan sebuah kalimat berupa Teks "Hello World!' menggunakan Javascript yang ada di dalam syntax HTML

Berikut kode program tersebut
```
<html>
   <body>   
      <script language = "javascript" type = "text/javascript">
         <!--
            document.write("Hello World!")
         //-->
      </script>      
   </body>
</html>
```

Kode Program di atas akan menampilkan!
```
Hello World!
```

### Variable 
Variable adalah sebuah alokasi memori yang tersimpan di komputer yang mana nilainya bisa berubah-ubah sesuai dengan spesifikasi tertentu
contoh pembuatan variable dalam javascript adalah

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <script>
        var nama = 'Bima Laksana Putra';
        var umur = 17;
        var status = true;
        var pi = 3.14;

        document.writeln(nama);
        document.writeln(umur);
        document.writeln(status);
        document.writeln(pi);
    </script>
</body>
</html>
```

Kode program diatas akan menampilkan!
```
Bima Laksana Putra 17 true 3.14
```
#### Tugas!!!
Buatlah beberapa variable dari data studi kasus tentang Aplikasi Bank

### Kondisi (if, else if, else)
Kondisi di dalam pemrograman sangat berperan penting dalam proses logika untuk menyelesaikan permasalahan,
if       -> digunakan untuk pernyataan atau statement kondisi jika benar dan terpenuhi
else if  -> digunakan untuk pernyataan atau statement yang lain dalam kondisi jika benar dan terpenuhi
else     -> digunakan jika nilai yang di ambil tidak memenuhi persyaratan selain if dan else if

Contoh Kasus
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <script>
        var grade = 74;
        if (grade >= 90) {
            document.write("Nilai A");
        }else if (grade >= 80) {
            document.write("Nilai B");            
        }else if(grade >= 75){
            document.write("Nilai C");

        }else{
            document.write("Nilai D");

        }

        var username = "budi"
        var password = "admin";
        if (password == "admin" && username == "user") {
            document.write(" Welcome");            
        }else{
            document.write(" Forbidden");
        }
    </script>
</body>
</html>
```

maka kode priogram di atas akan menampilkan
```
Nilai D Forbidden
```
#### Tugas!!!
1. Buatlah sebuah kondisi yang berada di lingkungan sekitar dengan memanfaatkan logika if, else if, dan else
2. Cari tau menerapkan kondisi menggunaka switch case

### Simple Perulangan For
Buatlah kode program di bawah ini
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <script>
        var first = 0;
        var limit = 100;

        for (var index = first; index < limit; index++) {
            console.log(index);
        }
    </script>
</body>
</html>
```

Sekarang kita akan mencpba mempelajari log pada console javascript kita
untuk melihat hasil tersebut adalah dengan melakukan klik kanan pada halaman browser, kemudian pilih Inspect dan pilih Tab Console

arti dari syntax console.log adalah untuk menampilkan output kita ke console javascript pada browser

jika kode program di atas dijalankan maka akan tampil angka 1 s/d 100

#### Tugas!!!
1. silahkan mencari tau dan menerapkan perulangan pada while dan do while
2. Tampilkan bilangan genap dari 1 s/d 100
3. Tampilkan bilangan ganjil dari 100 s/d 1


