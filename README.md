# TUKUPOS Sales Analysis

Proyek ini berfokus pada analisis data penjualan dari perusahaan yang terdaftar di **TUKUPOS**, sebuah aplikasi manajemen UMKM yang dikembangkan oleh dosen **Telkom University Purwokerto**, **Novian Adi Prasetyo, M.Kom** dan **Arief Rais Bahtiar, M.Kom**. Aplikasi ini bertujuan membantu pelaku UMKM di Purbalingga dalam mengelola keuangan dan penjualan secara digital dengan antarmuka yang **user-friendly** dan **terjangkau**.

## 📊 Deskripsi Proyek

Analisis ini bertujuan untuk:
- Mengidentifikasi tren penjualan dari data perusahaan UMKM.
- Menentukan produk terlaris dan waktu penjualan terbaik.
- Memberikan insight bagi UMKM untuk mengoptimalkan strategi bisnis mereka.

## 📈 Hasil Analisis Utama

1. **Analisis Deret Waktu (Time Series Analysis):**  
   - **Tren Penjualan:** Tidak terdapat peningkatan penjualan.
   - **Waktu Penjualan Terbaik:** Penjualan tertinggi terjadi pada hari **Jumat**.

2. **Analisis Asosiasi dengan Algoritma Apriori:**  
   - **Produk Terlaris dan Kombinasi Penjualan:**  
     - Produk A dan Produk B sering dibeli bersamaan
     - Kombinasi **Produk C + Produk D** memiliki *support* tertinggi di kategori barang rumah tangga.
   - **Rekomendasi Bundling:** Berdasarkan hasil Apriori, disarankan untuk membuat paket penjualan antara **Produk A** dan **Produk B**.
  
## 🔒 Tentang Data
Data yang digunakan dalam analisis ini memiliki format sebagai berikut:

| ID  | Tanggal     | Trans ID  | Konsumen     | Nama Produk  | Kategori        | Qty  |
|-----|-------------|-----------|--------------|--------------|-----------------|------|
| 1   | 2023-01-01  | TRX001    | Konsumen A   | Produk A     | Minuman         | 2    |
| 2   | 2023-01-01  | TRX002    | Konsumen B   | Produk B     | Makanan Ringan  | 1    |
| 3   | 2023-01-02  | TRX003    | Konsumen C   | Produk A     | Minuman         | 3    |
| 4   | 2023-01-02  | TRX004    | Konsumen D   | Produk C     | Alat Rumah Tangga | 1  |
| 5   | 2023-01-03  | TRX005    | Konsumen E   | Produk B     | Makanan Ringan  | 4    |

### Penjelasan Kolom:
- **ID:** Nomor urut data.
- **Tanggal:** Tanggal transaksi dilakukan.
- **Trans ID:** ID unik untuk setiap transaksi.
- **Konsumen:** Nama atau identitas konsumen.
- **Nama Produk:** Produk yang dibeli dalam transaksi.
- **Kategori:** Kategori produk (misalnya Minuman, Makanan Ringan, Alat Rumah Tangga, dll).
- **Qty:** Jumlah produk yang dibeli.

Data asli **tidak disertakan** dalam repository ini karena alasan privasi. Anda dapat menggunakan data dengan format serupa untuk menjalankan analisis.

