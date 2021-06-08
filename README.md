

# PRAKTIKUM PEMROGRAMAN WEB

## Praktikum Pertemuan 11

Praktikum dilakukan dengan modul praktikum yang sudah disediakan.

- File praktikum terdapat pada folder **lab9_php_modular**.
- File tugas terdapat pada folder **lab9_php_modular** didalam folder **lab8_php_database**.

## 1. Praktikum Modularisasi

### CSS

Sebelumnya terdapat file css tambahan untuk mengubah tampilan awal dari praktikum yang diberikan.

![enter image description here](https://github.com/antonmartinus72/Lab9Web/raw/main/Screenshot/6_css.jpg)

### HEADER

![enter image description here](https://github.com/antonmartinus72/Lab9Web/raw/main/Screenshot/1_code.jpg)

*Tampilan header setelah diterapkan kode css :

![enter image description here](https://github.com/antonmartinus72/Lab9Web/raw/main/Screenshot/1.jpg)

### FOOTER

![enter image description here](https://github.com/antonmartinus72/Lab9Web/raw/main/Screenshot/2_code.jpg)

*Tampilan footer setelah diterapkan kode css :

![enter image description here](https://github.com/antonmartinus72/Lab9Web/raw/main/Screenshot/2.jpg)

### HOME

Pada kode dibawah ini, file header.php dan footer.php diatas dipanggil kembali.

![enter image description here](https://github.com/antonmartinus72/Lab9Web/raw/main/Screenshot/3_code.jpg)

Halaman home.php akan terlihat seperti dibawah ini.

![enter image description here](https://github.com/antonmartinus72/Lab9Web/raw/main/Screenshot/3.jpg)

### ABOUT

Sama seperti home.php, file ini (about.php) juga memanggil file header.php dan footer.php.

![enter image description here](https://github.com/antonmartinus72/Lab9Web/raw/main/Screenshot/4_code.jpg)

Output :

![enter image description here](https://github.com/antonmartinus72/Lab9Web/raw/main/Screenshot/4.jpg)

## 2. Tugas

**Soal** : Implementasikan konsep modularisasi pada kode program praktikum 8 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.

<hr>

Untuk melakukan modularisasi dengan file ini (index.php), saya hanya perlu menambahkan `require('../header.php')` pada awal kode dan `require('../footer.php')` pada akhir kode. Dimana pada kasus saya, file-file tersebut disimpan pada parent direktori.

![enter image description here](https://github.com/antonmartinus72/Lab9Web/raw/main/Screenshot/5_code.jpg)

Output :

![enter image description here](https://github.com/antonmartinus72/Lab9Web/raw/main/Screenshot/5.jpg)

## Sekian & Terimakasih.