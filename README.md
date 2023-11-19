# Lab7Web

# Pertama-tama buat PHP DASAR

Buat file baru dengan nama php_dasar.php pada directory tersebut. Kemudian buat
kode seperti berikut.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
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
`Untuk hhasilnya akan seperti ini`

![tampilan awal](https://github.com/MikaelRivaldo/Lab7Web/assets/115770247/58a640e8-8567-4a1a-86cb-0461294e3eb9)

# Selanjutnya membuat Variable PHP
Untuk codenya bisa menggunakan di bawah ini:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>

<body>
    <h1>Belajar PHP Dasar</h1>
    <?php
    echo "Hello World";
    ?>
    <h2>Menggunakan Variable</h2>
    <?php
    $nim = "312210378";
    $nama = 'Mikael Rivaldo';
    echo "NIM : " . $nim . "<br>";
    echo "Nama : $nama";
    ?>
</body>

</html>
```

`Untuk hasilnya akan seperti ini`

![1](https://github.com/MikaelRivaldo/Lab7Web/assets/115770247/73697aef-7ecf-4ab5-a161-47fec782eddf)

# Selanjutnya membuat  Form Input
untuk codenya bisa menggunakan dibawah ini:

```html
Membuat Form Input
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>

<body>
    <h2>Form Input</h2>
    <form method="post">
        <label>Nama: </label>
        <input type="text" name="nama">
        <input type="submit" value="Kirim">
    </form>
    <?php
    echo 'Selamat Datang ' . $_POST['nama'];
    ?>
</body>

</html>
```

`Untuk hasilnya akan seperti ini`

![tampilan form](https://github.com/MikaelRivaldo/Lab7Web/assets/115770247/cc1fb51f-b010-4806-b74b-3221d4e1db38)

# TUGAS

![Tugas](https://github.com/MikaelRivaldo/Lab7Web/assets/115770247/5a6b4da2-fe70-4f00-b033-5637b6896352)



