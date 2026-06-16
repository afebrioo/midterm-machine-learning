# Replikasi Statistika Praktis untuk Data Science

| Identitas | Detail |
| :--- | :--- |
| **Nama** | Rahmanda Afebrio Yuris Soesatyo |
| **NIM** | 1103223024 |

Repositori ini dibuat untuk mereplikasi kode program, ringkasan, dan penjelasan teoritis dari buku acuan statistika data science populer:
> **"Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python"**
> *Karya: Peter Bruce, Andrew Bruce, & Peter Gedeck (O'Reilly)*

Seluruh penjelasan teori, visualisasi, latihan kode, dan ringkasan disajikan dalam **Bahasa Indonesia** dengan kualitas premium.

---

## 📌 Daftar Bab dan Jupyter Notebooks

Berikut adalah daftar bab pembelajaran beserta tautan langsung ke masing-masing berkas notebook utama:

*   **[Bab 1: Analisis Data Eksploratif (Exploratory Data Analysis)](01.Exploratory_Data_Analysis.ipynb)**
    *   *Deskripsi:* Membahas dasar-dasar Analisis Data Eksploratif (EDA), tipe-tipe data, estimasi pemusatan (mean, median), estimasi variabilitas, serta visualisasi sebaran data.
*   **[Bab 2: Distribusi Data dan Pengambilan Sampel (Data and Sampling Distributions)](02.Data_and_Sampling_Distributions.ipynb)**
    *   *Deskripsi:* Membahas bagaimana sampel diambil dari populasi, pembuktian komputasional Central Limit Theorem (CLT), standard error, teknik bootstrapping, dan jenis-jenis distribusi probabilitas standar.
*   **[Bab 3: Eksperimen Statistik dan Uji Signifikansi (Statistical Experiments and Significance Testing)](03.Statistical_Experiments_and_Significance_Testing.ipynb)**
    *   *Deskripsi:* Membahas prinsip eksperimen terkontrol menggunakan A/B testing, perumusan hipotesis nol, penghitungan p-value, t-test, uji ANOVA, serta uji Chi-Square.
*   **[Bab 4: Regresi dan Prediksi (Regression and Prediction)](04.Regression_and_Prediction.ipynb)**
    *   *Deskripsi:* Membahas pemodelan regresi linier sederhana, regresi linier berganda, evaluasi kinerja model regresi (RMSE, R-squared), analisis diagnostik regresi, serta regresi polinomial.
*   **[Bab 5: Klasifikasi (Classification)](05.Classification.ipynb)**
    *   *Deskripsi:* Membahas klasifikasi menggunakan Naive Bayes, Discriminant Analysis, Logistic Regression, serta metrik evaluasi klasifikasi (ROC-AUC, Confusion Matrix, imbalance data strategies).
*   **[Bab 6: Machine Learning Statistik (Statistical Machine Learning)](06.Statistical_Machine_Learning.ipynb)**
    *   *Deskripsi:* Membahas perluasan konsep statistik ke machine learning meliputi K-Nearest Neighbors (K-NN), Decision Trees, Bagging & Random Forest, serta Boosting.
*   **[Bab 7: Pembelajaran Tanpa Pengawasan (Unsupervised Learning)](07.Unsupervised_Learning.ipynb)**
    *   *Deskripsi:* Membahas pengelompokan data menggunakan K-Means Clustering, Hierarchical Clustering, DBSCAN, serta Principal Component Analysis (PCA) untuk reduksi dimensi.

---

## 🛠️ Persyaratan Lingkungan (Requirements)

Untuk menjalankan seluruh notebook di atas, disarankan menggunakan **Python 3.10+** dengan beberapa dependensi utama berikut:
```bash
pip install numpy<2 pandas matplotlib scipy sympy scikit-image statsmodels seaborn dmba wquantiles
```

*Semua dataset yang digunakan dalam modul ini disertakan secara lokal di dalam folder `data/`.*
