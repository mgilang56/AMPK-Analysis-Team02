# 🚀 Implementasi Random Forest untuk Klasifikasi dan Analisis Aktivasi AMPK

![Project Banner](https://via.placeholder.com/1000x300?text=Random+Forest+AMPK+Analysis)

## 📋 Daftar Isi
- [🌟 Pendahuluan](#pendahuluan)
- [✨ Fitur](#fitur)
- [📂 Struktur Proyek](#struktur-proyek)
- [⚙️ Persyaratan](#persyaratan)
- [🚀 Penggunaan](#penggunaan)
- [🤝 Kontributor](#kontributor)
- [📜 Lisensi](#lisensi)

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

### Pustaka Utama:
- Python 3.8+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

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
   ```bash
   python src/data_preprocessing.py
   ```

4. Latih model Random Forest:
   ```bash
   python src/model_training.py
   ```

5. Evaluasi model:
   ```bash
   python src/evaluation.py
   ```

6. Visualisasikan hasil menggunakan Jupyter Notebooks di folder `notebooks`.

---

## 🤝 Kontributor

| Nama                     | Profil GitHub                              | Email                          |
|--------------------------|---------------------------------------------|--------------------------------|
| **M. Gilang Martiansyah** | [@gilangmartiansyah](https://github.com/gilangmartiansyah) | mgilang.121450056@student.itera.ac.id |
| **Ghozi Alvin Karim**     | [@ghozialvin](https://github.com/ghozialvin)           |                                |
| **Lia Alyani**            | [@liaalyani](https://github.com/liaalyani)             |                                |
| **Nadilla Andhara Putri** | [@nadillaputri](https://github.com/nadillaputri)       |                                |
| **Anisa Dini Amalia**     | [@anisadini](https://github.com/anisadini)             |                                |
| **M. Faqih**              | [@mfaqih](https://github.com/mfaqih)                   |                                |

---

## 📜 Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT. Lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

---

## 🌟 Penghargaan
Terima kasih khusus kepada **Tirta Setiawan, S.Pd., M.Si.**, atas bimbingan dan mentoring dalam proyek ini, serta seluruh anggota tim atas dedikasi dan kolaborasinya!
