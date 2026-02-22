# FIGHTING RANSOMWARE: DATA RECOVERY SYSTEM

**Fighting Ransomware** adalah kerangka kerja keamanan profesional yang dirancang untuk mengidentifikasi dan memulihkan integritas data yang terdampak oleh berbagai varian enkripsi berbahaya. Proyek ini dikembangkan sebagai alat bantu bagi peneliti keamanan siber dan spesialis pemulihan data untuk mengembalikan aset digital secara efisien.

## Fitur Utama

* **Heuristic Signature Scanning**: Sistem mampu memindai direktori secara otomatis untuk mendeteksi tanda tangan digital dari varian ransomware tertentu.
* **Multi-Variant Database**: Mendukung identifikasi untuk lebih dari 100 keluarga ransomware global.
* **Modular Recovery Kernel**: Arsitektur sistem yang memungkinkan penambahan modul pemulihan baru sesuai dengan perkembangan ancaman siber.
* **Professional Interface**: Tampilan antarmuka yang bersih, sejajar, dan fungsional untuk memudahkan pengoperasian dalam situasi darurat data.

## Detail Teknis Pemulihan

Sistem ini memiliki modul aktif yang dioptimalkan khusus untuk varian **rm19ware**. = Berdasarkan analisis pada kode sumbernya, varian ini menggunakan teknik kompresi data tingkat tinggi (`gzdeflate` level 9) untuk menyembunyikan konten asli file=

Logika pemulihan pada sistem ini bekerja dengan:
1. Melakukan verifikasi tanda tangan file pada direktori target.
2. Menerapkan algoritma dekompresi *engine-level* untuk membalikkan proses penguncian
3. Mengembalikan integritas file asli dan menghapus jejak enkripsi berbahaya secara permanen

## Cara Penggunaan

1. Jalankan aplikasi utama **fight.ransomeware.exe**.
2. Pilih direktori atau folder yang terdampak melalui menu **Choose Directory**.
3. Gunakan fitur **Scan for Variants** untuk identifikasi otomatis, atau pilih varian secara manual dari database yang tersedia.
4. Klik **Start Recovery Process** untuk memulai langkah pemulihan data.
<img src="https://raw.githubusercontent.com/Mister-RdanM19/Fight.RANSOMEWARE/refs/heads/main/tampilan.png">

## Disclaimer

Alat ini disediakan untuk tujuan edukasi, penelitian keamanan siber, dan pemulihan data yang sah secara hukum. Pengembang tidak bertanggung jawab atas penyalahgunaan alat ini untuk aktivitas ilegal apa pun.

---
**Developed by: Mr.Rm19** 
