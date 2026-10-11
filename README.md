# Website Demo Multipage SMP Negeri 2 Kota Blitar — WEB IN-AJA

## Struktur proyek
- `index.html` — beranda
- `profil.html` — profil, visi, misi, nilai pendidikan
- `akademik.html` — kurikulum, proses belajar, kalender, fasilitas
- `kesiswaan.html` — OSIS, ekstrakurikuler, prestasi, pembinaan
- `informasi.html` — berita, pengumuman, agenda, SPMB
- `galeri.html` — dokumentasi
- `kontak.html` — alamat dan kontak
- `css/style.css` — seluruh desain, responsif, satu stylesheet bersama
- `js/script.js` — hamburger, animasi reveal, tahun footer
- `assets/images/logo-smpn2.jpg` — logo dari pengguna
- `assets/images/foto-bersama.jpg` — foto bersama dari pengguna
- `assets/images/favicon.svg` — favicon konsep

## Cara menjalankan
Buka `index.html` di browser. Semua halaman HTML berada di root folder supaya mudah dipakai di GitHub Pages. Foto dan Google Fonts perlu koneksi internet? Foto yang diberikan pengguna disimpan lokal; Google Fonts perlu koneksi internet.

## Deploy GitHub Pages
1. Buat repository baru, misalnya `demo-smpn2-kota-blitar`.
2. Upload semua isi folder proyek, bukan folder ZIP-nya.
3. Pastikan `index.html` berada di root repository.
4. Buka Settings → Pages.
5. Pada Build and deployment, pilih Deploy from a branch, branch `main`, folder `/(root)`, lalu Save.
6. Tunggu proses selesai, kemudian buka URL Pages yang ditampilkan GitHub.
7. Coba semua tautan dari Beranda sampai Kontak di HP dan laptop.

## Peringatan konten
- Website ini adalah DEMO, bukan situs resmi SMP Negeri 2 Kota Blitar.
- Logo dan foto yang disertakan berasal dari pengguna. Pastikan pengguna memiliki izin yang diperlukan untuk mempublikasikannya.
- Visi dan misi pada `profil.html` adalah CONTOH SEMENTARA untuk diganti, bukan visi-misi resmi sekolah.
- Data alamat, telepon, email, akreditasi, dan NPSN harus diverifikasi dengan sumber resmi sebelum ditampilkan sebagai informasi resmi.
- Berita, jadwal, prestasi, daftar ekstrakurikuler, dan informasi SPMB masih berupa kategori/template.
- Tidak ada panel admin atau database. Developer memperbarui file HTML secara manual.
- Untuk melindungi reputasi demo, jangan menyatakan situs ini sebagai website resmi tanpa persetujuan sekolah.

## Mengganti visi dan misi
Buka `profil.html`, cari `VISI SEKOLAH · DRAF PENGGANTI` dan `MISI SEKOLAH · DRAF PENGGANTI`, lalu ganti teks contoh dengan teks resmi setelah dikonfirmasi.
