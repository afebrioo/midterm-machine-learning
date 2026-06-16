# Replikasi Pengantar Machine Learning dengan Python

| Identitas | Detail |
| :--- | :--- |
| **Nama** | Rahmanda Afebrio Yuris Soesatyo |
| **NIM** | 1103223024 |

Repositori ini dibuat untuk memenuhi tugas replikasi kode, ringkasan bab, dan penjelasan teoritis dari buku populer:
> **"Introduction to Machine Learning with Python: A Guide for Data Scientists"**
> *Karya: Andreas C. Müller & Sarah Guido (O'Reilly)*

Seluruh penjelasan teori, ringkasan alur kerja, dan dokumentasi di dalam repositori ini disajikan dalam **Bahasa Indonesia**.

---

## Daftar Isi & Status Pembelajaran

- [x] **[Bab 1: Pendahuluan (Introduction)](file:///c:/College/Machine%20learning/Introduction%20to%20Machine%20Learning%20with%20Python/01.Introduction.ipynb)** - Klasifikasi Bunga Iris menggunakan K-Nearest Neighbors (k-NN).
- [x] **[Bab 2: Supervised Learning](file:///c:/College/Machine%20learning/Introduction%20to%20Machine%20Learning%20with%20Python/02.Supervised_Learning.ipynb)** - Algoritma klasifikasi dan regresi (Linear Model, SVM, Decision Tree, Random Forest, dll.).
- [x] **[Bab 3: Unsupervised Learning & Preprocessing](file:///c:/College/Machine%20learning/Introduction%20to%20Machine%20Learning%20with%20Python/03.Unsupervised_Learning.ipynb)** - PCA, K-Means, DBSCAN, scaling, dan reduksi dimensi.
- [x] **[Bab 4: Representasi Data & Feature Engineering](file:///c:/College/Machine%20learning/Introduction%20to%20Machine%20Learning%20with%20Python/04.Representing_Data.ipynb)** - Categorical variables, binning, interaction, dan polynomial features.
- [x] **[Bab 5: Evaluasi & Perbaikan Model](file:///c:/College/Machine%20learning/Introduction%20to%20Machine%20Learning%20with%20Python/05.Model_Evaluation.ipynb)** - Cross-validation, Grid Search, metrik evaluasi (Precision, Recall, ROC-AUC).
- [x] **[Bab 6: Pipeline](file:///c:/College/Machine%20learning/Introduction%20to%20Machine%20Learning%20with%20Python/06.Pipeline.ipynb)** - Enkapsulasi alur kerja pemrosesan data dan pemodelan.
- [x] **[Bab 7: Bekerja dengan Data Teks](file:///c:/College/Machine%20learning/Introduction%20to%20Machine%20Learning%20with%20Python/07.Text_Data.ipynb)** - Bag-of-Words, TF-IDF, analisis sentimen.
- [x] **[Bab 8: Ringkasan & Langkah Selanjutnya](file:///c:/College/Machine%20learning/Introduction%20to%20Machine%20Learning%20with%20Python/08.Summary.ipynb)** - Tips praktis dalam menangani proyek machine learning nyata.

---

## Ringkasan Bab

### [Bab 1: Pendahuluan (Introduction)](file:///c:/College/Machine%20learning/Introduction%20to%20Machine%20Learning%20with%20Python/01.Introduction.ipynb)

Bab pertama ini memberikan fondasi penting mengenai apa itu machine learning, mengapa menggunakan Python dan ekosistem pustaka ilmiahnya, serta mendemonstrasikan aplikasi praktis klasifikasi menggunakan dataset Iris klasik.

#### 1. Konsep Utama Machine Learning
* **Supervised Learning (Pembelajaran Terawasi):** Model dilatih menggunakan data yang sudah memiliki pasangan masukan dan keluaran (label) yang benar. Contoh kasus di bab ini adalah klasifikasi spesies bunga Iris berdasarkan ukuran kelopak dan benang sarinya.
* **Unsupervised Learning (Pembelajaran Tanpa Pengawasan):** Algoritma mencari pola intrinsik dalam data tanpa adanya label keluaran yang diketahui.

#### 2. Pustaka Esensial yang Digunakan
* **NumPy:** Digunakan untuk komputasi ilmiah dengan struktur data array multi-dimensi (`ndarray`) berkecepatan tinggi.
* **SciPy:** Menyediakan fungsi matematika tingkat lanjut, optimasi, dan representasi matriks jarang (*sparse matrices* seperti format CSR dan COO) untuk menghemat memori pada dataset berdimensi besar.
* **Matplotlib:** Pustaka visualisasi utama untuk membuat grafik publikasi berkualitas (seperti plot garis dan scatter plot).
* **Pandas:** Digunakan untuk manipulasi dan analisis data tabular (`DataFrame`) secara efisien, serta menyediakan utilitas plotting tingkat tinggi seperti matriks pencar (*scatter matrix*).
* **scikit-learn:** Pustaka machine learning terlengkap di Python yang menjadi fokus utama buku ini.
* **mglearn:** Pustaka pembantu (*helper library*) bawaan buku untuk menyederhanakan visualisasi pemodelan.

#### 3. Aplikasi Pertama: Klasifikasi Spesies Iris (Iris Species Classification)
Dalam studi kasus pertama, kita membangun model klasifikasi untuk memprediksi apakah bunga Iris termasuk spesies **Setosa**, **Versicolor**, atau **Virginica** berdasarkan 4 fitur: panjang sepal, lebar sepal, panjang petal, dan lebar petal.
* **Data Splitting (Pembagian Data):** Menggunakan `train_test_split` untuk membagi data menjadi **Training Set (75%)** untuk melatih model dan **Test Set (25%)** untuk menguji performa model baru. Pembagian acak dikontrol menggunakan parameter `random_state` agar hasil eksperimen konsisten.
* **Visualisasi Pencar (Pair Plot):** Menggunakan `pd.plotting.scatter_matrix` untuk memeriksa hubungan antarlapisan fitur dan memastikan kelas-kelas data dapat dipisahkan sebelum model dibuat.
* **Model K-Nearest Neighbors (k-NN):** Algoritma klasifikasi berbasis instance yang memprediksi kelas data baru berdasarkan suara terbanyak dari $k$ tetangga terdekatnya. Pada bab ini, kita menggunakan $k=1$.
* **Evaluasi Model:** Model diuji menggunakan data tes (yang belum pernah dilihat model selama pelatihan) dan menghasilkan akurasi yang diukur melalui metode `score`. Alur kerja dasar ini dilatih agar model dapat digeneralisasi dengan baik pada data baru di masa depan.
