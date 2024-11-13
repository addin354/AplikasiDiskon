# Aplikasi Perhitungan Diskon Harga

Aplikasi ini adalah aplikasi GUI berbasis Java Swing yang memungkinkan pengguna untuk menghitung diskon harga suatu produk. Pengguna dapat memasukkan harga asli, menentukan persentase diskon menggunakan slider, 
serta memasukkan kode kupon opsional untuk mendapatkan tambahan diskon.

## Identitas
- Nama  : Addin Husnan Nadhari
- Npm   : 2210010037
- Kelas : 5B Nonreg Banjarmasin

## Fitur

- **Input Harga Asli**: Pengguna dapat memasukkan harga asli dari produk.
- **Slider Diskon**: Menentukan persentase diskon antara 0% hingga 50%.
- **Kode Kupon**: Masukkan kode kupon "DISKON10" untuk mendapatkan tambahan diskon 10%.
- **Hasil Perhitungan**: Menampilkan harga akhir setelah diskon dan jumlah penghematan.
- **Riwayat Perhitungan**: Menampilkan riwayat perhitungan diskon pada JTextArea.
- **Tombol Keluar**: Menutup aplikasi.

## Cara Menggunakan

1. Jalankan aplikasi.
2. Masukkan harga asli produk.
3. Tentukan persentase diskon menggunakan slider.
4. (Opsional) Masukkan kode kupon "DISKON10" untuk tambahan diskon 10%.
5. Klik tombol "Hitung" untuk melihat harga akhir dan penghematan.
6. Riwayat perhitungan akan ditampilkan pada JTextArea di sebelah kanan.
7. Klik tombol "Keluar" untuk menutup aplikasi.

## Struktur Kode

- **DiskonFrame**: Kelas utama yang mewarisi `javax.swing.JFrame` untuk mengatur tampilan dan fungsi aplikasi.
- **hitungDiskon()**: Fungsi untuk menghitung diskon berdasarkan harga asli dan persentase diskon.
- **updateRiwayat()**: Fungsi untuk memperbarui tampilan riwayat diskon pada JTextArea.

## Persyaratan Sistem

- Java Development Kit (JDK) 8 atau lebih tinggi.
- IDE Java seperti NetBeans atau IntelliJ IDEA untuk pengembangan dan pengujian.

## Cara Menjalankan Aplikasi

1. Clone repository ini.
2. Buka proyek di IDE Java pilihan Anda.
3. Compile dan run `DiskonFrame` sebagai program utama.
4. Aplikasi akan muncul dengan antarmuka GUI untuk mengelola diskon.


