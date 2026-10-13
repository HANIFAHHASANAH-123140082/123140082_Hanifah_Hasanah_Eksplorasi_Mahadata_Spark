# Eksplorasi Performa Machine Learning pada Mahadata Menggunakan Apache Spark

Repositori ini memuat kode eksperimen untuk mata kuliah Mahadata. Eksperimen ini melakukan replikasi parsial terhadap artikel jurnal ilmiah bereputasi untuk membandingkan kinerja komputasi dan performa prediksi model Machine Learning terdistribusi menggunakan Apache Spark (Spark MLlib).

---

* **Nama** : Hanifah Hasanah (123140082)
  
---

## Artikel Rujukan
* **Judul Artikel** : *Applying Machine Learning on Big Data With Apache Spark*
* **Penulis** : Elias Dritsas & Maria Trigka (2025)
* **Jurnal** : IEEE Access (Volume 13, Tahun 2025)
* **DOI** : [10.1109/ACCESS.2025.3552042]

---

## Ringkasan Eksperimen
Eksperimen ini berfokus pada tugas klasifikasi biner untuk mendeteksi partikel Higgs Boson :
1. Dataset: Replikasi parsial 50.000 sampel representatif dengan 28 fitur numerik (kinematic features) dan 1 label biner (rasio 65% background dan 35% signal sesuai karakteristik data asli UCI).
2. Framework: Apache Spark 4.0.4 (PySpark MLlib) dengan konfigurasi memori driver 4 GB.
3. Model yang Dibandingkan:
   * Logistic Regression (LR): Model linear parametrik sederhana.
   * Random Forest (RF): Model ensemble tree (20 pohon keputusan, kedalaman maksimum 5).
4. Metrik Pengujian: Waktu latih (training time), waktu prediksi (testing time), Akurasi, F1-Score, dan Area Under ROC (AUC).

---

## Struktur Berkas Repositori
```text
├── 123140082_Hanifah_Hasanah_Eksplorasi_Mahadata_Spark.ipynb   # Notebook utama eksperimen PySpark
├── requirements.txt                                            # Daftar dependensi pustaka Python
├── grafik_perbandingan_model.png                               # Gambar grafik visualisasi hasil uji
└── README                                                      # Dokumentasi dan panduan repositori
