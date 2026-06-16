# Replikasi Kode dan Prapemrosesan scikit-learn Cookbook, Third Edition

| Identitas | Detail |
| :--- | :--- |
| **Nama** | Rahmanda Afebrio Yuris Soesatyo |
| **NIM** | 1103223024 |

Indeks dan dokumentasi repositori pembelajaran Bahasa Indonesia untuk buku **"scikit-learn Cookbook, Third Edition"** karya John Sukup (Packt Publishing). Repositori ini berisi notebook Jupyter hasil replikasi kode resep (*recipes*) dari Bab 1 sampai Bab 13, lengkap dengan penjelasan teoretis, analisis kode, dan solusi latihan dalam Bahasa Indonesia dengan standar kualitas premium ("rapi dan niat").

---

## 📌 Daftar Bab dan Jupyter Notebooks

Berikut adalah daftar bab pembelajaran beserta tautan langsung ke masing-masing berkas notebook utama dan solusi latihannya:

### Bab 1: Konvensi Umum dan Elemen API scikit-learn
*   **[Jupyter Notebook](01.Common_Conventions_and_API_Elements_of_scikit_learn.ipynb)**
    *   *Deskripsi:* Memahami filosofi desain scikit-learn, konsep pemrograman OOP (Estimator, Transformer, Predictor), metode fit/predict/transform, pembuatan transformer kustom, otomatisasi alur kerja dengan Pipeline, serta metadata routing pada scikit-learn v1.5+.

### Bab 2: Pre-Model Workflow and Data Preprocessing
*   **[Jupyter Notebook](02.Pre_Model_Workflow_and_Data_Preprocessing.ipynb)**
    *   *Deskripsi:* Penanganan data hilang (`SimpleImputer`, `KNNImputer`, `IterativeImputer`), teknik skalasi data (`StandardScaler`, `MinMaxScaler`, `RobustScaler`), pengodean kategori (`OneHotEncoder`, `OrdinalEncoder`), dan rekayasa fitur polinomial.

### Bab 3: Dimensionality Reduction Techniques
*   **[Jupyter Notebook](03.Dimensionality_Reduction_Techniques.ipynb)**
    *   *Deskripsi:* Reduksi dimensi dengan PCA (unsupervised), LDA (supervised), dan teknik visualisasi sebaran data non-linier menggunakan t-SNE.

### Bab 4: Building Models with Distance Metrics and Nearest Neighbors
*   **[Jupyter Notebook](04.Building_Models_with_Distance_Metrics_and_Nearest_Neighbors.ipynb)**
    *   *Deskripsi:* Klasifikasi dan regresi dengan k-Nearest Neighbors (k-NN), kustomisasi metrik jarak (Euclidean, Manhattan, Minkowski), serta optimasi parameter $k$ dengan Grid Search.

### Bab 5: Linear Models and Regularization
*   **[Jupyter Notebook](05.Linear_Models_and_Regularization.ipynb)**
    *   *Deskripsi:* Regresi linier sederhana, serta regresi ter-regularisasi Ridge (L2 penalty), Lasso (L1 penalty), dan kombinasi ElasticNet untuk mencegah overfitting.

### Bab 6: Advanced Logistic Regression and Extensions
*   **[Jupyter Notebook](06.Advanced_Logistic_Regression_and_Extensions.ipynb)**
    *   *Deskripsi:* Regresi logistik tingkat lanjut, klasifikasi multikelas menggunakan strategi One-vs-Rest (OVR) dan One-vs-One (OVO), serta klasifikasi multilabel.

### Bab 7: Support Vector Machines and Kernel Methods
*   **[Jupyter Notebook](07.Support_Vector_Machines_and_Kernel_Methods.ipynb)**
    *   *Deskripsi:* Pemodelan SVM, trik kernel (RBF, Polynomial, Linear) untuk batas keputusan non-linier, visualisasi batas keputusan, serta penyetelan hyperparameter $C$ dan $\gamma$.

### Bab 8: Tree-Based Algorithms and Ensemble Methods
*   **[Jupyter Notebook](08.Tree_Based_Algorithms_and_Ensemble_Methods.ipynb)**
    *   *Deskripsi:* Decision Trees, Bagging, Random Forest, dan Gradient Boosting (GBM) untuk data tabular serta penyetelan kedalaman pohon.

### Bab 9: Text Processing and Multiclass Classification
*   **[Jupyter Notebook](09.Text_Processing_and_Multiclass_Classification.ipynb)**
    *   *Deskripsi:* Rekayasa fitur teks menggunakan CountVectorizer (Bag-of-Words) dan TfidfVectorizer (TF-IDF), penyaringan stop words, ekstraksi n-grams, dan klasifikasi berita/teks.

### Bab 10: Clustering Techniques
*   **[Jupyter Notebook](10.Clustering_Techniques.ipynb)**
    *   *Deskripsi:* Pembelajaran tanpa pengawasan dengan K-Means, Clustering Hierarki, DBSCAN berbasis kepadatan, dan Gaussian Mixture Models (GMM), serta metrik evaluasi Silhouette Score.

### Bab 11: Outlier and Novelty Detection
*   **[Jupyter Notebook](11.Outlier_and_Novelty_Detection.ipynb)**
    *   *Deskripsi:* Deteksi anomali pada data latih (Outlier Detection) dan data baru (Novelty Detection) menggunakan Isolation Forest, One-Class SVM, dan Local Outlier Factor (LOF).

### Bab 12: Cross-Validation and Model Evaluation Techniques
*   **[Jupyter Notebook](12.Cross_Validation_and_Model_Evaluation_Techniques.ipynb)**
    *   *Deskripsi:* Evaluasi generalisasi model dengan K-Fold dan Stratified K-Fold CV, Grid Search dan Randomized Search, serta visualisasi Learning Curves dan Validation Curves.

### Bab 13: Deploying scikit-learn Models in Production
*   **[Jupyter Notebook](13.Deploying_scikit_learn_Models_in_Production.ipynb)**
    *   *Deskripsi:* Langkah final siklus machine learning: persistensi model dengan `pickle`/`joblib`, penulisan deployment pipeline terintegrasi, pemantauan akurasi terhadap *model drift*, dan otomatisasi deployment check.

---

## 🛠️ Persyaratan Lingkungan (Requirements)

Untuk menjalankan seluruh notebook di atas, disarankan menggunakan **Python 3.10+** dengan beberapa dependensi utama berikut:
```bash
pip install numpy pandas scikit-learn>=1.5.0 matplotlib scipy
```

*Semua dataset yang digunakan dalam modul ini dihasilkan secara dinamis menggunakan modul buatan scikit-learn (seperti `make_classification`, `make_blobs`) atau diunduh secara otomatis melalui API dataset bawaan scikit-learn.*
