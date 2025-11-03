# 10 — Panduan Praktik Real-Time & Tools Analitik

## 1. Tools Observasi Order Book
- **RTI Business / MOST / Neo HOTS** — monitoring bid–offer live.  
- **TradingView + DOM Simulator** — untuk latihan visualisasi order flow.  
- **Excel / Python (pandas)** — mencatat snapshot order book & menghitung imbalance.

## 2. Praktik Harian
1. Pilih 1 saham likuid (SIMP, BREN, PGEO).  
2. Amati perubahan best bid/offer setiap 10 detik selama 10 menit.  
3. Catat kapan terjadi eksekusi besar & perbandingkan dengan perubahan harga.

## 3. Analisis Data
Gunakan log sederhana seperti:
```
timestamp, best_bid, best_offer, bid_vol, offer_vol, last_price
```
Kemudian hitung:
```
Imbalance = (bid_vol / offer_vol)
Hit Ratio = (transaksi di ask / total transaksi)
```

## 4. Saran Etika & Kebiasaan
- Jangan terpaku satu sinyal; konfirmasi selalu penting.  
- Fokus pada *proses membaca aliran niat*, bukan sekadar menebak harga.  
- Catat setiap eksperimen: data membentuk insting.
