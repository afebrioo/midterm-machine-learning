# Replikasi Aljabar Linier Praktis untuk Data Science

| Identitas | Detail |
| :--- | :--- |
| **Nama** | Rahmanda Afebrio Yuris Soesatyo |
| **NIM** | 1103223024 |

Repositori ini dibuat untuk mereplikasi kode program, ringkasan, dan penjelasan teoritis dari buku acuan aljabar linier modern:
> **"Practical Linear Algebra for Data Science: With Python"**
> *Karya: Mike X. Cohen (O'Reilly)*

Seluruh penjelasan teori, visualisasi, latihan kode, dan ringkasan disajikan dalam **Bahasa Indonesia** dengan kualitas premium.

---

## 📌 Daftar Bab dan Jupyter Notebooks

Berikut adalah daftar bab pembelajaran beserta tautan langsung ke masing-masing berkas notebook utama:

*   **[Bab 1: Pendahulan (Introduction)](01.Introduction.ipynb)**
    *   *Deskripsi:* Pengenalan aljabar linier komputasional, perbedaan dengan aljabar tradisional, motivasi data science, dan soft-proofs.
*   **[Bab 2: Vektor, Bagian 1 (Vectors, Part 1)](02.Vectors_Part_1.ipynb)**
    *   *Deskripsi:* Representasi geometri dan numerik dari vektor, operasi dasar penjumlahan, pengurangan, perkalian skalar, transpose, dan sifat distributif dot product.
*   **[Bab 3: Vektor, Bagian 2 (Vectors, Part 2)](03.Vectors_Part_2.ipynb)**
    *   *Deskripsi:* Kombinasi linier berbobot, basis vektor, koordinat, norm (panjang), hubungan dot product dengan geometri, serta proyeksi vektor.
*   **[Bab 4: Aplikasi Vektor (Vector Applications)](04.Vector_Applications.ipynb)**
    *   *Deskripsi:* Aplikasi vektor dalam korelasi data, kemiripan kosinus (*cosine similarity*), dan penyaringan spasial (*spatial filtering*).
*   **[Bab 5: Matriks, Bagian 1 (Matrices, Part 1)](05.Matrices_Part_1.ipynb)**
    *   *Deskripsi:* Dasar-dasar matriks, representasi citra, slicing baris/kolom, matriks khusus, penjumlahan, shifting, perkalian skalar, dan perkalian Hadamard.
*   **[Bab 6: Matriks, Bagian 2 (Matrices, Part 2)](06.Matrices_Part_2.ipynb)**
    *   *Deskripsi:* Perkalian matriks standar, geometri perkalian matriks-vektor, transpose matriks, trace, norm Frobenius, ruang kolom (column space), dan null space.
*   **[Bab 7: Aplikasi Matriks (Matrix Applications)](07.Matrix_Applications.ipynb)**
    *   *Deskripsi:* Aplikasi matriks meliputi pembuatan matriks kovarians, matriks transformasi geometri (rotasi, scaling, shear), animasi, dan konvolusi citra.
*   **[Bab 8: Invers Matriks (Matrix Inverse)](08.Matrix_Inverse.ipynb)**
    *   *Deskripsi:* Konsep invers matriks, determinan, matriks identitas, invers matriks diagonal, left-inverse, dan pseudoinvers Moore-Penrose.
*   **[Bab 9: Matriks Ortogonal dan Dekomposisi QR (Orthogonal Matrices and QR Decomposition)](09.Orthogonal_Matrices_and_QR_Decomposition.ipynb)**
    *   *Deskripsi:* Matriks ortogonal, proyeksi ortogonal, ortogonalisasi Gram-Schmidt, dekomposisi QR (faktor Q dan R).
*   **[Bab 10: Reduksi Baris dan Dekomposisi LU (Row Reduction and LU Decomposition)](10.Row_Reduction_and_LU_Decomposition.ipynb)**
    *   *Deskripsi:* Eliminasi Gauss-Jordan, bentuk eselon baris tereduksi (RREF), penyelesaian persamaan linier, dan dekomposisi LU (Lower-Upper).
*   **[Bab 11: General Linear Models (GLM) dan Least Squares](11.General_Linear_Models_and_Least_Squares.ipynb)**
    *   *Deskripsi:* Persamaan normal least squares, formulasi GLM, dan pemodelan regresi linier dari perspektif aljabar linier.
*   **[Bab 12: Aplikasi Least Squares (Least Squares Applications)](12.Least_Squares_Applications.ipynb)**
    *   *Deskripsi:* Regresi data riil (bike rental), pemodelan polinomial, penanganan multikolinieritas, dan regularisasi.
*   **[Bab 13: Dekomposisi Eigen (Eigendecomposition)](13.Eigendecomposition.ipynb)**
    *   *Deskripsi:* Nilai eigen (eigenvalues) dan vektor eigen (eigenvectors), diagonalisasi matriks, sifat matriks simetris, dan bentuk kuadratis.
*   **[Bab 14: Singular Value Decomposition (SVD)](14.Singular_Value_Decomposition.ipynb)**
    *   *Deskripsi:* Teori SVD, komponen U, Sigma, dan V-transpose, serta rekonstruksi matriks peringkat rendah (low-rank approximation).
*   **[Bab 15: Aplikasi Eigendecomposition dan SVD (Eigendecomposition and SVD Applications)](15.Eigendecomposition_and_SVD_Applications.ipynb)**
    *   *Deskripsi:* Algoritma Principal Component Analysis (PCA) berbasis SVD pada data keuangan, serta kompresi citra digital.
*   **[Bab 16: Tutorial Python (Python Tutorial)](16.Python_Tutorial.ipynb)**
    *   *Deskripsi:* Rangkuman dasar-dasar pemrograman Python, modul dasar NumPy, dan Matplotlib untuk manipulasi aljabar linier.

---

## 🛠️ Persyaratan Lingkungan (Requirements)

Untuk menjalankan seluruh notebook di atas, disarankan menggunakan **Python 3.10+** dengan beberapa dependensi utama berikut:
```bash
pip install numpy<2 pandas matplotlib scipy sympy scikit-image statsmodels plotly
```
