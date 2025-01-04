# UAS-Agortima
Program Pengelolaan Data Mahasiswa
Program ini adalah aplikasi berbasis C++ yang digunakan untuk mengelola data mahasiswa. Program memiliki beberapa fitur seperti menambah data mahasiswa, mencari data berdasarkan NIM, mengurutkan data berdasarkan nilai akhir, serta menyimpan dan membaca data dari berkas (file).

Fitur Program
Tambah Data Mahasiswa
Memungkinkan pengguna untuk menambahkan data mahasiswa berupa:

NIM
Nama
Nilai Akhir
Tampilkan Semua Data
Menampilkan semua data mahasiswa yang telah dimasukkan.

Cari Data Mahasiswa
Pencarian mahasiswa berdasarkan NIM menggunakan algoritma pencarian linear.

Urutkan Data
Mengurutkan data mahasiswa berdasarkan Nilai Akhir dalam urutan menurun (descending) menggunakan algoritma Bubble Sort.

Simpan Data ke Berkas
Menyimpan data mahasiswa ke dalam berkas (file) bernama data_mahasiswa.txt dengan format:

Copy code
NIM,Nama,Nilai Akhir
Baca Data dari Berkas
Membaca data mahasiswa dari berkas data_mahasiswa.txt dan memuatnya kembali ke dalam program.

Keluar
Mengakhiri program dengan menampilkan pesan perpisahan.

Cara Menggunakan Program
Kompilasi Program
Gunakan compiler C++ seperti g++ untuk mengompilasi program:

bash
Copy code
g++ -o pengelolaan_mahasiswa pengelolaan_mahasiswa.cpp
Jalankan Program
Jalankan program yang telah dikompilasi:

bash
Copy code
./pengelolaan_mahasiswa
Ikuti Instruksi
Program akan menampilkan menu utama dengan beberapa pilihan:

markdown
Copy code
Menu Utama:
1. Tambah Data Mahasiswa
2. Tampilkan Semua Data
3. Cari Data Mahasiswa
4. Urutkan Data
5. Simpan Data ke Berkas
6. Baca Data dari Berkas
7. Keluar
Pilih opsi (1-7):
Pilih opsi yang diinginkan dengan memasukkan angka yang sesuai.

Contoh Interaksi dengan Program
yaml
Copy code
Menu Utama:
1. Tambah Data Mahasiswa
2. Tampilkan Semua Data
3. Cari Data Mahasiswa
4. Urutkan Data
5. Simpan Data ke Berkas
6. Baca Data dari Berkas
7. Keluar
Pilih opsi (1-7): 1
Masukkan jumlah mahasiswa: 2
Masukkan NIM Mahasiswa ke-1: 12345
Masukkan Nama Mahasiswa ke-1: Budi
Masukkan Nilai Akhir Mahasiswa ke-1: 85.0
Masukkan NIM Mahasiswa ke-2: 67890
Masukkan Nama Mahasiswa ke-2: Ani
Masukkan Nilai Akhir Mahasiswa ke-2: 90.5
Data berhasil ditambahkan!
Struktur Berkas
Program menyimpan data ke dalam berkas data_mahasiswa.txt dengan format sebagai berikut:

Copy code
12345,Budi,85.0
67890,Ani,90.5
Teknologi yang Digunakan
Bahasa Pemrograman: C++
Compiler: g++
