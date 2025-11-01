# 02 — Bid–Offer (Membaca Sisi Harga)

## Sinyal Dasar
- **Best Bid naik** berulang: demand agresif meningkat.  
- **Best Offer turun** berulang: supply agresif menekan.  
- **Spread mengecil**: harga siap bergerak; volatilitas mikro bisa meningkat.

## Red Flag Umum
- **Spoofing/Fake Bid**: lot besar muncul-hilang memancing reaksi. Catat *durasi kemunculan*.  
- **Ping Order**: lot kecil-kecil “menguji” likuiditas tersembunyi.

## Metode Observasi
- Catat *rate of change* best bid/offer.  
- Hitung rasio saldo lot bid vs offer (top N level).  
- Monitor transaksi yang mengeksekusi di *ask* (tanda buyer agresif) vs di *bid* (seller agresif).
