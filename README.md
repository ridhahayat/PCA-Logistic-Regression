# PCA-Logistic-Regression

# 📊 PCA & Logistic Regression pada Dataset Penghasilan (Adult Dataset)

Proyek ini menunjukkan alur kerja *machine learning* secara end-to-end menggunakan **Principal Component Analysis (PCA)** dan **Logistic Regression** pada **Adult Income Dataset** untuk memprediksi apakah penghasilan seseorang melebihi \$50K per tahun.

## 🔧 Tools & Library
- Python, Jupyter Notebook  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn  

## 🧪 Alur Kerja
1. Memuat & mengeksplorasi data (`adult.csv`)
2. Pra-pemrosesan:
   - Menangani Missing Value
   - Encoding fitur kategorikal
   - Normalisasi data
3. Menerapkan PCA untuk mengurangi dimensi  
   (90% variansi tercapai dengan 12 komponen)
4. Melatih model Logistic Regression
5. Evaluasi menggunakan skor akurasi

## 📈 Hasil
- Jumlah komponen PCA optimal: **12**
- Akurasi model: **82.27%**
- PCA berhasil mengurangi dimensi tanpa kehilangan banyak informasi

## 👤 Penulis
Dibuat oleh [Ridha Shanabiel Hayat] 
