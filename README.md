# UAS Kecerdasan Buatan - Klasifikasi Penyakit Jantung

Proyek ini disusun untuk memenuhi syarat Ujian Akhir Semester (UAS) pada mata kuliah TIF701-Kecerdasan Buatan.

## Identitas Mahasiswa
* Nama : Irfan Tarwin Suryadi
* NIM : 312210311
* Kelas : TI.22.C.SE.1 
* Dosen Pengampu : Yogi Yulianto, M.Kom.

---

## Deskripsi Project
Project ini bertujuan untuk menerapkan konsep kecerdasan buatan dalam memprediksi risiko penyakit jantung berdasarkan data medis pasien. Studi kasus yang dipilih adalah **Supervised Learning (Classification)** dengan membandingkan performa dua model algoritma yang berbeda.

## Dataset
Dataset yang digunakan berasal dari **Kaggle**.
* **Link Dataset**: [Heart Disease Dataset - Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
* **File**: `heart.csv` 

## Tahapan Project
Sesuai dengan kriteria penilaian, project ini mencakup lima tahap utama.
1. **Exploratory Data Analysis (EDA)**: Visualisasi korelasi fitur dan distribusi target.
2. **Pre-processing Data**: Pembersihan data dan pembagian dataset (train-test split).
3. **Feature Engineering**: Standarisasi skala fitur menggunakan StandardScaler.
4. **Training Model & Perbandingan**: Implementasi model Logistic Regression dan Random Forest Classifier.
5. **Evaluasi & Analisis**: Penilaian akurasi menggunakan Classification Report dan Confusion Matrix.

## Teknologi yang Digunakan
* **Bahasa**: Python 
* **Platform**: Google Colab / Jupyter Notebook 
* **Library**: Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib.

## Struktur Folder
Penyusunan file dalam repository ini mengikuti standar berikut :
```text
📦 UAS AI
 ┣ 📜 README.md
 ┣ 📜 heart.csv
 ┗ 📜 uas-praktek.ipynb
