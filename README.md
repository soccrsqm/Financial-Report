# Financial Report Indra Gusti HSB

Dashboard keuangan pribadi berbasis HTML/CSS/JavaScript. Tidak membutuhkan proses build atau instalasi.

## Fitur
- Dashboard dark mode dengan layout responsif seperti gambar referensi.
- Kartu ringkasan pengeluaran, sisa anggaran, target tabungan, dan rata-rata harian.
- Grafik donut kategori dan grafik pengeluaran mingguan.
- Kalender transaksi, peringatan anggaran, transaksi terbaru.
- Form tambah pengeluaran, pencarian transaksi.
- Backup/restore JSON, ekspor CSV untuk Excel, dan cetak ke PDF.
- Penyimpanan data lokal browser melalui localStorage.

## Upload ke GitHub Pages
1. Buat repository baru di GitHub.
2. Upload `index.html` dan `README.md` ke root repository.
3. Buka **Settings → Pages**.
4. Pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu Save.
5. Buka URL GitHub Pages yang muncul.

## Penting
- Data disimpan di browser yang digunakan, tidak otomatis tersinkron ke perangkat lain.
- Grafik memakai Chart.js dari CDN dan font Inter dari Google Fonts, jadi perlu koneksi internet.
- Pilihan bukti transaksi saat ini hanya menampilkan nama file, belum mengunggah gambar ke server.
- Nilai awal transaksi adalah data contoh dan dapat diganti dengan transaksi milik sendiri.
