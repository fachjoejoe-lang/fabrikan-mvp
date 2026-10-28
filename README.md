# Fabrikan.id — Smart Inventory MVP

Prototype front-end untuk ide aplikasi inventaris bahan baku manufaktur.

## Fitur demo
- Dashboard ringkasan inventaris dan grafik aktivitas simulasi.
- Daftar bahan baku dengan pencarian dan filter status.
- Tambah dan edit bahan baku.
- Simulasi penyesuaian stok masuk/keluar.
- Notifikasi stok minimum.
- Ekspor data inventaris ke CSV.
- Halaman pergerakan stok dan data pemasok.
- Layout responsif untuk desktop dan ponsel.

> Catatan: Ini adalah mockup front-end. Data disimpan sementara di memori browser selama halaman terbuka. Belum ada backend, autentikasi, database, sinkronisasi cloud, kamera barcode sungguhan, atau RFID.

## Jalankan lokal
Pastikan Node.js dan npm sudah terpasang.

```bash
npm install
npm start
```

Buka alamat lokal yang ditampilkan di terminal (umumnya http://localhost:3000).

## Deploy ke Railway
1. Push folder ini ke repository GitHub.
2. Di Railway, buat project baru dan pilih deploy dari repository GitHub.
3. Pilih repository `fabrikan-mvp`.
4. Railway akan membaca `package.json` dan menjalankan script `start`.
5. Setelah deployment selesai, buka Settings / Networking lalu generate domain publik jika belum tersedia.
6. Pastikan build/deployment berhasil, kemudian kunjungi domain tersebut.

Railway dan kebijakan paket gratis dapat berubah; periksa dashboard dan dokumentasi Railway saat deploy.
