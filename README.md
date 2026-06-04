# CREDORA Lite — DSR Calculator

> Alat pengiraan Debt Service Ratio (DSR) percuma untuk penilaian awal kelayakan pembiayaan.

![Version](https://img.shields.io/badge/version-1.0.0-B6FF00?style=flat-square&labelColor=111214)
![License](https://img.shields.io/badge/license-MIT-B6FF00?style=flat-square&labelColor=111214)
![HTML](https://img.shields.io/badge/built%20with-HTML%20%2F%20CSS%20%2F%20JS-B6FF00?style=flat-square&labelColor=111214)

---

## 🔗 Live Demo

**[credora-lite.github.io/credora-lite](https://github.io)**

---

## Tentang CREDORA Lite

CREDORA Lite adalah versi ringan dan percuma daripada **CREDORA** — platform analisis kredit institusi untuk institusi kewangan Malaysia. Versi Lite ini direka khas untuk:

- Pegawai kredit yang ingin semak DSR dengan cepat
- Penasihat kewangan yang memerlukan alat penilaian awal
- Orang awam yang ingin tahu kelayakan pembiayaan mereka

Tiada backend. Tiada login. Tiada data dihantar ke mana-mana server. **100% berjalan dalam browser anda.**

---

## Ciri-ciri

### DSR Analyser
- Input jumlah komitmen bulanan dan pendapatan kasar
- Pengiraan DSR secara langsung (live update)
- Gauge bar visual dengan marker threshold
- Verdict automatik — **PASS / CAUTION / FAIL**
- Commentary analisis dalam Bahasa Melayu

### Threshold Config
- 4 preset threshold — DSR 60%, NDR 70%, Penjawat Awam 75%, BLR 80%
- Custom threshold via range slider (30% – 95%)
- Toggle pilihan paparan — commentary, gauge bar, auto-save
- Konfigurasi disimpan secara kekal dalam browser

### History
- Rekod automatik setiap analisis yang dijalankan
- Statistik — jumlah Pass / Caution / Fail
- Padam rekod individu atau kosongkan semua
- Data disimpan dalam `localStorage` — kekal walaupun browser ditutup

---

## Formula DSR

```
DSR (%) = (Jumlah Komitmen Bulanan ÷ Jumlah Pendapatan Kasar) × 100
```

| DSR | Status |
|-----|--------|
| ≤ 85% daripada threshold | ✅ PASS |
| 85% – 100% daripada threshold | ⚠️ CAUTION |
| > threshold | ❌ FAIL |

*Contoh: Threshold 60% → PASS jika DSR ≤ 51%, CAUTION jika 51%–60%, FAIL jika > 60%*

---

## Cara Guna

Tiada installation diperlukan. Dua cara:

**1. Guna terus online (GitHub Pages)**
```
https://[username].github.io/credora-lite/
```

**2. Download dan buka secara tempatan**
```
1. Download fail index.html
2. Double-click untuk buka dalam browser
3. Siap — berfungsi 100% offline
```

---

## Teknologi

- **HTML5 / CSS3 / Vanilla JavaScript** — tiada framework
- **Google Fonts** — Syne, Inter, IBM Plex Mono
- **localStorage** — simpan history dan konfigurasi
- Tiada dependency luaran, tiada npm, tiada build step

---

## Had Penggunaan

> ⚠️ CREDORA Lite adalah untuk **penilaian awal sahaja**.
> Keputusan yang dipaparkan **bukan keputusan kredit rasmi**.
> Sila rujuk pegawai kredit bank untuk keputusan muktamad.

---

## Lesen

MIT License — bebas guna, ubah suai, dan edarkan semula.

---

## Berkaitan

CREDORA (versi penuh) adalah platform underwriting institusi dengan:
- Enjin analisis kredit multi-faktor
- Penilaian DSR, NDI, dan Survivability
- Simulasi What-If dan Debt Consolidation
- Laporan kredit automatik
- Sistem audit log

*Untuk maklumat lanjut tentang CREDORA versi penuh, hubungi pembangun.*

---

<div align="center">
  <sub>Dibina dengan ❤️ untuk institusi kewangan Malaysia</sub>
</div>
