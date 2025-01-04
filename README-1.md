Aplikasi Keuangan Harian

Deskripsi

Aplikasi Keuangan Harian adalah program sederhana berbasis C++ yang membantu pengguna mencatat dan menghitung pengeluaran harian mereka. Program ini memungkinkan pengguna untuk menambahkan pengeluaran, melihat total pengeluaran, dan menampilkan sisa saldo.

Fitur Utama

Tambah Pengeluaran

Pengguna dapat menambahkan pengeluaran dengan memasukkan nama kategori dan jumlah pengeluaran.

Program akan mengurangi saldo berdasarkan jumlah pengeluaran yang dimasukkan.

Program akan memberikan peringatan jika jumlah pengeluaran lebih besar dari saldo.

Tampilkan Total Pengeluaran

Menampilkan total pengeluaran yang telah dicatat sejauh ini.

Tampilkan Sisa Saldo

Menampilkan sisa saldo yang tersisa setelah dikurangi dengan total pengeluaran.

Keluar

Mengakhiri program dengan menampilkan pesan perpisahan.

Cara Menggunakan

Kompilasi program menggunakan compiler C++ seperti g++:

g++ -o keuangan_harian keuangan_harian.cpp

Jalankan program:

./keuangan_harian

Masukkan saldo awal saat diminta.

Pilih opsi yang tersedia di menu utama:

1 untuk menambah pengeluaran.

2 untuk menampilkan total pengeluaran.

3 untuk menampilkan sisa saldo.

4 untuk keluar dari aplikasi.

Program akan terus menampilkan menu utama hingga pengguna memilih opsi keluar.

Contoh Interaksi

Selamat datang di Aplikasi Keuangan Harian!
Masukkan saldo awal Anda: 500000

Menu Utama:
1. Tambah Pengeluaran
2. Tampilkan Total Pengeluaran
3. Tampilkan Sisa Saldo
4. Keluar
Pilih opsi (1-4): 1
Masukkan nama kategori pengeluaran: Makanan
Masukkan jumlah pengeluaran: 100000
Pengeluaran untuk Makanan sebesar 100000 berhasil ditambahkan!

Menu Utama:
1. Tambah Pengeluaran
2. Tampilkan Total Pengeluaran
3. Tampilkan Sisa Saldo
4. Keluar
Pilih opsi (1-4): 3
Sisa saldo Anda: 400000

Menu Utama:
1. Tambah Pengeluaran
2. Tampilkan Total Pengeluaran
3. Tampilkan Sisa Saldo
4. Keluar
Pilih opsi (1-4): 4
Terima kasih telah menggunakan Aplikasi Keuangan Harian!

Penanganan Error

Program akan menolak pengeluaran jika jumlah pengeluaran lebih besar dari saldo.

Program akan menolak pengeluaran jika jumlah yang dimasukkan kurang dari atau sama dengan nol.

Jika pengguna memasukkan opsi yang tidak valid, program akan memberikan pesan kesalahan dan meminta pengguna untuk memilih opsi yang benar.

Teknologi yang Digunakan

Bahasa Pemrograman: C++

Compiler: g++ atau compiler C++ lainnya
