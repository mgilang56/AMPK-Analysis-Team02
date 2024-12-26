# 🚀 Implementasi Random Forest untuk Klasifikasi dan Analisis Aktivasi AMPK

<p align="center">
  <img src="https://raw.githubusercontent.com/mgilang56/AMPK-Analysis-Team02/refs/heads/main/Assets/Banner%20Github%20%26%20Background%20Zoom.png" alt="Project Banner" width="100%">
</p>


## 📋 Daftar Isi
1. [🌟 Pendahuluan](#-pendahuluan)
2. [✨ Fitur](#-fitur)
3. [📂 Struktur Proyek](#-struktur-proyek)
4. [⚙️ Persyaratan](#️-persyaratan)
5. [📊 Deskripsi Data](#-deskripsi-data)
6. [🛠️ Metode](#️-metode)
7. [🔬 Hasil dan Pembahasan](#-hasil-dan-pembahasan)
8. [🚀 Penggunaan](#-penggunaan)
9. [🤝 Kontributor](#-kontributor)
10. [📜 Lisensi](#-lisensi)
11. [🌟 Penghargaan dan Apresiasi](#-penghargaan-dan-apresiasi)

---

## 🌟 Pendahuluan
Repositori ini berisi implementasi model Random Forest untuk menganalisis aktivasi AMP-activated protein kinase (AMPK) dalam metabolisme dan penyakit metabolik. Proyek ini memanfaatkan data bioaktivitas dari ChEMBL untuk mengidentifikasi properti molekuler utama dan memprediksi aktivasi AMPK.

### 🎯 Tujuan:
- Menganalisis peran AMPK dalam metabolisme energi dan potensinya sebagai aplikasi terapeutik.
- Mengidentifikasi pola regulasi menggunakan Random Forest.
- Mengevaluasi efektivitas algoritma Random Forest dalam menangani data biologis berdimensi tinggi.

### 🛠 Sorotan:
- Preprocessing data, termasuk pembersihan data dan deduplikasi.
- Analisis Data Eksploratif (EDA) dengan visualisasi wawasan utama.
- Ekstraksi fitur menggunakan sidik jari molekuler.
- Pembangunan model dan evaluasi menggunakan metrik yang kuat.
- Analisis kesamaan menggunakan koefisien Tanimoto.

---

## ✨ Fitur
✅ **Preprocessing Data**: Membersihkan nilai yang hilang dan duplikat untuk kualitas data optimal.

📊 **Visualisasi EDA**: Scatter plot, box plot, dan histogram untuk mengidentifikasi tren data.

🌳 **Klasifikasi Random Forest**: Pohon keputusan multi-fitur untuk prediksi bioaktivitas.

📈 **Evaluasi Metrik**: Akurasi, presisi, recall, F1-score, matriks kebingungan, dan kurva ROC.

🔬 **Analisis Kesamaan**: Kesamaan Tanimoto untuk perbandingan molekuler.

---

## 📂 Struktur Proyek
```
├── Assets
│   ├── logo jurusan sains.png
│   ├── logo sains data.jpg
│   ├── logo-itera-oke.jpg
├── Code
│   ├── RA_Kelompok02_Model_RandomForest_AMPK.ipynb
│   ├── RA_Kelompok02_Tubes_Bio_Screening.ipynb
├── Data
│   ├── AMPK2.csv
│   ├── data_preprasi_AMPK.csv
│   ├── data_preprasi_kategori_AMPK.csv
│   ├── dataset_model_AMPK.csv
│   ├── dataset_modelvariance_AMPK.csv
│   ├── dataset_prep_AMPK.csv
│   ├── descriptors_output.csv
│   ├── input_deskriptor.csv
│   ├── label_AMPK.csv
│   ├── label2class_AMPK.csv
│   ├── mannwhitney_NumHAcceptors.csv
│   ├── mannwhitney_NumHDonors.csv
│   ├── mannwhitney_pIC50.csv
├── Laporan
│   ├── Asset Laporan
│   │   ├── Laporan_Kelompok02_RA_TubesBioinformatika.docx_files
│   │   ├── Laporan_Kelompok02_RA_TubesBioinformatika.docx.html
│   ├── Laporan_Kelompok02_RA_TubesBioinformatika.docx
│   ├── Jurnal Rujukan
│   ├── PPT_Kelompok02_RA_TubesBioinformatika.pptx
```

---

## ⚙️ Persyaratan
Untuk menjalankan proyek ini, instal dependensi yang diperlukan:

```bash
pip install -r requirements.txt
```

## 🛠️ Teknologi dan Library yang Digunakan

Berikut adalah daftar lengkap bahasa pemrograman dan library yang digunakan dalam proyek ini:

| **Komponen**    | **Deskripsi**                                                                                                                                       |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| ![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python) | Bahasa utama untuk pengembangan proyek ini.                                                                                         |
| ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?style=flat&logo=pandas) | Library untuk manipulasi data tabular dengan efisiensi tinggi.                                                                      |
| ![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange?style=flat&logo=numpy) | Mendukung perhitungan matematis dan operasi array yang kompleks.                                                                    |
| ![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-green?style=flat&logo=scikit-learn) | Library untuk membangun, melatih, dan mengevaluasi model machine learning, termasuk Random Forest.                                 |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-yellow?style=flat&logo=matplotlib) | Digunakan untuk membuat grafik visualisasi data, seperti histogram, scatter plot, dan lainnya.                                      |
| ![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-blueviolet?style=flat&logo=seaborn) | Membuat visualisasi data statistik yang lebih menarik dan interaktif.                                                              |
| ![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?style=flat&logo=tensorflow) | Framework untuk membangun model deep learning canggih dan mendalam.                                                                |
| ![Keras](https://img.shields.io/badge/Keras-Neural%20Networks-red?style=flat&logo=keras) | Library untuk pengembangan model deep learning yang lebih mudah dan cepat.                                                         |
| ![RDKit](https://img.shields.io/badge/RDKit-Chemoinformatics-purple?style=flat&logo=chemistry) | Library untuk analisis data molekuler, seperti perhitungan properti molekul.                                                       |
| ![PaDEL](https://img.shields.io/badge/PaDEL-Descriptor%20Calculation-brightgreen?style=flat&logo=chemistry) | Mendukung perhitungan deskriptor molekul yang penting dalam analisis kimia komputasi.                                              |
| ![VisualKeras](https://img.shields.io/badge/VisualKeras-Model%20Visualization-red?style=flat&logo=keras) | Membantu memvisualisasikan arsitektur neural network yang dibuat, membuatnya lebih intuitif.                                        |
| ![LazyPredict](https://img.shields.io/badge/LazyPredict-AutoML-green?style=flat&logo=robotframework) | Mempercepat proses eksperimen dengan membandingkan berbagai algoritma machine learning secara otomatis.                             |

---

## 🔎 Penjelasan Komponen

1. **Python**: Platform pemrograman serbaguna yang memberikan fleksibilitas dalam pemrosesan data dan pengembangan model.
2. **Pandas & NumPy**: Digunakan untuk menangani data dengan efisiensi tinggi dalam format tabel dan array multidimensi.
3. **Scikit-learn**: Komponen inti untuk implementasi algoritma Random Forest dan evaluasi performa model.
4. **TensorFlow & Keras**: Untuk pengembangan model deep learning, mendukung analisis lebih kompleks terhadap pola data.
5. **RDKit & PaDEL**: Alat khusus untuk menangani data kimia, seperti properti molekuler dan deskriptor.
6. **Matplotlib & Seaborn**: Membantu dalam memvisualisasikan hasil analisis secara informatif dan menarik.
7. **LazyPredict**: Solusi cepat untuk membandingkan performa berbagai algoritma tanpa proses coding manual yang rumit.

---

---

## 📊 Deskripsi Data

Dataset diambil dari **database ChEMBL** yang berisi data aktivitas biologis molekul terhadap protein AMPK. Berikut adalah rincian utama dataset:

- **Jumlah Molekul**: 174
- **Kolom Fitur Utama**: 
  - **MW (Molecular Weight)**: Massa molekul
  - **LogP**: Logaritma partisi lipofilik
  - **NumHDonors**: Jumlah donor hidrogen
  - **NumHAcceptors**: Jumlah akseptor hidrogen
  - **pIC50**: Efektivitas molekul dalam menghambat AMPK
  - **Fingerprint Molekuler**: Representasi biner (0/1) fitur kimia.
- **Kolom Target**: Kelas bioaktivitas (Active/InActive)

Dataset memiliki 889 kolom fingerprint molekuler yang memberikan deskripsi rinci tentang fitur kimia unik.

**Tabel Contoh Dataset**:

| No  | Molecul Chembl ID | Canonical Smile      | MW    | LogP  | NumHDonors | NumHAcceptors | pIC50 | Class     |
|-----|-------------------|----------------------|-------|-------|------------|---------------|-------|-----------|
| 1   | CHEMBL535         | CCN(CC)CCNC(=O)...  | 398.48| 3.33  | 3          | 3             | 7.20  | Active    |
| 2   | CHEMBL281957      | CCN(CC)C/C=C/c...   | 484.43| 6.54  | 2          | 6             | 6.00  | Active    |
| ... | ...               | ...                  | ...   | ...   | ...        | ...           | ...   | ...       |

---
## 🛠️ Metode

Tahapan dalam penelitian ini melibatkan langkah-langkah berikut:

1. **Data Preparation**:
   - Membersihkan data dengan menghapus nilai kosong dan duplikasi.
   - Memilih kolom penting: `molecule_chembl_id`, `canonical_smiles`, `standard_value`.
   - Normalisasi nilai pIC50 dan klasifikasi molekul berdasarkan nilai pIC50 ≥ 6.5 sebagai **Active**, dan < 6.5 sebagai **Inactive**.

2. **Exploratory Data Analysis (EDA)**:
   - Analisis distribusi bioaktivitas molekul menggunakan visualisasi seperti histogram, scatter plot, dan boxplot.
   - Identifikasi pola hubungan antara fitur kimia utama dengan bioaktivitas.

3. **Fingerprint Molekuler & Tanimoto Similarity**:
   - Menggunakan fingerprint molekuler untuk mendeskripsikan karakteristik kimia molekul.
   - Mengukur kesamaan molekul dengan Tanimoto Similarity.

4. **Modeling dengan Random Forest**:
   - Menggunakan algoritma Random Forest untuk klasifikasi molekul berdasarkan fitur kimia dan bioaktivitas.
   - Evaluasi model menggunakan akurasi, presisi, recall, F1-score, confusion matrix, dan kurva ROC.

5. **Evaluasi Model**:
   - Analisis performa model berdasarkan **AUC (Area Under Curve)**, yang menunjukkan kemampuan diskriminasi model.

---
## 🔬 Hasil dan Pembahasan

### **1. Exploratory Data Analysis (EDA)**

- Distribusi kelas bioaktivitas:
  - Molekul Active: **33 molekul**
  - Molekul Inactive: **141 molekul**
  - Kelas Active memiliki nilai pIC50 lebih tinggi (≥ 6.5), sedangkan Inactive lebih rendah.

- Pola hubungan fitur:
  - Molekul dengan MW > 400 dan LogP 4–6 cenderung **Active**.
  - Distribusi fitur seperti **NumHDonors** dan **NumHAcceptors** menunjukkan pola unik pada masing-masing kelas bioaktivitas.

### **2. Evaluasi Random Forest**

**Tabel Evaluasi Model:**

| Parameter        | Presisi | Recall | F1-Score | Support |
|------------------|---------|--------|----------|---------|
| Active           | 0.80    | 0.57   | 0.67     | 7       |
| Inactive         | 0.90    | 0.96   | 0.93     | 28      |
| **Akurasi**      |         |        | 0.89     | 35      |
| **AUC**          |         |        | **0.95** |         |

- **Confusion Matrix**:
  - True Positives: 4
  - True Negatives: 27
  - False Positives: 1
  - False Negatives: 3

- **Fitur Penting**:
  - MW (Molecular Weight): 0.0361
  - PubchemFP568: 0.0310
  - PubchemFP194: 0.0306
  - pIC50: 0.0258

---

## 🚀 Penggunaan

### 🛠 Langkah-Langkah:
1. Kloning repositori:
   ```bash
   git clone https://github.com/your-repo/random-forest-ampk.git
   cd random-forest-ampk
   ```

2. Siapkan dataset dengan meletakkannya di direktori `data`.

3. Jalankan skrip preprocessing:

4. Latih model Random Forest:

5. Evaluasi model:

6. Visualisasikan hasil menggunakan Jupyter Notebooks di folder `notebooks`.
---

## 🤝 Kontributor

Kami ingin mengapresiasi para kontributor luar biasa yang telah berkontribusi pada proyek ini. Berikut adalah tim hebat kami:

<table>
  <tr align="center">
    <th>📸 Nama</th>
    <th>🌐 Profil GitHub</th>
    <th>✉️ Email</th>
  </tr>
  <tr align="center">
    <td>
      <img src="https://github.com/mgilang56.png?size=100" width="80"><br>
      <b>M. Gilang Martiansyah</b>
    </td>
    <td><a href="https://github.com/mgilang56">@mgilang56</a></td>
    <td>mgilang.121450056@student.itera.ac.id</td>
  </tr>
  <tr align="center">
    <td>
      <img src="https://github.com/Ghozialvin.png?size=100" width="80"><br>
      <b>Ghozi Alvin Karim</b>
    </td>
    <td><a href="https://github.com/Ghozialvin">@ghozialvin</a></td>
    <td>-</td>
  </tr>
  <tr align="center">
    <td>
      <img src="https://github.com/liaalyani.png?size=100" width="80"><br>
      <b>Lia Alyani</b>
    </td>
    <td><a href="https://github.com/liaalyani">@liaalyani</a></td>
    <td>lia.121450138@student.itera.ac.id</td>
  </tr>
  <tr align="center">
    <td>
      <img src="https://github.com/nadillaandhara.png?size=100" width="80"><br>
      <b>Nadilla Andhara Putri</b>
    </td>
    <td><a href="https://github.com/nadillaandhara">@nadillaandhara</a></td>
    <td>nadilla.121450003@student.itera.ac.id</td>
  </tr>
  <tr align="center">
    <td>
      <img src="https://github.com/andiniamal01.png?size=100" width="80"><br>
      <b>Anisa Dini Amalia</b>
    </td>
    <td><a href="https://github.com/andiniamal01">@anisadini</a></td>
    <td>anisa.121450081@student.itera.ac.id</td>
  </tr>
  <tr align="center">
    <td>
      <img src="https://github.com/muhammadfaqih12345.png?size=100" width="80"><br>
      <b>M. Faqih</b>
    </td>
    <td><a href="https://github.com/muhammadfaqih12345">@mfaqih</a></td>
    <td>-</td>
  </tr>
</table>

---


> _**Terima kasih kepada seluruh tim atas kerja keras, kreativitas, dan dedikasinya dalam proyek ini!**_


## 📜 Lisensi

Proyek ini **belum dilisensikan** secara resmi. Jika Anda ingin menggunakan atau memodifikasi proyek ini, silakan hubungi kami melalui email untuk mendapatkan izin. Kami terbuka untuk diskusi terkait kolaborasi dan penggunaan proyek ini di masa depan.


---

## 🌟 Penghargaan dan Apresiasi

Proyek ini tidak akan terwujud tanpa dukungan dan kontribusi luar biasa dari banyak pihak. Dengan penuh rasa syukur, kami ingin menyampaikan penghargaan kepada:

- **Tirta Setiawan, S.Pd., M.Si.**  
  Terima kasih yang sebesar-besarnya kepada dosen pembimbing kami atas bimbingan, wawasan, dan dukungan yang tak ternilai selama proyek ini. Dedikasi Bapak dalam membimbing kami tidak hanya memberikan arahan yang tepat, tetapi juga menginspirasi kami untuk terus belajar dan berkembang dalam bidang bioinformatika.

- **Seluruh Anggota Tim**  
  - **M. Gilang Martiansyah**, **Ghozi Alvin Karim**, **Lia Alyani**, **Nadilla Andhara Putri**, **Anisa Dini Amalia**, dan **M. Faqih**:  
    Kolaborasi, kerja keras, dan semangat tak kenal lelah dari kalian adalah kunci sukses dari proyek ini. Setiap diskusi, ide kreatif, dan upaya bersama telah membawa hasil yang luar biasa. Terima kasih telah menjadikan perjalanan ini penuh makna dan menyenangkan!

Kami juga ingin mengucapkan terima kasih kepada semua pihak yang secara langsung maupun tidak langsung telah mendukung proyek ini, termasuk rekan-rekan di Fakultas Sains, Institut Teknologi Sumatera.

> _“Kolaborasi adalah kekuatan utama. Bersama, kita menciptakan sesuatu yang lebih besar dari apa yang bisa kita capai sendiri.”_

Semoga hasil dari proyek ini dapat memberikan manfaat bagi komunitas akademik dan penelitian di masa depan. Kami merasa sangat beruntung dapat berbagi perjalanan luar biasa ini bersama kalian semua! 🌟
