# Penjelasan singkat program
Program ini merupakan solver untuk permainan IQ Puzzler yang menggunakan algoritma brute force dengan backtracking. Program membaca konfigurasi papan dan balok dari file, kemudian mencoba menyusun balok hingga menemukan solusi atau menyatakan bahwa tidak ada solusi.

# Requirement program
Untuk menjalankan program dibutuhkan requirement sebagai berikut
* Java Development Kit (JDK) 8 atau lebih baru.
* Editor atau IDE seperti VS Code, IntelliJ IDEA, atau Eclipse.

Jika belum memiliki JDK, silakan unduh dan instal dari [Oracle JDK atau]([https://](https://www.oracle.com/java/technologies/downloads/#java11?er=221886)) 

Pastikan Java telah terinstal dengan menjalankan perintah berikut di terminal atau command prompt:
```
java -version
```
Jika terinstal dengan benar, akan muncul informasi versi Java.

# Cara Mengompilasi Program
Karena program ditulis dalam bahasa Java, perlu dikompilasi terlebih dahulu sebelum dijalankan.
Gunakan perintah berikut:
```
javac IQPuzzler.java
```
Perintah ini akan menghasilkan file ReadFile.class yang siap dieksekusi.

# Cara Menjalankan dan Menggunakan Program
1. Siapkan file input (misalnya test3.txt) dengan format:
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
3. Jika solusi ditemukan, program akan:
* Menampilkan hasil dengan warna di terminal.
* Menunjukkan jumlah kasus yang ditinjau.
* Menampilkan waktu eksekusi.
* Menawarkan opsi untuk menyimpan solusi ke dalam file.
4. Jika ingin menyimpan solusi, ketik ```ya``` saat ditanya. Jika tidak ingin menyimpan solusi, ketik ```tidak``` saat ditanya. Solusi akan disimpan di **solution.txt**.

# Author
* Nama: Muhamamd Zakkiy
* Email: muhammadzakkiy6@gmail.com
