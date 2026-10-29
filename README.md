# 🍕 Pizza Sales Performance & Operational Analytics Dashboard

[![Looker Studio](https://img.shields.io/badge/Looker%20Studio-Live%20Dashboard-blue?logo=google)](LINK_DASHBOARD_LOOKER_STUDIO_KAMU)
[![Dataset](https://img.shields.io/badge/Dataset-Maven%20Analytics-green)](#about-the-dataset)
[![Status](https://img.shields.io/badge/Project%20Status-Completed-success)](#)

Interactive Business Intelligence dashboard yang dibangun menggunakan **Google Looker Studio** untuk mengevaluasi kinerja penjualan tahunan, mengidentifikasi pola jam sibuk operasional (*peak hours*), serta menganalisis kontribusi produk dan kategori menu pizza terhadap total pendapatan.

🔗 **[Klik di Sini untuk Mengakses Live Interactive Dashboard](LINK_DASHBOARD_LOOKER_STUDIO_KAMU)**

---

## 📌 Pratinjau Dashboard

<img width="487" height="377" alt="image" src="https://github.com/user-attachments/assets/d13f615e-34b6-4f03-b687-02964630f780" />


---

## 🎯 Latar Belakang & Pertanyaan Bisnis (Business Questions)

Manajemen restoran pizza membutuhkan visibilitas menyeluruh terhadap dinamika transaksi harian dan performa produk untuk menjawab 3 tantangan bisnis utama:

1. **Efisiensi Operasional & Tenaga Kerja:** Kapan jam sibuk (*rush hours*) terjadi, dan bagaimana restoran dapat menjadwalkan staf dapur serta kurir secara presisi untuk meminimalkan waktu tunggu (*turnaround time*)?
2. **Kinerja Produk & Risiko Portofolio:** Menu pizza mana yang menjadi motor utama pendapatan (*revenue driver*), dan apakah performa penjualan terlalu bergantung pada kategori tertentu?
3. **Peluang Monetisasi Jam Sepi:** Bagaimana struktur nilai pesanan rata-rata (*Average Order Value* / AOV) pelanggan, dan di rentang waktu mana terdapat kapasitas oven yang belum terutilisasi maksimal?

---

## 📊 Ringkasan Metrik Utama (Key Performance Indicators)

| Metrik KPI | Nilai | Penjelasan Bisnis |
| :--- | :---: | :--- |
| **Total Revenue** | **$817,860.05** | Total akumulasi pendapatan kotor sepanjang tahun berjalan |
| **Total Pizzas Sold** | **49,574** | Volume seluruh loyang pizza yang berhasil diproduksi dan terjual |
| **Total Orders** | **21,350** | Jumlah transaksi unik (*distinct order IDs*) yang tercatat |
| **Average Order Value (AOV)** | **$38.31** | Rata-rata nilai belanja per transaksi pelanggan (`Revenue / Orders`) |

> **Rasio Pembelian:** Dengan rasio sekitar **2.3 pizza per pesanan** ($49,574 / 21,350$), sebagian besar transaksi pelanggan merupakan pesanan multiproduk atau ukuran keluarga (*sharing meal*), bukan transaksi personal tunggal.

---

## 🔍 Temuan Utama & Storytelling Analisis

### 1. Pola Beban Operasional: Fenomena Jam Sibuk Ganda (*The Two-Rush Pattern*)
Distribusi volume pesanan per jam (*Peak Ordering Hours*) memperlihatkan siklus kerja yang konsisten setiap harinya:
* **Gelombang Makan Siang (*Lunch Rush*):** Lonjakan volume dimulai pukul 11:00 dan mencapai titik puncak pada pukul **12:00–13:00** (~2,500 pesanan per jam).
* **Fase Perlambatan (*Afternoon Dip*):** Terjadi penurunan aktivitas tajam antara pukul **14:00–16:00** (hanya sekitar 1,400 pesanan per jam).
* **Gelombang Makan Malam (*Dinner Rush*):** Beban kerja kembali melonjak stabil mulai pukul 16:00 hingga puncaknya pada pukul **17:00–18:00** sebelum melandai menjelang penutupan restoran di pukul 23:00.

### 2. Diversifikasi Kategori Produk yang Sehat (*Balanced Mix*)
Pangsa pasar pendapatan per kategori menunjukkan keseimbangan yang sangat kuat:
* **Classic:** 26.9% ($~220K)
* **Supreme:** 25.5% ($~208K)
* **Chicken:** 24.0% ($~196K)
* **Veggie:** 23.7% ($~193K)

*Insight:* Bisnis tidak rentan terhadap risiko konsentrasi produk (*single-point failure*). Minat konsumen terhadap kategori vegetarian (*Veggie*) hampir seimbang dengan kategori daging dan ayam, mengindikasikan segmen pelanggan yang beragam.

### 3. Varian Menu Andalan (*Top Revenue Drivers*)
Tiga varian pizza penyumbang omzet terbesar didominasi oleh olahan berbasis ayam:
1. **The Thai Chicken Pizza** — `$43,434.25`
2. **The Barbecue Chicken Pizza** — `$42,768.00`
3. **The California Chicken Pizza** — `$41,409.50`
4. **The Classic Deluxe Pizza** — `$38,180.50`
5. **The Spicy Italian Pizza** — `$34,831.25`

*Insight:* Bahan baku ayam olahan serta saus racikan khusus (*Thai & BBQ sauce*) merupakan aset paling bernilai di dapur yang wajib dijaga konsistensi rasa dan ketersediaannya.

---

## 💡 Rekomendasi Strategis (Actionable Recommendations)

1. **Optimasi Jadwal Kerja Staf (*Staggered Shift Scheduling*):**
   * Alokasikan kapasitas maksimal koki perakitan (*prep cook*) dan kurir pengantaran pada dua jendela waktu krusial: **11:30–13:30** dan **16:30–18:30**.
   * Gunakan sistem *split shift* atau pekerja paruh waktu di jam sibuk untuk mengendalikan biaya tenaga kerja tanpa mengorbankan kecepatan layanan.

2. **Monetisasi Waktu Sepi (*Off-Peak Revenue Generation*):**
   * Buat program promo khusus jam 14:00–16:00, seperti paket hemat *"Afternoon Pizza Slice & Drink Combo"*, untuk memacu utilisasi oven dan tenaga kerja dapur yang menganggur di sela jam makan utama.

3. **Manajemen Rantai Pasok Bahan Baku Utama (*Inventory Control*):**
   * Terapkan tingkat persediaan pengaman (*safety stock*) yang lebih ketat pada pasokan fillet ayam dan bahan baku pendukung menu *Thai Chicken* dan *BBQ Chicken* guna mencegah potensi kehilangan penjualan (*stockout*) saat lonjakan pesanan.

---

## 🛠️ Alat & Metodologi

* **Google Sheets / Microsoft Excel:** Pemeriksaan konsistensi data (*data cleaning*), standarisasi tipe data, dan validasi rekonsiliasi angka.
* **Google Looker Studio:** Desain visualisasi interaktif, implementasi *calculated fields*, integrasi *cross-filtering*, dan penataan tata letak bertema kartu analitik modern.

---

## 📂 Struktur Repository

```text
├── assets/
│   └── dashboard-preview.png     # Screenshot dashboard untuk dokumentasi
├── data/
│   └── pizza_sales_master.csv    # Dataset mentah transaksi penjualan
└── README.md                     # Dokumentasi studi kasus proyek
