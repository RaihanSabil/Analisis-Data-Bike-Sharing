# Analisis-Data-Bike-Sharing

# Ringkasan Proyek (Overview)
Proyek ini merupakan analisis data eksplorasi (Exploratory Data Analysis - EDA) pada dataset **Bike Sharing**. Tujuan utama dari proyek ini adalah untuk memahami faktor-faktor yang memengaruhi jumlah penyewaan sepeda dan menemukan pola-pola menarik dari data.

Analisis ini menggali bagaimana variabel seperti musim, cuaca, hari libur, dan jam dalam sehari berpengaruh terhadap permintaan penyewaan sepeda. Wawasan (insight) yang dihasilkan dapat menjadi dasar bagi pengambilan keputusan strategis dalam bisnis penyewaan sepeda, seperti perencanaan alokasi sepeda, strategi pemasaran musiman, dan penentuan jam operasional.

Proyek ini dibuat sebagai bagian dari portofolio data analisis saya.

# Pertanyaan Bisnis (Business Questions)
Analisis ini berfokus untuk menjawab pertanyaan-pertanyaan berikut:

1. Bagaimana pengaruh musim (season) terhadap jumlah total sewa sepeda harian?

2. Bagaimana pola penyewaan sepeda per jam dalam sehari, dan apakah ada perbedaan signifikan antara hari kerja (weekday) dan akhir pekan (weekend)?

Dataset
Dataset yang digunakan dalam proyek ini adalah **"Bike Sharing Dataset"** yang berisi data penyewaan sepeda harian dan per jam dari tahun 2011 hingga 2012 pada sistem Capital Bikeshare di Washington D.C., AS.

Sumber Dataset: UCI Machine Learning Repository

# Metode Analisis
Analisis dilakukan melalui beberapa tahapan utama:

**Data Wrangling:** Mengumpulkan, menilai, dan membersihkan data untuk memastikan kualitas dan konsistensi sebelum dianalisis.

**Exploratory Data Analysis (EDA):** Melakukan eksplorasi data untuk mengidentifikasi tren, pola, dan anomali.

**Visualisasi Data:** Membuat berbagai jenis plot dan grafik untuk menjawab pertanyaan bisnis dan menyajikan temuan secara efektif dan mudah dipahami.

# Hasil dan Temuan (Key Findings)
Berdasarkan analisis yang telah dilakukan, ditemukan beberapa wawasan penting:

1. **Pengaruh Musim:** Jumlah penyewaan sepeda tertinggi terjadi pada **Musim Gugur (Fall)**, diikuti oleh Musim Panas dan Musim Dingin. Jumlah penyewaan terendah tercatat pada Musim Semi (Spring).

2. **Pola Penyewaan Harian:** Terdapat perbedaan pola penyewaan yang jelas antara hari kerja dan akhir pekan.

   - **Hari Kerja:** Puncak penyewaan terjadi pada jam-jam sibuk komuter, yaitu pagi hari (sekitar pukul 08:00) dan sore hari (sekitar pukul 17:00-18:00).

   - **Akhir Pekan:** Puncak penyewaan terjadi lebih landai sepanjang siang hingga sore hari (sekitar pukul 10:00-18:00), yang mengindikasikan penggunaan untuk tujuan rekreasi.

# Teknologi yang Digunakan
- **Python**

- **Pandas** (untuk manipulasi dan analisis data)

- **Matplotlib & Seaborn** (untuk visualisasi data)

- **Jupyter Notebook** (sebagai lingkungan kerja)

# Cara Menjalankan Proyek
Untuk menjalankan notebook analisis ini di lingkungan lokal Anda, ikuti langkah-langkah berikut:

1. **Clone repositori ini:**

Bash

git clone https://github.com/[Username-Anda]/[Nama-Repo-Anda].git

2. **Pindah ke direktori proyek:**

Bash

cd [Nama-Repo-Anda]

3. **Install library yang dibutuhkan:**

Bash

pip install pandas matplotlib seaborn jupyter

4. **Jalankan Jupyter Notebook:**
Bash

jupyter notebook

5. Buka file Proyek_Analisis_Data.ipynb dan jalankan sel-sel di dalamnya.

