Proyek ini merupakan bagian dari sertifikasi Intermediate Data Analysis. Analisis dilakukan menggunakan Python, Pandas, dan Matplotlib untuk mengidentifikasi tren penjualan, segmentasi pelanggan, dan strategi retensi pelanggan.

## 👤 Penulis
**Yulman Ndraha**

## 🛠 Tools
- Python
- Pandas
- Matplotlib / Seaborn (opsional)
- Jupyter Notebook

## 🗂 Dataset
Dataset yang digunakan berasal dari Kaggle:

> **Sales Transaction v.4a.csv**  
> [Link Kaggle Dataset](https://www.kaggle.com) *(https://www.kaggle.com/datasets/gabrielramos87/an-online-shop-business)*

Dataset ini berisi data transaksi penjualan lengkap dengan tanggal transaksi, produk, quantity, dan customer ID yang digunakan untuk melakukan analisis tren, segmentasi, dan retensi.

## 🎯 Tujuan Proyek
- Mengidentifikasi pola penjualan & tren waktu
- Menemukan produk dengan kontribusi tertinggi
- Menganalisis loyalitas & perilaku pembelian pelanggan
- Memberikan rekomendasi bisnis berbasis data

## 🔎 Fokus Analisis Bisnis
- **Tren penjualan sepanjang tahun**: memahami pola musiman dan momentum kampanye
- **Segmentasi pelanggan** berdasarkan profitabilitas dan retensi
- **Produk kontribusi terbesar**: prioritas promosi & stok
- **Perilaku transaksi pelanggan**: ukuran keranjang & kebiasaan belanja
- **Rekomendasi strategi** untuk meningkatkan performa penjualan menyeluruh

## 🧹 Data Cleaning
- Mengubah kolom tanggal ke format `datetime`
- Menghapus data retur (transaction no diawali “C”)
- Menghapus transaksi dengan quantity negatif
- Dataset siap digunakan untuk analisis lanjutan

## 📈 Analisis yang Dilakukan
- Tren penjualan harian & mingguan sepanjang tahun
- Distribusi produk berdasarkan segmentasi
- Perbandingan produk super populer per bulan (contoh: November vs Juli)
- Strategi retensi pelanggan: Segmentasi & Churn
- Analisis retensi pelanggan (Cohort Analysis)
- Segmentasi pelanggan (Frekuensi vs Revenue)
- Distribusi segmentasi pelanggan (Gold / Silver / Bronze)
- Produk favorit pelanggan Gold
- Price Sensitivity Analysis
- Basket Size Analysis (per hari, per minggu, per negara)

## 📝 Insight Utama
- Penjualan tertinggi terjadi pada kuartal keempat & meningkat signifikan menjelang akhir tahun  
- Pelanggan loyal masih terbatas, namun menunjukkan repeat order 2–4 kali  
- Produk kontribusi tertinggi cenderung barang kecil & dekoratif namun dinamis antar bulan  
- Rata-rata pelanggan membeli ±4 produk per transaksi → potensi peningkatan nilai keranjang belanja  
- Beberapa produk sangat sensitif terhadap harga → perlu pendekatan pricing selektif  
- 35% pelanggan hanya belanja 1x sepanjang tahun  
- Produk favorit pelanggan Gold dapat dijadikan andalan promosi bundling  
- Basket size bervariasi antar hari & negara  

## 💡 Rekomendasi Bisnis
- Tambahkan auto-prompt bundling di checkout  
- Gunakan bundling dinamis dari produk super populer  
- Berikan diskon weekday untuk produk sensitif harga  
- Jalankan campaign besar sejak Oktober (kuartal 4 fokus)  
- Terapkan program loyalitas berbasis frekuensi  
- Fokus pada pelanggan yang hanya beli 1x (34%) dengan promosi reaktivasi melalui email/push notif  
- Segmentasi pelanggan (Gold/Silver/Bronze) untuk membuat penawaran personalisasi  
- Perkuat strategi cohort untuk pelanggan baru  

## 📂 Struktur Repo
