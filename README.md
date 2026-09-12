Mushroom Classification Project 🍄

Repositori ini berisi proyek Machine Learning untuk melakukan klasifikasi jamur (apakah dapat dimakan/edible atau beracun/poisonous) berdasarkan karakteristik fisik dan morfologinya. Proyek ini dikerjakan sebagai bagian dari Take-Home Challenge Machine Learning.

📋 Daftar Isi
 1. Overview Proyek
 2. Sumber Dataset
 3. Struktur Repository
 4. Metodologi & Tahapan Pengerjaan
    • Problem Definition & Data
    • Problem Definition & Data   Understanding
    • EDA & Visualization
    • Data Preprocessing
    • Classification Model Development
    • Model Evaluation & Comparison
    • Deep Learning Implementation
    • Hyperparameter Tuning & Model Interpretation
    • Regression Exploration
    • Analysis & Final Insight
    
  5. Kesimpulan (Conclusion)

🌟 Overview Proyek
Masalah utama dalam keamanan pangan terkait jamur liar adalah membedakan antara jamur yang aman dikonsumsi (edible) dan jamur yang beracun (poisonous). Proyek ini membangun sistem prediktif menggunakan teknik Machine Learning dan Deep Learning untuk mengotomatisasi proses identifikasi berdasarkan atribut fisik jamur, sehingga dapat membantu meminimalkan risiko keracunan fatal

📊 Sumber Dataset
Dataset yang digunakan dalam proyek ini diperoleh dari Kaggle:
Nama Dataset: Mushroom Classification
Tautan Dataset: Kaggle - Mushroom Classification Dataset

Catatan: Peserta bertanggung jawab penuh untuk mencantumkan sumber dataset dengan benar serta memperhatikan ketentuan penggunaan dan hak cipta yang berlaku.

📂 Struktur Repository
Struktur direktori repository ini diatur sebagai berikut:

Mushroom-Classification/
│
├── data/
│   └── mushrooms.csv
│
├── notebook/
│   └── Nama_NIM_TakeHomeML.ipynb
│
└── README.md

🛠️ Metodologi & Tahapan Pengerjaan
1. Problem Definition & Data Understanding
• Definisi Masalah: Menentukan tujuan bisnis/analitis, yaitu memprediksi kelas jamur secara akurat untuk mencegah kesalahan konsumsi.
• Pemahaman Data: Memeriksa ukuran dataset, tipe data dari setiap kolom (fitur kategorikal/numerik), serta mendeteksi ada atau tidaknya missing values.

2. EDA & Visualization
• Melakukan analisis eksploratif untuk melihat distribusi kelas target (edible vs poisonous).
• Membuat visualisasi data (seperti countplot, barplot) untuk melihat korelasi antara fitur fisik (bentuk tudung, warna, bau) dengan kelas jamur.
• (Opsional Bonus) Melakukan visualisasi PCA 2D untuk pemisahan kelas.

3. Data Preprocessing
• Penanganan nilai kosong (missing values) jika ada.
• Encoding fitur kategorikal (menggunakan Label Encoding atau One-Hot Encoding) karena algoritma machine learning memerlukan input numerik.
• Pembagian data (Train-Test Split) dengan proporsi yang sesuai.
