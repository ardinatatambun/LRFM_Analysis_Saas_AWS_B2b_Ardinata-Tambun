 **Identifying Customer Segmentation for Business Optimization**  
oleh: Ardinata Tambun

## 📌 Tujuan Proyek
Proyek ini bertujuan untuk:
- Mengidentifikasi pengelompokan pelanggan menggunakan metode analisis **LRFM (Length, Recency, Frequency, Monetary)**.
- Mengklasifikasikan pelanggan ke dalam segmen strategis untuk mendukung keputusan bisnis berbasis data.
- Memberikan **insight yang dapat ditindaklanjuti** guna menyusun strategi pertumbuhan berdasarkan perilaku pelanggan.

## 🏢 Konteks Bisnis
Perusahaan berbasis **SaaS (Software as a Service)** ingin memahami pola perilaku pelanggan B2B-nya agar dapat:
- Meningkatkan **retensi pelanggan**.
- Meningkatkan **kualitas layanan**.
- Menyusun strategi **berbasis segmentasi pelanggan**.

## 📊 Dataset
Dataset mencakup informasi penting seperti:
- Produk dan tanggal pemesanan.
- Data pelanggan, lokasi (negara, kota, region).
- Kategori industri dan segmen pasar.
- Data transaksi: jumlah penjualan, diskon, kuantitas, dan profit.

## 🧪 Langkah Analisis
1. **Eksplorasi dan Pembersihan Data**: 
   - Visualisasi distribusi sales dan profit.
   - Deteksi outlier dan missing values.
2. **Perhitungan Skor LRFM**:
   - Menghitung Length, Recency, Frequency, dan Monetary.
   - Skoring dan normalisasi.
3. **Segmentasi Pelanggan**:
   - Pengelompokan pelanggan menggunakan teknik clustering (k-means, dsb).
   - Analisis tiap segmen secara deskriptif.

## 📈 Insight & Rekomendasi
Notebook menghasilkan beberapa insight seperti:
- Segmen pelanggan mana yang menghasilkan profit tertinggi.
- Strategi berbeda untuk pelanggan loyal vs pelanggan yang hampir hilang.

## 🧩 Tools & Library
- Python: Pandas, NumPy, Matplotlib, Seaborn
- Algoritma: LRFM, K-means (jika digunakan)
- Jupyter Notebook

## ✅ Hasil
Proyek ini memberikan dasar segmentasi yang kuat bagi perusahaan untuk:
- Menargetkan kampanye pemasaran secara efektif.
- Meningkatkan customer experience dan profitabilitas.

## 📂 Struktur File
- `Capstone_Module_2_Ardinata_Tambun.ipynb`: Notebook utama berisi proses analisis end-to-end.
- `SaaS-Sales.csv`: Dataset yang digunakan (harus disediakan di direktori yang sama).
