Prediksi Nilai Ekspor Produk Industri Kehutanan Indonesia
Repositori ini berisi implementasi model machine learning menggunakan metode Multiple Linear Regression untuk memprediksi nilai ekspor industri kehutanan di Indonesia. Proyek ini merupakan bagian dari penelitian skripsi yang menggunakan data historis tahun 2020-2024.

📊 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis pengaruh volume produksi bahan baku terhadap nilai ekspor industri kehutanan. Data yang digunakan berasal dari Direktorat Jenderal Pengelolaan Hutan Produksi Lestari, Kementerian Kehutanan.

Variabel Penelitian:
Target (y): Nilai Ekspor.

Fitur (X):

Kayu Bulat (Log)

Kayu Olahan

Hasil Hutan Bukan Kayu (HHBK)

Data waktu (Tahun & Bulan) serta Lokasi (Provinsi)

📁 Struktur File Jupyter
Notebook 202231059_Renata_Yasmine_Selomita_Aplikasi_Skripsi.ipynb mencakup langkah-langkah end-to-end sebagai berikut:

Data Loading & Transformation:

Mengimpor data dari format CSV.

Melakukan transformasi data dari format wide ke long format untuk mempermudah analisis time-series.

Data Preprocessing:

Penggabungan (Merging) dataset Ekspor, Kayu Bulat, Kayu Olahan, dan HHBK berdasarkan Provinsi dan Waktu.

Penanganan Missing Values menggunakan metode imputasi rata-rata per provinsi.

Encoding variabel kategorikal (Provinsi) dan penskalaan fitur menggunakan RobustScaler.

Exploratory Data Analysis (EDA):

Statistik deskriptif untuk setiap variabel.

Visualisasi distribusi data menggunakan histogram dan KDE plot.

Modeling:

Pembagian data menjadi Training set dan Testing set.

Penerapan algoritma LinearRegression melalui Scikit-Learn Pipeline.

Evaluation:

Mengukur performa model menggunakan metrik: R-Squared (R²), Mean Squared Error (MSE), dan Mean Absolute Error (MAE).

🛠️ Teknologi yang Digunakan
Bahasa: Python

Library Utama:

pandas & numpy (Manipulasi data)

matplotlib & seaborn (Visualisasi data)

scikit-learn (Modeling & Preprocessing)

🚀 Cara Menjalankan
Pastikan Anda memiliki Python terinstal (disarankan versi 3.8+).

Instal dependensi yang diperlukan:

Bash
pip install pandas numpy matplotlib seaborn scikit-learn
Buka file .ipynb di Google Colab atau Jupyter Notebook.

Sesuaikan path direktori data pada bagian base = "/content/drive/My Drive/SKRIPSI/" sesuai dengan lokasi file CSV Anda.

✒️ Penulis
Renata Yasmine Selomita
Peneliti / Mahasiswa Tingkat Akhir - Teknik Informatika
