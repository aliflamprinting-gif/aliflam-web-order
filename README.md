# ALIFLAM PRINTING — Halaman Pemesanan

1. Unggah isi folder ini ke repository GitHub Pages.
2. Buka `index.html` dan ganti URL `ISI_DEPLOYMENT_ID` dengan URL Web App Apps Script yang sudah di-deploy.
3. Pastikan sheet VARIASI PRODUK sudah berisi SKU aktif, bahan, ukuran, finishing, harga, dan berat.
4. Setiap baris variasi ditampilkan sebagai item katalog tersendiri.

Halaman ini belum terhubung ke payment gateway. QRIS/transfer dicatat sebagai metode pembayaran dan verifikasi dilakukan admin.


## Konfigurasi koneksi
Database Spreadsheet sudah dipasangkan pada backend Apps Script dengan ID:
`1-aUrmYTsfSikkyUQ_lf08aGv-QX6jGEXdt8gEsqn3WI`

Untuk alasan keamanan, halaman pelanggan tidak mengakses Spreadsheet secara langsung. Setelah Apps Script dideploy sebagai Web App, URL Web App `/exec` sudah dipasangkan di `index.html`.


URL API terpasang: https://script.google.com/macros/s/AKfycbzzis01Cv-kWurEimDySmksL_6bvASB_sQop0X64kILzKULHWM1E2Ci7lX2PFctUA5G1w/exec
