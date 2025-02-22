# Penjelasan singkat program
Program ini merupakan solver untuk permainan IQ Puzzler yang menggunakan algoritma brute force dengan backtracking. Program membaca konfigurasi papan dan balok dari file, kemudian mencoba menyusun balok hingga menemukan solusi atau menyatakan bahwa tidak ada solusi.

# Requirement program
Untuk menjalankan program dibutuhkan requirement sebagai berikut. 
  * Java Development Kit (JDK) 8 atau lebih baru.
  * Editor atau IDE seperti VS Code, IntelliJ IDEA, atau Eclipse.

Jika belum memiliki JDK, silahkan unduh dan instal dari [Oracle JDK](https://www.oracle.com/java/technologies/downloads/#java11?er=221886)

Pastikan Java telah terinstal dengan menjalankan perintah berikut di terminal atau command prompt:
```
java -version
```
Jika terinstal dengan benar, maka akan muncul informasi mengenai versi Java.

# Cara Mengompilasi Program
Karena program ditulis dalam bahasa Java, program perlu dikompilasi terlebih dahulu sebelum dijalankan.
Gunakan perintah berikut:
```
javac IQPuzzler.java
```
Perintah ini akan menghasilkan file ```IQPuzzler.class``` yang siap dieksekusi.

# Cara Menjalankan dan Menggunakan Program
1. program akan memberikan pengguna sebuah prompt untuk menuliskan path file test case
berekstensi ```.txt```, kemudian program membaca file test case tersebut yang berisi
    * Dimensi Papan yang terdiri atas dua buah variabel **N** dan **M** yang membentuk papan berdimensi **NxM**.
    * Banyak blok puzzle direpresentasikan oleh variabel integer **P**.
    * Jenis kasus sebuah variabel string **S** yang digunakan untuk mengidentifikasi kasus konfigurasi, Pada program ini kasus konfigurasi hanya mungkin bernilai **DEFAULT**.
    * Bentuk blok puzzle yang dilambangkan oleh konfigurasi Character berupa huruf. Akan ada **P** buah blok puzzle berbeda yang dibentuk oleh **P** buah huruf berbeda.   Character yang digunakan adalah huruf A-Z dalam kapital.

    File ```.txt``` yang akan dibaca memiliki format sebagai berikut.

```
  N M P
  S
  puzzle_1_shape
  puzzle_2_shape
  …
  puzzle_P_shape
```
2. Jalankan program dengan perintah berikut:
```
java IQPuzzler
```
3. Program akan meminta masukan berupa nama file. tulis nama file nya saja. Misalkan jika nama filenya ```test1.txt```, tulis ```test1.txt```.
4. Jika solusi ditemukan, program akan:
    * Menampilkan hasil dengan warna di terminal.
    * Menunjukkan jumlah kasus yang ditinjau.
    * Menampilkan waktu eksekusi.
    * Menawarkan opsi untuk menyimpan solusi ke dalam file.
4. Jika ingin menyimpan solusi, ketik ```ya``` saat ditanya. Jika tidak ingin menyimpan solusi, ketik ```tidak``` saat ditanya. Solusi akan disimpan di **solution.txt**.

# Author
* Nama: Muhammad Zakkiy
* Email: muhammadzakkiy6@gmail.com
