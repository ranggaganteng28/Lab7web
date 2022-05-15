# Praktikum 7

## Profil
| | Biodata |
| -------- | --- |
| **Nama** | Rangga Saputra |
| **NIM** | 312010266 |
| **Kelas** | TI.20.A2 |
| **Mata Kuliah** | Pemrograman Web |

## 1. Install XAMPP

Download XAMPP pada situs resminya, lalu ekstrak file dan simpan directory yang diinginkan
Disini saya menyimpan pada OS(C:)

![Directory](img/xampp.JPG)

## 2. Install XAMPP

Tekan tombol **start** pada action **apache** seperti gambar dibawah.
![web server](img/runxampp.png)

## 3 Memulai PHP
Buat folder `lab7_php_dasar` pada (C:\xampp\htdocs) seperti gambar dibawah.
![folder](img/run_PHP.png)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: 
http://localhost/lab7web/lab7_php_dasar/

![Localhost](img/localhost.png)

## 4. PHP dasar

Buat file baru dengan nama **php_dasar.php** pada directory tersebut. Kemudian buat kode seperti berikut.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PHP Dasar</title>
</head>
<body>
    <h1>Belajar PHP Dasar</h1>
    <?php
        echo "Hello World";
    ?>
</body>
</html>
```
Kemudian untuk hasilnya seperti berikut.

![phpdasar](img/dasar.png)