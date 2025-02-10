# TUKUPOS Sales Analysis

Proyek ini berfokus pada analisis data penjualan dari perusahaan yang terdaftar di **TUKUPOS**, sebuah aplikasi manajemen UMKM yang dikembangkan oleh dosen **IT Telkom Purwokerto**, **Novian Adi Prasetyo, M.Kom** dan **Arief Rais Bahtiar, M.Kom**. Aplikasi ini bertujuan membantu pelaku UMKM di Purbalingga dalam mengelola keuangan dan penjualan secara digital dengan antarmuka yang **user-friendly** dan **terjangkau**.

## 📊 Deskripsi Proyek

Analisis ini bertujuan untuk:
- Mengidentifikasi tren penjualan dari data perusahaan UMKM.
- Menentukan produk terlaris dan waktu penjualan terbaik.
- Memberikan insight bagi UMKM untuk mengoptimalkan strategi bisnis mereka.

## 📈 Hasil Analisis Utama

1. **Analisis Deret Waktu (Time Series Analysis):**  
   - **Tren Penjualan:** Terjadi peningkatan penjualan yang signifikan dalam 6 bulan terakhir.
   - **Waktu Penjualan Terbaik:** Penjualan tertinggi terjadi pada akhir pekan, terutama hari **Sabtu**.
   - **Musiman:** Pola musiman menunjukkan lonjakan penjualan di awal bulan, berkaitan dengan periode gajian.

2. **Analisis Asosiasi dengan Algoritma Apriori:**  
   - **Produk Terlaris dan Kombinasi Penjualan:**  
     - Produk A dan Produk B sering dibeli bersamaan, dengan *confidence* sebesar **75%**.
     - Kombinasi **Produk C + Produk D** memiliki *support* tertinggi di kategori barang rumah tangga.
   - **Rekomendasi Bundling:** Berdasarkan hasil Apriori, disarankan untuk membuat paket penjualan antara **Produk A** dan **Produk B**.
  
## 🔒 Tentang Data
Data yang digunakan dalam proyek ini bersifat **sensitif** karena berkaitan dengan informasi penjualan perusahaan UMKM yang terdaftar di **TUKUPOS**. Oleh karena itu, data asli **tidak disertakan** dalam repository ini untuk menjaga privasi perusahaan terkait.

Jika Anda ingin menjalankan analisis ini dengan data sendiri, silakan gunakan format data serupa seperti yang dijelaskan di bagian di bawah ini.

