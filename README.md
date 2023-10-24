Nama : Rafif Isdarufa Athallah

NIM : 312210299

Kelas : TI.22.A3

---

## Pratikum

### Membuat Dokumen HTML

- Buat dokumen HTML seperti berikut:
- `document.write()` adalah metode yang digunakan untuk menuliskan teks ke dalam jendela browser. Metode ini dapat digunakan untuk menampilkan teks, gambar, atau kode HTML.
- `console.log()` adalah metode yang digunakan untuk menampilkan pesan ke dalam konsol browser. Metode ini dapat digunakan untuk menampilkan informasi debugging atau untuk menampilkan pesan kesalahan.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>

    <script language="javascript">
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```

![Intro](./images/JS%20Intro.jpeg)

---

### Pemakaian Alert

- `alert()` dapat digunakan untuk menampilkan informasi, peringatan, atau pesan kesalahan. Metode ini akan menampilkan pesan dalam sebuah kotak dialog dan menunggu pengguna untuk mengklik tombol "OK".

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alert Box</title>
</head>
<body>
    <h1>JavaScript Alert</h1>

    <script language="javascript">
        window.alert("Ini merupakan pesan untuk anda")
    </script>
</body>
</html>
```

![Alert](./images/JS%20Alert.jpeg)

---

### Pemakaian Method

- *Method* adalah sebuah fungsi yang didefinisikan di dalam sebuah objek. *Method* dapat digunakan untuk mengakses atau mengubah properti dari objek tersebut. *Method* dapat dipanggil dengan menggunakan tanda titik (.)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Method</title>
</head>
<body>
    <h1>Percobaan memakai script:</h1>

    <script language="javascript">
        document.write("Selamat mencoba JavaScript<br>");
        document.write("Semoga sukses!");
    </script>
</body>
</html>
```

![Method](./images/JS%20Method.jpeg)

---

### Pemakaian Prompt

- `prompt()` adalah metode yang digunakan untuk menampilkan kotak dialog yang meminta pengguna untuk memasukkan teks. Metode ini akan mengembalikan nilai yang dimasukkan pengguna.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pemasukan Data</title>
</head>
<body>
    <h1>Pemakaian Prompt</h1>

    <script language="javascript">
        var nama = prompt("Siapa nama anda? Masukkan nama anda:");
        document.write("Hai, " + nama);
    </script>
</body>
</html>
```

![Prompt 1](./images/JS%20Prompt.jpeg)
![Prompt 2](./images/JS%20Prompt%20(2).jpeg)

---

### Pembuatan Fungsi

- `function()` adalah sebuah blok kode yang dapat digunakan untuk melakukan tugas tertentu. Fungsi ini dapat menerima argumen sebagai input, melakukan operasi tertentu, dan mengembalikan nilai jika diperlukan.
- Fungsi dapat didefinisikan dengan menggunakan kata kunci *"function"*, diikuti dengan nama fungsi dan tanda kurung yang berisi argumen (opsional).

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program JavaScript</title>

    <script language="javascript">
        function pesan() {
            alert("Memanggil JavaScript lewat body onload");
        }
    </script>
</head>
<body onload="pesan()"></body>
</html>
```

![Function](./images/JS%20Function.jpeg)

---
### Operasi Aritmatika

- *JavaScript* mendukung operasi aritmatika dasar seperti penjumlahan (+), pengurangan (-), perkalian (*), pembagian (/), dan modulus (%).

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program JavaScript</title>

    <script language="javascript">
        function test(val1, val2) {
            document.write("<br>" + "Perkalian: val1*val2 " + "<br>");
            document.write(val1*val2, "<br>");
            document.write("<br>" + "Pembagian: val1/val2 " + "<br>");
            document.write(val1/val2, "<br>");
            document.write("<br>" + "Penjumlahan: val1+val2 " + "<br>");
            document.write(val1+val2, "<br>");
            document.write("<br>" + "Pengurangan: val1-val2 " + "<br>");
            document.write(val1-val2, "<br>");
            document.write("<br>" + "Modulus: val1%val2 " + "<br>");
            document.write(val1%val2, "<br>");
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="Arithmetic" onclick=test(9,4)>
</body>
</html>
```

![Aritmatika 1](./images/JS%20Aritmatika%20(1).jpeg)
![Aritmatika 2](./images/JS%20Aritmatika%20(2).jpeg)

---

### Kondisi If-Else

- `if()` dan `else()` adalah struktur kontrol yang digunakan untuk menentukan apakah suatu kondisi terpenuhi atau tidak. Jika kondisi terpenuhi, maka blok kode yang didefinisikan setelah kata kunci *"if"* akan dijalankan. Jika kondisi tidak terpenuhi, maka blok kode yang didefinisikan setelah kata kunci *"else"* akan dijalankan.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh If-Else</title>
</head>
<body>
    <script language="javascript">
        var nilai = prompt("Nilai (0-100): ", 0);
        var hasil = "";

        if (nilai >= 60) {
            hasil = "Lulus";
        } else {
            hasil = "Tidak lulus";
        }

        document.write("Hasil: " + hasil);
    </script>
</body>
</html>
```

![If-Else 1](./images/JS%20If-Else%20(1).jpeg)
![If-Else 2](./images/JS%20If-Else%20(2).jpeg)

---

### Operator Switch

- Operator `switch()` digunakan untuk melakukan pemilihan kondisi. Operator `switch()` akan memeriksa nilai dari sebuah variabel dan menjalankan blok kode yang sesuai dengan nilai tersebut.
- Operator `switch()` dapat digunakan untuk melakukan pemilihan kondisi yang lebih kompleks dibandingkan dengan `if()` dan `else()`. Operator `switch()` juga dapat digunakan untuk melakukan pengecekan terhadap beberapa nilai sekaligus.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Switch</title>

    <script language="javascript">
        function test() {
            val1 = window.prompt("Input nilai 1-5: ");
            switch (val1) {
                case "1":
                    document.write("Bilangan satu");
                    break
                case "2":
                    document.write("Bilangan dua");
                    break
                case "3":
                    document.write("Bilangan tiga");
                    break
                case "4":
                    document.write("Bilangan empat");
                    break
                case "5":
                    document.write("Bilangan lima");
                    break
                default:
                    document.write("Bilangan lainnya");
            }
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="Switch" onclick="test()">
</body>
</html>
```

![Switch 1](./images/JS%20Switch%20(1).jpeg)
![Switch 2](./images/JS%20Switch%20(2).jpeg)

---

### Form Input

- Form tersebut memiliki dua input, yaitu input untuk memasukkan bilangan dan input untuk menampilkan hasil. Ketika tombol "TEBAK" ditekan, maka fungsi `test()` akan dijalankan. Fungsi `test()` akan memeriksa apakah bilangan yang dimasukkan adalah bilangan genap atau bilangan ganjil. Jika bilangan tersebut adalah bilangan genap, maka nilai dari input "T2" akan berubah menjadi "Bilangan genap". Jika bilangan tersebut adalah bilangan ganjil, maka nilai dari input "T2" akan berubah menjadi "Bilangan ganjil".

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Form</title>

    <script language="javascript">
        function test() {
            var val1 = document.kirim.T1.value;

            if (val1 % 2 == 0) {
                document.kirim.T2.value = "Bilangan genap";
            } else {
                document.kirim.T2.value = "Bilangan ganjil";
            }
        }
    </script>
</head>
<body>
    <form method="post" name="kirim">
        <p>Bil <input type="text" name="T1" size="20"> Merupakan Bil <input type="text" name="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick="test()"></p>
    </form>
</body>
</html>
```

![Form Input](./images/JS%20Form%20Input.jpeg)

---

### Form Button

- Fungsi `ubahWarnaLB()` digunakan untuk mengubah warna latar belakang dokumen, sedangkan fungsi `ubahWarnaLD()` digunakan untuk mengubah warna teks dokumen. Kedua fungsi tersebut menggunakan properti **bgColor** dan **fgColor** untuk mengubah warna dokumen.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Objek Dokumen</title>
</head>
<body>
    <script language="javascript">
        function ubahWarnaLB(warna) {
            document.bgColor = warna;
        }
        
        function ubahWarnaLD(warna) {
            document.fgColor = warna;
        }
    </script>

    <h1>Tes</h1>
    <form method="post" name="kirim">
        <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('Green')">
        <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('White')">
        <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('Yellow')">
        <input type="button" value="Teks Biru" onclick="ubahWarnaLD('Blue')">
    </form>

    <script language="javascript">
        document.write("Dimodifikasi terakhir pada " + document.lastModified)
    </script>
</body>
</html>
```

![Form Button 1](./images/JS%20Form%20Button%20(1).jpeg)
![Form Button 2](./images/JS%20Form%20Button%20(2).jpeg)

---

### HTML DOM

- HTML DOM adalah singkatan dari **Document Object Model**. HTML DOM adalah model objek yang mewakili struktur dokumen HTML. HTML DOM memungkinkan *JavaScript* untuk mengakses dan memanipulasi dokumen HTML.
- HTML DOM terdiri dari elemen-elemen yang mewakili struktur dokumen HTML. Elemen-elemen ini dapat diakses dan dimanipulasi menggunakan *JavaScript*.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=7">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daftar Menu</title>

    <script language="javascript">
        function hitung(ele) {
            var total = document.getElementById("total").value;
            total = (total ? parseInt(total) : 0);
            var harga = 0;

            if (ele.checked) {
                harga = ele.value;
                total += parseInt(harga);
            } else {
                harga = ele.value;
                if (total > 0) {
                    total -= parseInt(harga);
                }
            }

            document.getElementById("total").value = total;
        }
    </script>
</head>
<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);">Ayam Goreng Rp 5.000</label><br>
    <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);">Tempe Goreng Rp 500</label><br>
    <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);">Telur Dadar Rp 2.500</label><br>
    <strong>Total bayar: Rp. <input type="text" id="total"></strong>
</body>
</html>
```

![HTML DOM](./images/JS%20HTML%20DOM.jpeg)

---

### Pertanyaan dan Tugas

#### Buat script untuk melakukan validasi pada isian form.

![Tugas](./images/Tugas%20(1).jpeg)
![Tugas](./images/Tugas%20(2).jpeg)

---

### Sekian, terimakasih.