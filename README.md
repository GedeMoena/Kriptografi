# Kriptografi
Soal
Buatlah sebuah program C++/Phyton/R yang mengimplementasikan:
a) Vigenere Cipher standard (26 huruf alfabet)
b) Tiga (3) varian Vigenere Cipher
c) Extended Vigenere Cipher (256 karakter ASCII)
d) Playfair Cipher (26 huruf alfabet)
e) Super enkripsi: Vigenere Cipher standard + cipher transposisi (bebas) dengan spesifikasi
sebagai berikut:
1. Program dapat menerima pesan berupa file sembarang (text atau file biner) atau pesan yang
diketikkan dari papan-ketik.
2. Program dapat mengenkripsi plainteks. Khusus untuk Vigenere Cipher dengan 26 huruf
alfabet dan Playfair Cipher dengan 26 huruf alfabet, program hanya mengenkripsi karakter
alfabet saja. Angka, spasi, dan tanda baca tidak dienkripsi, dibiarkan saja.
3. Program dapat mendekripsi cipherteks.
4. Program menampilkan plainteks dan cipherteks di layar.
5. Cipherteks dapat ditampilkan ke layar dalam bentuk:
(a) apa adanya (sesuai susunan plainteks)
(b) tanpa spasi
(c) dalam kelompok 5-huruf
6. Program dapat menyimpan cipherteks ke dalam file.
7. Kunci dimasukkan oleh pengguna. Panjang kunci bebas.
8. Untuk enkripsi plainteks sembarang file (dengan Extended Vigenere Cip her), setiap file

diperlakukan sebagai file of bytes. Program membaca se tiap byte di dalam file (termasuk byte-
byte header file) dan mengenkripsinya. Hanya saja file yang sudah terenkripsi tidak bisa dibuka

oleh program ap likasinya karena header file ikut terenkripsi. Namun dengan mendekripsinya
kembali maka file tersbut dapat dibuka oleh aplikasinya
