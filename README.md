# Portfolio personal — GitHub + Vercel

Website portfolio statis yang dibuat mengikuti referensi video: latar bintang bergerak, intro lightning singkat, navigasi Home/About/Portfolio/Contact, foto profil, timeline, kartu proyek, filter kategori, daftar skill, dan formulir kontak.

## Struktur file

- `index.html` — semua HTML, CSS, dan JavaScript.
- `assets/profile.jpg` — taruh foto profil kamu di sini. Kalau file belum ada, website menampilkan placeholder.
- `assets/README.txt` — petunjuk foto.

## Edit informasi pribadi

Di `index.html`, cari bagian `EDIT DATA PORTFOLIO DI BAGIAN INI`, lalu ganti:
- `Nama Kamu`
- `emailkamu@example.com`
- `https://github.com/username`
- `https://instagram.com/username`

Ubah juga deskripsi, proyek contoh, statistik, dan skill supaya sesuai keadaanmu. Jangan biarkan data contoh dianggap sebagai pencapaian asli.

## Deploy lewat HP Android

1. Download dan ekstrak ZIP ini menggunakan aplikasi pengelola file HP.
2. Buat repository di https://github.com/new, misalnya `portfolio-website`.
3. Di repository, tekan **Add file → Upload files**. Upload `index.html` serta folder `assets` beserta file di dalamnya. Pastikan path foto tetap `assets/profile.jpg`.
4. Tekan **Commit changes**.
5. Buka https://vercel.com/new dan login dengan GitHub.
6. Import repository `portfolio-website`. Untuk situs statis ini, Framework Preset pilih **Other** (atau biarkan terdeteksi), Build Command kosong, Output Directory kosong/default. Tekan **Deploy**.
7. Setelah selesai, buka URL `.vercel.app` yang ditampilkan Vercel.

## Cara menambahkan foto

Ubah nama file foto kamu menjadi `profile.jpg`, lalu upload ke folder `assets` di GitHub. Gunakan foto yang kamu punya hak untuk dipublikasikan. Bila upload foto lewat web GitHub HP terasa sulit, buka folder `assets` di repository → Add file → Upload files.

## Tes fungsi

- Menu atas berpindah ke section yang sesuai.
- Filter kategori menyaring kartu proyek.
- Formulir memeriksa nama, email, dan pesan lalu membuka aplikasi email.
- Animasi bintang dan reveal berjalan di browser modern.

Catatan: form kontak memakai `mailto:` sehingga aplikasi email pengunjung perlu dikonfigurasi. Ini tidak mengirim pesan ke database/server. Untuk form yang mengirim tanpa aplikasi email, perlu layanan form/backend terpisah.
