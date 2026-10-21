# PAW Modul 2 - Latihan CRUD Showroom

## 9. Hubungan Antarfile

### Koneksi dan fungsi pendukung

- **`connect.php`** membuka koneksi ke database MySQL dan menyediakan koneksi melalui variabel `$conn`.
- **`functions.php`** berisi fungsi-fungsi pendukung untuk membaca input, memvalidasi data, mengamankan keluaran HTML, memformat harga, dan mencari data mobil.
- **`db_modul2.sql`** berisi struktur database dan data contoh. Impor berkas ini ke MySQL sebelum menjalankan aplikasi.

### Halaman aplikasi

- **`index.php`** menampilkan daftar mobil, pencarian, dan filter tipe. Dari halaman ini pengguna dapat membuka halaman tambah, detail, atau edit.
- **`create.php`** menampilkan form dan menyimpan mobil baru. Setelah penyimpanan berhasil, pengguna diarahkan kembali ke daftar mobil.
- **`detail.php`** menampilkan informasi lengkap satu mobil, dengan tautan untuk mengedit, menghapus, atau kembali ke daftar.
- **`update.php`** menampilkan form edit dan menyimpan perubahan data mobil. Setelah berhasil, pengguna diarahkan kembali ke halaman detail mobil.
- **`delete.php`** meminta konfirmasi sebelum menghapus mobil. Setelah penghapusan berhasil, pengguna diarahkan kembali ke daftar mobil.

### Tampilan

- **`form_mobil.php`** berisi field form data mobil yang digunakan bersama oleh `create.php` dan `update.php`.
- **`header.php`** menampilkan bagian atas halaman, navigasi, dan pesan notifikasi. Berkas ini juga memuat `styles.css`.
- **`footer.php`** menampilkan bagian bawah halaman.
- **`styles.css`** mengatur tampilan halaman dan komponen aplikasi.
