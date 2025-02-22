# Penjelasan singkat program
Program ini merupakan solver untuk permainan IQ Puzzler yang menggunakan algoritma brute force dengan backtracking. 
Program membaca konfigurasi papan dan balok dari file, kemudian mencoba menyusun balok hingga menemukan solusi atau menyatakan bahwa tidak ada solusi.

# Requirement program
-Java Development Kit (JDK) 8 atau lebih baru.
-Editor atau IDE seperti VS Code, IntelliJ IDEA, atau Eclipse.

# Cara Mengompilasi Program
Karena program ditulis dalam bahasa Java, perlu dikompilasi terlebih dahulu sebelum dijalankan.
Gunakan perintah berikut:
javac ReadFile.java
Perintah ini akan menghasilkan file ReadFile.class yang siap dieksekusi.

# Cara Menjalankan dan Menggunakan Program
1. Siapkan file input (misalnya test3.txt) dengan format:
  N M P
  S
  puzzle_1_shape
  puzzle_2_shape
  …
  puzzle_P_shape
2. Jalankan program dengan perintah berikut:
   java ReadFile
3. Jika solusi ditemukan, program akan:
   -Menampilkan hasil dengan warna di terminal.
   -Menunjukkan jumlah kasus yang ditinjau.
   -Menampilkan waktu eksekusi.
   -Menawarkan opsi untuk menyimpan solusi ke dalam file.
4. Jika ingin menyimpan solusi, ketik "ya" saat ditanya. Jika tidak ingin menyimpan solusi, ketik "tidak" saat ditanya. Solusi akan disimpan di solution.txt.

# Author
Nama: Muhamamd Zakkiy
Email: muhammadzakkiy6@gmail.com
