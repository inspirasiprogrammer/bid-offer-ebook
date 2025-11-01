# 03 — Order Book (Kedalaman & Ketidakseimbangan)

## Depth & Imbalance
- **Depth Map**: jumlah lot pada setiap level harga.  
- **Imbalance**: (Σ lot bid top N) / (Σ lot offer top N). Nilai > 1 condong ke demand.

## Dinamika Penting
- **Refresh Liquidity**: lot di level yang “terisi” namun segera diisi ulang — tanda niat kuat.  
- **Hidden Liquidity**: eksekusi besar meski depth terlihat tipis — waspadai iceberg.

## Contoh Mini (Tabel)
| Level | Bid (Lot) | Harga | Offer (Lot) |
|------:|----------:|------:|------------:|
| 1     | 120,000   | 505   | 95,000      |
| 2     | 80,000    | 504   | 110,000     |
| 3     | 60,000    | 503   | 70,000      |

Imbalance top-3 ≈ (120+80+60)/(95+110+70)=260/275≈0.95 → netral-tipis.
