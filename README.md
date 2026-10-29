# Pizza Sales Performance and Operational Analytics Dashboard

Interactive Business Intelligence dashboard yang dibangun menggunakan Google Looker Studio untuk mengevaluasi kinerja penjualan tahunan, menganalisis pola operasional jam sibuk (peak hours), serta meninjau kontribusi menu dan kategori pizza terhadap total pendapatan.

Link Dashboard Interaktif: https://datastudio.google.com/reporting/81574dad-5d2d-4a15-aafb-eefb54548a3e


<img width="487" height="377" alt="image" src="https://github.com/user-attachments/assets/3796a228-1677-4d5c-8af4-a43cbd412148" />



## Latar Belakang dan Pertanyaan Bisnis

Manajemen restoran memerlukan visibilitas menyeluruh terhadap dinamika transaksi harian dan performa produk untuk menjawab beberapa tantangan bisnis:

* Efisiensi Operasional: Mengetahui jam operasional tersibuk (rush hours) agar penjadwalan staf dapur dan kurir dapat disesuaikan untuk memangkas waktu tunggu pesanan.
* Kinerja Produk: Mengetahui varian menu yang menjadi penggerak utama omzet dan memastikan apakah portofolio menu memiliki ketergantungan pada kategori tertentu.
* Peluang Penjualan: Menganalisis nilai rata-rata transaksi (Average Order Value) serta mengidentifikasi rentang waktu yang belum terutilisasi maksimal.

## Ringkasan Metrik Utama

Berdasarkan data operasional setahun penuh, berikut ringkasan metrik performa utama:

* Total Revenue: $817.860,05 (total akumulasi omzet penjualan)
* Total Pizzas Sold: 49.574 loyang pizza terjual
* Total Orders: 21.350 transaksi unik
* Average Order Value (AOV): $38,31 per pesanan

Dengan rata-rata volume sekitar 2,3 loyang per transaksi, mayoritas pesanan pelanggan merupakan pesanan kelompok atau ukuran keluarga (sharing meal), bukan konsumsi personal tunggal.

## Analisis dan Insight Bisnis

### Pola Jam Sibuk Operasional (Peak Ordering Hours)

Distribusi waktu transaksi memperlihatkan pola beban kerja ganda yang berulang setiap harinya:

* Gelombang Makan Siang (Lunch Rush): Lonjakan pesanan dimulai pukul 11.00 dan memuncak pada pukul 12.00–13.00 dengan volume mencapai sekitar 2.500 pesanan per jam.
* Penurunan Jam Sore (Afternoon Dip): Aktivitas pesanan mengalami penurunan signifikan pada rentang waktu 14.00–16.00 dengan rata-rata 1.400 pesanan per jam.
* Gelombang Makan Malam (Dinner Rush): Pesanan kembali meningkat stabil mulai pukul 16.00 hingga puncaknya pada pukul 17.00–18.00 sebelum akhirnya melandai menuju jam tutup operasional di pukul 23.00.

### Distribusi Kategori Penjualan

Portofolio penjualan menu terbagi sangat seimbang di seluruh kategori:

* Classic: 26,9%
* Supreme: 25,5%
* Chicken: 24,0%
* Veggie: 23,7%

Keseimbangan ini menunjukkan diversifikasi menu yang sehat dan bisnis tidak bertumpu pada satu kategori saja. Permintaan pada kategori vegetarian (Veggie) yang mencapai hampir seperempat total omzet membuktikan adanya basis pelanggan yang kuat di luar menu olahan daging atau ayam.

### Varian Menu Terlaris (Top 5 by Revenue)

Varian dengan kontribusi omzet terbesar didominasi oleh menu berbahan dasar ayam:

1. The Thai Chicken Pizza: $43.434,25
2. The Barbecue Chicken Pizza: $42.768,00
3. The California Chicken Pizza: $41.409,50
4. The Classic Deluxe Pizza: $38.180,50
5. The Spicy Italian Pizza: $34.831,25

Bahan baku ayam olahan dan saus khusus (Thai dan BBQ) memegang peranan krusial terhadap stabilitas pendapatan restoran sehingga kontinuitas pasokannya perlu diprioritaskan.

## Rekomendasi Strategis

* Penjadwalan Staf Bertahap (Staggered Shift): Fokuskan kapasitas penuh koki dan staf perakitan di jam 11.30–13.30 dan 16.30–18.30 untuk mempercepat pemrosesan pesanan di jam sibuk.
* Utilisasi Jam Sepi: Buat promosi paket hemat personal atau pizza slice dan minuman di rentang jam 14.00–16.00 untuk mengoptimalkan penggunaan oven di luar jam makan utama.
* Pengamanan Pasokan Bahan Baku: Terapkan batas aman stok yang lebih ketat untuk pasokan fillet ayam dan bumbu saus utama guna mencegah risiko kehabisan bahan saat jam sibuk.

## Alat yang Digunakan

* Microsoft Excel / Google Sheets: Pembersihan data, standarisasi tipe data, dan validasi rekonsiliasi angka.
* Google Looker Studio: Desain dashboard interaktif, pembuatan visualisasi data, calculated fields, dan filter interaktif.

