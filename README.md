# 🌲 Analisis Data Karhutla: Progres Penanganan & Kapasitas Pemadaman per Provinsi

Proyek analisis data ini mengevaluasi kinerja penanganan kebakaran hutan dan lahan (karhutla) serta kesiapan kapasitas operasional (personel, armada darat, dan armada udara) di 6 provinsi prioritas rawan karhutla di Indonesia berdasarkan data laporan BNPB per 16 Oktober 2026.

---

## 📌 Ringkasan Masalah & Pertanyaan Analisis

1. **Provinsi mana yang paling tertinggal dalam progres pemadaman lahan harian?**
2. **Bagaimana distribusi beban kebakaran (*hotspot* & *fire spot*) terhadap kapasitas personel dan armada penanganan di masing-masing provinsi?**
3. **Kendala operasional apa saja yang dilaporkan di lapangan yang berpotensi menghambat pemadaman?**

---

## 📊 Sumber Data & Cakupan

- **Sumber Data:** Badan Nasional Penanggulangan Bencana (BNPB), laporan situasi karhutla per 16 Oktober 2026 (sebagian narasi lapangan merujuk ke data 14–15 Oktober).
- **Cakupan Wilayah:** 6 Provinsi (Riau, Jambi, Sumatera Selatan, Kalimantan Barat, Kalimantan Tengah, Kalimantan Selatan).
- **Karakteristik Data:** Potret satu hari (*cross-sectional snapshot*), bukan analisis tren berkala (*time-series*).

---

## 📁 Struktur File & Direktori

```text
├── karhutla_analysis.ipynb          # Notebook analisis utama (data cleaning, metrik, visualisasi)
├── karhutla-2026_semua-provinsi.csv # Dataset mentah dari BNPB (45 kolom)
├── karhutla_clean.csv               # Dataset hasil pembersihan (21 kolom inti)
├── karhutla_metrik.csv              # Metrik rasio beban, kapasitas personel & armada
├── karhutla_kendala.csv             # Ekstraksi kendala & rekomendasi lapangan
├── karhutla_progres_penanganan.csv  # Tabel akhir rekap progres pemadaman per provinsi
└── README.md                        # Dokumentasi proyek
