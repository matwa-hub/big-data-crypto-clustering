# Analisis Perbandingan Return Kripto: Ethereum, Dogecoin, dan Litecoin

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<matwa-hub>/<big-data-crypto-clustering>/blob/main/notebooks/825230133_Matius.ipynb)

**Author:** Matius Wahyu Abadi  
**Project Type:** Ujian Big Data

---

## 📌 Deskripsi singkat
Proyek ini menganalisis **return harian** dari tiga kripto: **Ethereum (ETH)**, **Dogecoin (DOGE)**, dan **Litecoin (LTC)**. Analisis mencakup preprocessing data, perhitungan return, penerapan **K-Means Clustering** dan **Fuzzy C-Means Clustering**, visualisasi, dan evaluasi dengan metrik seperti *silhouette score*.

---

## 📂 File penting di repository
- `report/UAS_825230133_Matius.pdf` — Laporan final (PDF).  
- `data/Data_825230133_Matius.xlsx` — Dataset harga harian (Excel).  
- `notebooks/825230133_Matius.ipynb` — Jupyter Notebook analisis (kode Python).

---

## 📊 Hasil ringkas
| Metode              | Silhouette Score |
|---------------------|------------------|
| **K-Means**         | 0.6605 |
| **Fuzzy C-Means**   | 0.3786 |

Lihat `report/UAS_825230133_Matius.pdf` untuk pembahasan lengkap dan interpretasi hasil.

---

## 🧭 Cara menggunakan dataset & notebook
1. **Download repo** atau buka langsung notebook di Colab (klik badge di atas).  
2. Jika menjalankan lokal:
```bash
pip install -r requirements.txt
jupyter notebook notebooks/825230133_Matius.ipynb
