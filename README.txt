SISTEM KONVEKSI - VERCEL

Folder ini sudah disiapkan untuk deployment sebagai website statis di Vercel.
File utama: index.html

Cara deploy:
1. Ekstrak ZIP ini.
2. Buka https://vercel.com/ dan login.
3. Buat repository GitHub baru, misalnya "sistem-konveksi".
4. Upload file index.html ke repository tersebut.
5. Di Vercel pilih Add New -> Project, lalu Import repository GitHub tadi.
6. Framework Preset: Other.
7. Build Command: kosongkan / None.
8. Output Directory: . (root).
9. Klik Deploy. Setelah selesai, salin URL .vercel.app untuk dosen.

Catatan:
- Aplikasi ini menyimpan data pesanan di LocalStorage browser. Data demo/perubahan di laptop kamu tidak otomatis muncul di browser dosen.
- Login prototype: pilih peran, isi username dan password apa saja (tidak boleh kosong).
