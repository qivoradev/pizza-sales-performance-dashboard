# Pizza Sales Performance & Operational Analytics Dashboard

![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)

Interactive Business Intelligence dashboard yang dibangun menggunakan **Google Looker Studio** untuk mengevaluasi kinerja penjualan tahunan, menganalisis pola operasional jam sibuk (*peak hours*), serta meninjau kontribusi menu dan kategori pizza terhadap total pendapatan.

> 🔗 **[Lihat Dashboard Interaktif di Looker Studio](https://datastudio.google.com/reporting/81574dad-5d2d-4a15-aafb-eefb54548a3e)**  
> 📊 **[Akses Dataset / Spreadsheet](https://docs.google.com/spreadsheets/d/1lT0tvBmZi7sswTzVoYQziJopoOdlBn5c/edit?usp=sharing&ouid=103313291434112811548&rtpof=true&sd=true)**

<img width="973" height="754" alt="image" src="https://github.com/user-attachments/assets/602f3dd5-3105-47c3-8ed8-61f90b9b8c90" />



---

## Ringkasan Proyek

Manajemen restoran memerlukan visibilitas menyeluruh terhadap dinamika transaksi harian dan performa produk untuk menjawab tiga tantangan bisnis utama:

1. **Efisiensi Operasional:** Mengetahui jam operasional tersibuk (*rush hours*) agar penjadwalan staf dapur dan kurir dapat disesuaikan untuk memangkas waktu tunggu pesanan.
2. **Kinerja Produk:** Mengidentifikasi varian menu penggerak utama omzet serta memastikan apakah portofolio menu memiliki ketergantungan berlebih pada kategori tertentu.
3. **Peluang Penjualan:** Menganalisis nilai rata-rata transaksi (*Average Order Value*) dan menemukan rentang waktu yang belum terutilisasi secara maksimal.

---

## Ringkasan Metrik Utama (KPI)

| Metrik Utama | Nilai | Keterangan |
| :--- | :---: | :--- |
| **Total Revenue** | **$817.860,05** | Total akumulasi omzet penjualan setahun penuh |
| **Total Pizzas Sold** | **49.574** | Total loyang pizza yang terjual |
| **Total Orders** | **21.350** | Jumlah transaksi unik yang tercatat |
| **Average Order Value (AOV)** | **$38,31** | Rata-rata nilai belanja per pesanan |

Dengan volume rata-rata sekitar **2,3 loyang per transaksi**, mayoritas pesanan pelanggan merupakan pesanan kelompok atau ukuran keluarga (*sharing meal*), bukan konsumsi personal tunggal.

---

## Temuan Utama (*Key Insights*)

### 1. Pola Jam Sibuk Operasional (*Peak Ordering Hours*)
Distribusi waktu transaksi memperlihatkan pola beban kerja ganda yang berulang setiap harinya:
- **Gelombang Makan Siang (*Lunch Rush*):** Lonjakan pesanan dimulai pukul **11.00** dan memuncak pada pukul **12.00–13.00** dengan volume mencapai sekitar **2.500 pesanan per jam**.
- **Penurunan Jam Sore (*Afternoon Dip*):** Aktivitas pesanan turun signifikan pada rentang **14.00–16.00** dengan rata-rata sekitar **1.400 pesanan per jam**.
- **Gelombang Makan Malam (*Dinner Rush*):** Pesanan kembali naik stabil mulai pukul **16.00** hingga puncaknya pada pukul **17.00–18.00**, lalu melandai menuju jam tutup operasional pukul **23.00**.

### 2. Distribusi Kategori Penjualan yang Seimbang
Portofolio penjualan menu terbagi sangat merata di keempat kategori utama:
- **Classic:** 26,9%
- **Supreme:** 25,5%
- **Chicken:** 24,0%
- **Veggie:** 23,7%

Keseimbangan ini menunjukkan diversifikasi menu yang sehat tanpa ketergantungan pada satu kategori saja. Kontribusi kategori vegetarian (**Veggie**) yang mendekati seperempat total omzet membuktikan adanya basis pelanggan kuat di luar menu olahan daging maupun ayam.

### 3. Dominasi Menu Ayam pada Pendapatan Tertinggi
Tiga posisi teratas penyumbang pendapatan terbesar seluruhnya ditempati varian berbahan dasar ayam. Ketersediaan bahan baku ayam olahan dan saus khusus (*Thai* dan *BBQ*) menjadi faktor krusial bagi stabilitas pendapatan restoran.

---

## Top 5 Varian Menu Terlaris (*by Revenue*)

| Peringkat | Varian Menu | Total Pendapatan |
| :---: | :--- | :---: |
| 1 | **The Thai Chicken Pizza** | $43.434,25 |
| 2 | **The Barbecue Chicken Pizza** | $42.768,00 |
| 3 | **The California Chicken Pizza** | $41.409,50 |
| 4 | **The Classic Deluxe Pizza** | $38.180,50 |
| 5 | **The Spicy Italian Pizza** | $34.831,25 |

---

## Rekomendasi Strategis

- **Penjadwalan Staf Bertahap (*Staggered Shift*):** Fokuskan kapasitas penuh koki dan staf perakitan pada jam **11.30–13.30** serta **16.30–18.30** untuk mempercepat pemrosesan pesanan di jam sibuk.
- **Utilisasi Jam Sepi (*Afternoon Dip*):** Hadirkan promosi paket hemat personal atau *bundling* pizza *slice* dan minuman pada pukul **14.00–16.00** agar kapasitas oven tetap produktif di luar jam makan utama.
- **Pengamanan Pasokan Bahan Baku:** Terapkan batas aman stok (*safety stock*) lebih ketat untuk fillet ayam dan saus utama (*Thai* & *BBQ*) guna mencegah risiko kehabisan stok saat *rush hour*.

---

## Alur Kerja & Alat yang Digunakan

1. **Microsoft Excel / Google Sheets:** Pembersihan data (*data cleaning*), standarisasi tipe data, serta validasi dan rekonsiliasi angka.
2. **Google Looker Studio:** Perancangan dashboard interaktif, pembuatan visualisasi data, *calculated fields*, dan kontrol filter dinamis.

---

## Kontak

**Iqbal Dwi Fathonah**  
- Portfolio: [portobyiqbaldwifathonah.vercel.app](https://portobyiqbaldwifathonah.vercel.app/)  
- GitHub: [github.com/qivoradev](https://github.com/qivoradev)  
- Email: iqbalfathonah20@gmail.com
