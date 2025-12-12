# 🧠 Machine Learning Portfolio: Clustering & Classification

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange?style=flat&logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Learning-green)

Repository ini berisi dokumentasi dan kode implementasi saya dalam
mempelajari algoritma Machine Learning, berfokus pada **Clustering
(Unsupervised Learning)** dan **Classification (Supervised Learning)**.

Project ini dibuat untuk memahami bagaimana mesin mengelompokkan data
tanpa label dan memprediksi data berdasarkan label yang sudah ada.

## 📋 Daftar Isi

-   Konsep Dasar
-   Algoritma yang Digunakan
-   Struktur Project
-   Cara Menjalankan
-   Hasil & Visualisasi
-   Dataset

## 💡 Konsep Dasar

Dalam repository ini, saya membandingkan dua pendekatan utama dalam
Machine Learning:

1.  **Unsupervised Learning (Clustering)**
    -   Data tidak memiliki label/target.
    -   Tujuan: Menemukan pola tersembunyi atau pengelompokan alami
        dalam data.
2.  **Supervised Learning (Classification)**
    -   Data memiliki label/target yang jelas.
    -   Tujuan: Melatih model untuk memprediksi kelas/kategori dari data
        baru.

## 🛠 Algoritma yang Digunakan

### 1. K-Means Clustering

Algoritma clustering iteratif yang mempartisi dataset ke dalam **K**
kelompok (*cluster*) yang berbeda.

**Metode Evaluasi:** - Elbow Method - Silhouette Score

**Studi Kasus:** Segmentasi Pelanggan Mall

### 2. Decision Tree

Model prediksi yang memecah data menjadi himpunan bagian lebih kecil
menggunakan aturan keputusan (If-Else).

-   Kelebihan: Mudah diinterpretasikan
-   Kekurangan: Cenderung overfitting

### 3. Random Forest

Metode *Ensemble Learning* yang membangun banyak Decision Tree untuk
hasil yang lebih akurat dan stabil.

## 📂 Struktur Project

    ├── data/
    │   ├── raw/
    │   └── processed/
    ├── notebooks/
    │   ├── 1_KMeans_Clustering.ipynb
    │   ├── 2_Decision_Tree.ipynb
    │   └── 3_Random_Forest.ipynb
    ├── images/
    ├── requirements.txt
    └── README.md

## 🚀 Cara Menjalankan

1.  Clone repository:

```{=html}
<!-- -->
```
    git clone https://github.com/username-anda/repo-belajar-ml.git
    cd repo-belajar-ml

2.  Install library:

```{=html}
<!-- -->
```
    pip install -r requirements.txt

3.  Jalankan Notebook:

```{=html}
<!-- -->
```
    jupyter notebook

## 📊 Hasil & Visualisasi

### K-Means -- Elbow Method

*(Tempatkan gambar plot di folder `images/`)*

### Perbandingan Akurasi

  Model           Akurasi   Precision   Recall
  --------------- --------- ----------- --------
  Decision Tree   85%       0.84        0.86
  Random Forest   92%       0.91        0.93

## 💾 Dataset

Dataset berasal dari: - Kaggle - UCI Machine Learning Repository

## 🤝 Contact

Dibuat oleh **Nama Anda**.
