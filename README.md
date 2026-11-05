# CV Digital — Prayogi Sastra Adi Raja

Website Curriculum Vitae (CV) digital berbasis HTML, CSS, GitHub, dan Docker.
Proyek UTS Teknologi Web Ganjil 2025/2026, Universitas Bani Saleh.
Dosen: M. Dedi Suryadi.

## Isi Website

- **Home / Profil:** nama, foto profil, profesi, email, telepon, dan deskripsi diri.
- **About:** tentang saya.
- **Education:** D3 Teknik Komputer, Universitas Bani Saleh (semester 5).
- **Experience:** Asisten Laboratorium dan proyek perkuliahan.
- **Skills:** Jaringan Komputer, HTML & CSS, Git & GitHub, Docker & WSL, Pemrograman Mobile, VSCode.
- **Portfolio:** Website CV Digital, Aplikasi Referensi Obat, Topologi Jaringan Komputer 2, Denah Rumah Modern Minimalis.
- **Contact:** email, telepon, GitHub, dan lokasi.

## Teknologi

- HTML5 semantik (`header`, `nav`, `main`, `section`, `article`, `footer`)
- CSS eksternal (`style.css`) dengan Flexbox dan CSS Grid
- Git dan GitHub
- Docker dengan image Nginx

## Menjalankan Secara Lokal

Buka `index.html` di browser, atau jalankan server sederhana:

```bash
python3 -m http.server 8000
```

Lalu buka http://localhost:8000

## Menjalankan dengan Docker

```bash
docker build -t cv-digital .
docker run -d -p 8080:80 --name cv-digital cv-digital
```

Lalu buka http://localhost:8080

Cek container yang berjalan:

```bash
docker ps
```

Berhenti dan hapus container:

```bash
docker stop cv-digital
docker rm cv-digital
```

## Struktur File

```text
index.html
style.css
profile.jpg
Dockerfile
README.md
```

## Catatan

- Ganti nomor telepon di `index.html` dengan nomor HP yang sebenarnya sebelum dikumpulkan, jika diperlukan.
- Foto profil di `profile.jpg` adalah gambar inisial; ganti dengan foto profil asli jika ada.
