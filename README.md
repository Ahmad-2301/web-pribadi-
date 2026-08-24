# Website Pribadi Aman

Website portfolio pribadi yang modern, responsif, cepat, dan dibangun dengan praktik keamanan terbaik untuk situs statis.

## Fitur

- ✅ Desain modern (dark/light mode)
- ✅ Fully responsive (mobile-first)
- ✅ Navigasi smooth scroll
- ✅ Form kontak dengan validasi dasar
- ✅ Content Security Policy (CSP)
- ✅ Header keamanan (X-Content-Type-Options, X-Frame-Options, Referrer-Policy)
- ✅ Tidak ada tracker pihak ketiga
- ✅ Performa tinggi (tanpa framework berat)

## Cara Menggunakan

1. Ganti semua placeholder:
   - `Nama Anda` / `NamaAnda`
   - `email@contoh.com`
   - Deskripsi, skill, proyek, dll.

2. Buka `index.html` di browser untuk preview.

3. Untuk hosting (sangat direkomendasikan yang gratis & aman):
   - **Cloudflare Pages** (paling direkomendasikan)
   - **Netlify**
   - **Vercel**
   - **GitHub Pages**

## Tips Keamanan Produksi

1. **Gunakan HTTPS** — semua hosting di atas sudah otomatis.
2. **Hubungkan form kontak** ke layanan aman seperti:
   - Formspree
   - Getform
   - atau backend sendiri dengan rate limiting + CAPTCHA
3. **Jangan** menyimpan data sensitif di frontend.
4. Aktifkan **HSTS** di Cloudflare / hosting Anda.
5. Pertimbangkan menambahkan `robots.txt` dan `sitemap.xml` jika ingin SEO.

## Struktur File

```
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Kustomisasi Cepat

- Warna utama: ubah variabel `--accent` di `styles.css`
- Font: ganti Google Fonts di `index.html`
- Tema default: edit logika di `script.js`

---

Dibuat dengan fokus pada **keamanan**, **privasi**, dan **kinerja**.
