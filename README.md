# Milestone 1 — EDA Breast Cancer Wisconsin (Diagnostic)

## Deskripsi
Proyek ini merupakan Milestone 1 mata kuliah Statistika & Probabilitas (Modul 9).  
Tujuan utamanya adalah menerapkan framework Exploratory Data Analysis (EDA) 7 langkah.

## Dataset
- Nama: Breast Cancer Wisconsin (Diagnostic)
- Kaggle: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
- Sumber asli: UCI Machine Learning Repository
- DOI: https://doi.org/10.24432/C5DW2B
- Lisensi sumber asli: CC BY 4.0
- Ukuran: 569 observasi, 30 fitur numerik
- Target: Benign / Malignant

Dataset memuat karakteristik inti sel yang dihitung dari citra digital fine needle aspirate (FNA) massa payudara.

## Cara Menjalankan
1. Upload notebook `M9-Milestone1-EDA-Breast-Cancer-Muhammad-Bintang-Satriaji.ipynb` ke Google Colab.
2. Pilih **Runtime → Run all**.
3. Tidak perlu upload CSV terpisah karena dataset dimuat dari packaged copy `sklearn.datasets.load_breast_cancer`.
4. Pastikan seluruh tabel, 6+ visualisasi, dan 2 chart Plotly muncul tanpa error.

## Framework EDA
1. Load & inspect
2. Missing values & duplicate
3. Central tendency
4. Dispersion
5. Univariate visualization
6. Bivariate visualization
7. Insight & report

## Ringkasan Insight
- Kelas terdiri dari 357 benign (62.7%) dan 212 malignant (37.3%).
- Mean radius malignant (~17.46) lebih tinggi daripada benign (~12.15).
- Mean area bersifat right-skewed, sehingga median/IQR penting sebagai ukuran robust.
- Fitur ukuran seperti radius, perimeter, dan area memiliki korelasi sangat tinggi.
- Mean concavity memiliki variasi relatif besar dan berpotensi menjadi fitur pembeda diagnosis.

## Hipotesis untuk Milestone 2
1. Mean `mean radius` berbeda signifikan antara malignant dan benign.
2. Mean `mean texture` berbeda signifikan antara malignant dan benign.
3. Mean `mean concavity` pada malignant lebih tinggi daripada benign.

## File
- `M9-Milestone1-EDA-Breast-Cancer-Muhammad-Bintang-Satriaji.ipynb`
- `M9-dashboard-preview.png`
