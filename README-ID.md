# LYTUXZ Finance — proyek Android awal

Proyek ini membungkus prototipe HTML LYTUXZ v1.6 ke dalam aplikasi Android WebView.

## Status
- Proyek Android awal tersedia.
- Build APK belum dijalankan atau diverifikasi di lingkungan ini.
- Ini masih versi awal; sebelum dipakai untuk keuangan penting, fitur dan penyimpanan harus diuji.

## Cara paling mudah build lewat HP
1. Buat repositori GitHub baru dan unggah isi folder proyek ini.
2. Buka tab **Actions** di repositori.
3. Pilih workflow **Build LYTUXZ APK** lalu tekan **Run workflow**.
4. Setelah selesai, buka hasil workflow dan unduh artifact `LYTUXZ-debug-apk`.
5. Ekstrak ZIP artifact untuk mendapatkan `app-debug.apk`, lalu pasang di HP Android.

Build online membutuhkan akun GitHub. Workflow debug APK tidak memerlukan biaya untuk penggunaan dasar GitHub Actions sesuai batas gratis yang berlaku, tetapi kebijakan kuota dapat berubah.

## Catatan penting
- Data prototipe disimpan dalam penyimpanan browser/WebView lokal. Menghapus data aplikasi atau uninstall dapat menghilangkannya; ekspor cadangan secara rutin.
- File ini belum menyediakan integrasi bank, sinkronisasi cloud, atau tanda tangan rilis Google Play.
- Impor file cadangan dan pengunduhan laporan perlu diuji kembali di WebView Android. Build awal ini belum boleh dianggap rilis final.
