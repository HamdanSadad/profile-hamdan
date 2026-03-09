# Portofolio - Web CE

Ringkasan singkat

- Halaman portofolio sederhana berisi: hero (foto + teks), ikon sosial, dan footer.
- Dibuat sebagai proyek statis (HTML + CSS + sedikit JavaScript untuk efek typing).

Fitur

- Responsif: tata letak adaptif untuk desktop, tablet, dan ponsel.
- Ikon sosial yang bisa diarahkan ke GitHub / LinkedIn / WhatsApp / Instagram.
- Efek typing pada judul dan dekorasi lingkaran di belakang foto profil.

# Portofolio - Web CE

## Deskripsi

Proyek ini adalah halaman portofolio statis sederhana yang menampilkan foto profil, teks perkenalan, ikon sosial, dan footer. Dibangun dengan HTML, CSS, dan sedikit JavaScript untuk animasi dan fitur tema gelap/terang.

## Fitur utama

- Responsif: tata letak menyesuaikan untuk desktop, tablet, dan ponsel.
- Tema Gelap/Terang: toggle yang menyimpan preferensi pengguna (localStorage) dan mendukung prefers-color-scheme.
- Ikon sosial: tautan ke akun (GitHub, LinkedIn, WhatsApp, Instagram) dengan state fokus/hover yang jelas di kedua tema.
- Animasi mengetik sederhana pada judul.

## Struktur folder (ringkasan)

Berikut struktur file penting di proyek ini:

```
web-ce/
├─ index.html        # Halaman utama
├─ style.css         # Styling dan responsive rules
├─ README.md         # Dokumentasi (file ini)
└─ img/              # Gambar: profil dan ikon sosial
	├─ profil.jpg
	├─ github.png
	├─ linkedin.png
	├─ whatsapp.png
	└─ instagram.png
```

> Catatan: jika Anda menambahkan JavaScript atau folder lain, tambahkan ke struktur di atas.

## Spesifikasi teknis

- No build tools: proyek ini statis, tidak memerlukan Node.js atau bundler.
- Browser: modern browsers (Chrome, Edge, Firefox, Safari). Dukung minimal untuk CSS variables dan prefers-color-scheme.
- Aksesibilitas: tombol tema memiliki atribut ARIA (`aria-pressed`) dan fokus terlihat.

## Cara clone dan mulai (langkah demi langkah)

1. Clone repository:

```bash
git clone https://github.com/<username>/<repo>.git
cd <repo>
```

2. Buka langsung (cara cepat):

- Buka `index.html` di browser (klik dua kali atau `Open File`).

3. Atau gunakan Live Server (direkomendasikan untuk pengembangan):

- Di VSCode, install ekstensi **Live Server**, lalu klik `Go Live`.

## Perintah Git contoh untuk commit & push

```bash
git add .
git commit -m "feat: initial portfolio site"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

## Deploy ke GitHub Pages

1. Push code ke repository GitHub.
2. Buka `Settings` > `Pages` di repo GitHub.
3. Pilih source: `main` branch dan folder `/ (root)`, lalu klik `Save`.
4. Setelah beberapa menit, situs dapat diakses di `https://<username>.github.io/<repo>/`.

> Opsional: jika menggunakan custom domain, tambahkan file `CNAME` dan konfigurasi DNS.

## Tips kustomisasi cepat

- Ubah foto profil: ganti file `img/profil.jpg`.
- Update tautan sosial: edit elemen `<a class="social" href="...">` di `index.html`.
- Warna & tema: ubah variabel warna di `:root` pada `style.css`.
- Tambah halaman baru: buat file HTML baru dan perbarui navigasi.

## Rekomendasi sebelum push

- Periksa gambar teroptimasi (resize/webp) agar loading cepat.
- Tambahkan file `LICENSE` (mis. MIT) jika ingin membagikan kode secara terbuka.
- Tambahkan `.gitignore` jika diperlukan (tidak wajib untuk proyek statis kecil).

## Kontribusi

PR diterima: Fork proyek, buat branch baru, lalu buka pull request. Sertakan deskripsi singkat perubahan.

## Kontak

Untuk pertanyaan atau bantuan, tambahkan kontak pada `index.html` atau hubungi pemilik repo.

## Lisensi

Tambahkan file `LICENSE` jika Anda ingin menetapkan lisensi (mis. MIT).

## Terima kasih

Semoga file ini membantu menjelaskan proyek dan memudahkan proses deploy ke GitHub Pages.
