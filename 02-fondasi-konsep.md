[← Kembali ke Bab 1](01-pengantar.md)

# Bab 2 – Fondasi Konsep Dasar

## 1. Istilah Kunci
| Istilah | Arti |
|----------|------|
| Bid | Harga dan jumlah lot yang ingin dibeli |
| Offer (Ask) | Harga dan jumlah lot yang ingin dijual |
| Spread | Selisih antara offer terendah dan bid tertinggi |
| Depth | Banyaknya level harga yang terlihat di order book |
| Last Price | Harga transaksi terakhir |
| Volume | Jumlah saham yang diperdagangkan dalam periode tertentu |

## 2. Mekanika Order Book
Order book adalah daftar antrian jual-beli saham. Ketika seseorang membeli di harga offer, *likuiditas berkurang di sisi jual*. Jika pembeli agresif terus menyerang offer, harga akan naik.

Ilustrasi sederhana:
```
Harga   | Bid (Lot) || Offer (Lot) | Harga
-------------------------------------------
14.450  | 800       || 1.200       | 14.475
14.425  | 1.100     || 4.000       | 14.500
14.400  | 900       || 1.600       | 14.525
```

## 3. Jenis Order dan Dampaknya
- **Limit Order:** Masuk ke antrian bid/offer (likuiditas pasif).  
- **Market Order:** Langsung serang harga lawan (likuiditas agresif).  
- **Stop Order:** Aktif hanya setelah level tertentu tersentuh.

> Intinya: siapa yang *menyerang lawan* menentukan arah pergerakan harga.

---
[→ Lanjut ke Bab 3: Teknik Membaca Order Book](03-teknik-membaca.md)
