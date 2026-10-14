XI TKJ — KELAS DIGITAL
Dibuat oleh Nazril

ISI FITUR
- Beranda dan ringkasan kelas
- Daftar tugas, tenggat, prioritas, dan tanda selesai
- Notifikasi tugas (izin notifikasi browser diperlukan; notifikasi tugas baru ditampilkan pada perangkat tempat tugas dibuat)
- Rekap absensi: Hadir, Izin, Sakit, Alpa
- Jadwal mata pelajaran
- Jadwal piket Senin–Jumat
- Struktur organisasi kelas
- Login panel admin
- Ekspor dan impor cadangan JSON
- Penyimpanan lokal dan cache offline PWA

LOGIN ADMIN DEMO
Username: nazril
Password: admin1

PENTING
Versi ini adalah aplikasi front-end offline. Data disimpan di browser/perangkat yang dipakai, tidak otomatis tersinkron ke HP siswa lain. Untuk rekap kelas bersama yang bisa diperbarui dari banyak HP, dibutuhkan backend/database online.

Login admin front-end bukan keamanan sungguhan karena kredensial di dalam kode bisa dilihat oleh orang yang memeriksa file. Jangan pakai password penting dan jangan simpan data sensitif.

CARA MEMBUKA DARI HP ANDROID
1. Ekstrak ZIP ini ke folder di HP.
2. Untuk uji coba cepat, buka index.html dengan browser atau editor HTML yang mendukung preview. Sebagian fitur seperti service worker, pemasangan ke layar utama, dan notifikasi memerlukan situs HTTPS atau localhost.
3. Untuk memasang sebagai aplikasi dan membuat cache offline, unggah semua isi folder ke hosting HTTPS (contohnya GitHub Pages, Netlify, atau Vercel).
4. Buka URL HTTPS di Chrome Android, pilih menu browser, lalu “Tambahkan ke layar utama” / “Install app” jika ditampilkan.
5. Buka aplikasi sekali saat online agar file cache tersimpan. Setelah itu, halaman utama dapat dibuka tanpa internet.

CARA MENGGUNAKAN
- Buka Panel Admin.
- Login dengan username dan password demo di atas.
- Gunakan formulir Tambah Tugas atau Tambah Absensi.
- Ekspor JSON secara berkala untuk cadangan. Simpan file cadangan di tempat aman.
- Pengguna bisa menandai tugas sebagai selesai. Status ini tersimpan lokal di perangkat itu.
