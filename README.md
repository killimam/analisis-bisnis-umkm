[README.md](https://github.com/user-attachments/files/28233791/README.md)
# Analisis Kelayakan Bisnis — Tools UMKM Indonesia

> Kalkulator kelayakan usaha berbasis web dengan analisis AI, dirancang khusus untuk pelaku UMKM di Indonesia.

 **Live Demo:** [killimam.github.io/analisis-bisnis-umkm](https://killimam.github.io/analisis-bisnis-umkm)

---

## Fitur

| Fitur | Deskripsi |
|-------|-----------|
| **BEP (Break Even Point)** | Hitung titik impas dalam satuan unit maupun rupiah |
| **Proyeksi Laba/Rugi** | Tabel arus kas bulanan hingga 36 bulan ke depan |
| **ROI & Payback Period** | Return on Investment tahunan & estimasi waktu balik modal |
| **Arus Kas (Cash Flow)** | Visualisasi kumulatif surplus/defisit per bulan |
| **Analisis AI (Claude)** | Rekomendasi bisnis otomatis dalam Bahasa Indonesia |

---

## Cara Pakai

Tidak perlu instalasi. Buka langsung di browser:

1. Kunjungi link demo di atas, **atau**
2. Download file `analisis-bisnis.html` → buka di browser

### Input yang dibutuhkan:
- Modal awal
- Biaya tetap per bulan (sewa, gaji, listrik, dll.)
- Biaya variabel per unit (bahan baku, ongkir, dll.)
- Harga jual per unit
- Estimasi penjualan per bulan
- Durasi proyeksi (bulan)

---

## Teknologi

- **HTML / CSS / JavaScript** — murni vanilla, tanpa framework
- **Claude API (Anthropic)** — untuk analisis bisnis berbasis AI
- **Google Fonts** — Syne + DM Sans + DM Mono
- **GitHub Pages** — hosting gratis

---

## Deploy ke GitHub Pages

```bash
# 1. Clone atau buat repo baru
git init
git add analisis-bisnis.html README.md
git commit -m "first commit: analisis kelayakan bisnis UMKM"

# 2. Push ke GitHub
git remote add origin https://github.com/killimam/analisis-bisnis-umkm.git
git push -u origin main

# 3. Aktifkan GitHub Pages
# Settings → Pages → Source: Deploy from branch → main → Save
```

Setelah beberapa menit, aplikasi bisa diakses di:
`https://killimam.github.io/analisis-bisnis-umkm`

---

## Formula yang Digunakan

```
Margin per Unit     = Harga Jual - Biaya Variabel/Unit
BEP (Unit)          = Biaya Tetap / Margin per Unit
BEP (Rupiah)        = BEP Unit × Harga Jual
Laba Bersih/Bulan   = Pendapatan - (Biaya Tetap + Biaya Variabel Total)
ROI Tahunan         = (Laba Bersih × 12) / Modal × 100%
Payback Period      = Modal Awal / Laba Bersih per Bulan
```

---

## Kontribusi

Pull request terbuka! Beberapa ide pengembangan:

- [ ] Grafik/chart visual arus kas
- [ ] Export hasil ke PDF
- [ ] Fitur simpan & bandingkan skenario
- [ ] Mode multi-produk
- [ ] Kalkulasi pajak UMKM (PPh Final 0.5%)

---

## Lisensi

MIT License — bebas digunakan dan dimodifikasi.

---

<p align="center">Dibuat dengan ❤️ untuk UMKM Indonesia · Powered by <a href="https://anthropic.com">Claude AI</a></p>
