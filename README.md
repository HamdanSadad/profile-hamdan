<!--
  README untuk project portofolio "web-ce"
  Ditulis dalam bahasa Indonesia agar mudah dipahami.
-->

# Portofolio - Web CE

Ringkasan singkat

- Halaman portofolio sederhana berisi: hero (foto + teks), ikon sosial, dan footer.
- Dibuat sebagai proyek statis (HTML + CSS + sedikit JavaScript untuk efek typing).

Fitur

- Responsif: tata letak adaptif untuk desktop, tablet, dan ponsel.
- Ikon sosial yang bisa diarahkan ke GitHub / LinkedIn / WhatsApp / Instagram.
- Efek typing pada judul dan dekorasi lingkaran di belakang foto profil.

Struktur file

- `index.html` — markup utama halaman.
- `style.css` — semua styling dan media queries responsif.
- `js/nilai2.js` — contoh skrip/latihan (grading logic).
- `img/` — gambar profil dan ikon sosial.

Menjalankan secara lokal

1. Cara cepat: buka `index.html` langsung di browser (klik dua kali atau `Open File`).
2. Cara yang lebih baik (disarankan saat mengembangkan): gunakan Live Server diVSCode.

Contoh perintah (Git + push ke repo baru)

```bash
git init
git add .
git commit -m "Initial commit - portfolio"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

Deploy ke GitHub Pages (cara cepat)

1. Buat repository baru di GitHub dan push kode (lihat perintah di atas).
2. Buka Settings > Pages pada repository GitHub.
3. Pilih source: `main` branch dan folder `/ (root)`, lalu klik Save.
4. Tunggu beberapa menit; situs akan tersedia di `https://<username>.github.io/<repo>/`.

Tips penyesuaian

- Ganti gambar di `img/profil.jpg` untuk menggunakan foto sendiri.
- Update tautan di `index.html` pada elemen `.social` agar mengarah ke akun Anda.
- Jika ingin menambah halaman, buat folder baru dan perbarui navigasi bila perlu.

Kontribusi

- Fork repository, buat perubahan pada branch baru, lalu buka pull request.

Lisensi

- Jika ingin menambahkan lisensi, tambahkan file `LICENSE` (mis. MIT) di root repository.

Kontak

- Untuk pertanyaan cepat, tambahkan detail kontak pada `index.html` atau bagian footer.

Terima kasih telah menggunakan proyek ini — semoga membantu sebagai dasar portofolio Anda.
