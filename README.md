# Bid–Offer & Order Book — E-book

Repositori ini berisi e-book **Bid–Offer & Order Book** yang dapat dibaca langsung di GitHub Pages (Docsify) atau diunduh sebagai ZIP/PDF/EPUB.

## 🔗 Tautan Utama
- **Baca Online (GitHub Pages)**: `https://inspirasiprogrammer.github.io/bid-offer-ebook/` *(aktif setelah kamu mengaktifkan GitHub Pages dan push folder `/docs`)*
- **Unduh versi ZIP**: (lihat rilis atau gunakan file ZIP yang saya kirim di obrolan ini)

## 📦 Struktur
```
/docs
  ├── index.html
  ├── _sidebar.md
  ├── README.md
  ├── 00-pendahuluan.md
  ├── 01-fondasi-konsep.md
  ├── 02-bid-offer.md
  ├── 03-order-book.md
  ├── 04-strategi-eksekusi.md
  ├── 05-manajemen-risiko.md
  ├── 06-latihan-praktik.md
  ├── 07-advanced-topics.md
  ├── 08-lampiran-template.md
  └── assets/
      └── .gitkeep
LICENSE
CHANGELOG.md
EDITING_CHECKLIST.md
```

## ▶️ Cara Baca Lokal
Tanpa instalasi khusus — cukup buka `docs/index.html` di browser; atau jalankan server statis:
```
python3 -m http.server -d docs 3000
# lalu buka http://localhost:3000
```

## 🚀 Deploy ke GitHub Pages
1. Commit & push ke branch `main`.
2. Di **Settings → Pages**, set **Source: `main`** dan **Folder: `/docs`**.
3. Tunggu build selesai; situs akan tayang di `https://<username>.github.io/bid-offer-ebook/`.

## 🧪 Konversi ke PDF/EPUB (opsional)
Menggunakan Pandoc (pastikan terinstal):
```
pandoc docs/*.md -o BidOfferEbook.pdf
pandoc docs/*.md -o BidOfferEbook.epub
```

## 📝 Lisensi
MIT © 2025 Irwan Syahputra (@inspirasiprogrammer)
