# 📊 Liver Disease Prediction - Study Case 1

<img src="https://dinus.ac.id/wp-content/uploads/2024/11/Logo-Web-Udinus-Putih.png" width="400" alt="UDINUS Logo">

## 🧠 BK Associate Data Scientist  
**Teknik Informatika S1**

---

## 📌 Deskripsi Proyek

Proyek ini merupakan bagian dari studi kasus untuk posisi **BK Associate Data Scientist** di program studi Teknik Informatika. Tujuan dari proyek ini adalah untuk **memprediksi penyakit hati (liver disease)** dengan menggunakan pendekatan *Machine Learning* berbasis dataset klinis dari India.

---

## 📂 Dataset

Dataset yang digunakan adalah **Indian Liver Patient Dataset (ILPD)** yang berasal dari UCI Machine Learning Repository.

- Jumlah data: *583 pasien*
- Atribut: *10 fitur klinis + label*
- Label:
  - `1`: Pasien menderita penyakit hati
  - `2`: Pasien sehat

---

## 🎯 Tujuan Analisis

1. Memprediksi apakah seorang pasien memiliki penyakit hati berdasarkan data klinisnya.
2. Menerapkan berbagai metode analisis data dan klasifikasi.
3. Menilai performa model dengan berbagai metrik evaluasi.

---

## 🛠️ Tools & Library

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn (Visualisasi)
- Scikit-Learn (Modeling dan Evaluasi)

---

## 🔄 Alur Analisis

1. **Import Library**
2. **Load Dataset**
3. **Eksplorasi Data (EDA)**
4. **Preprocessing**
   - Mengatasi missing value
   - Encoding dan scaling
5. **Pemodelan**
   - Logistic Regression
   - K-Nearest Neighbors
   - Decision Tree
   - Random Forest
6. **Evaluasi Model**
   - Accuracy, Precision, Recall, F1 Score
7. **Visualisasi**
   - Confusion Matrix
   - Feature Importance

---

## 📊 Hasil dan Temuan

- Model terbaik dalam prediksi penyakit hati adalah `Random Forest` dengan akurasi mencapai ± **X%**.
- Fitur paling berpengaruh: `Age`, `Total Bilirubin`, `Albumin and Globulin Ratio`.
- Model menunjukkan potensi untuk diterapkan dalam sistem diagnosis awal otomatis.

---

## 📈 Visualisasi Contoh

Beberapa grafik visualisasi dalam notebook meliputi:

- Korelasi antar fitur
- Distribusi pasien penderita vs sehat
- Evaluasi performa model via confusion matrix

---

## ✅ Kesimpulan

Dengan dataset ILPD dan pendekatan machine learning, diagnosis awal penyakit hati dapat dilakukan secara efektif. Model klasifikasi mampu mengenali pola-pola klinis penting yang berkorelasi dengan kondisi hati pasien.

---

## 👨‍🔬 Penulis

**Ephesians Prismaranatha**  
**A11.2022.14632**
Program Studi Teknik Informatika S1  
Universitas Dian Nuswantoro

---

## 📎 Catatan

- Proyek ini adalah bagian dari studi kasus akademik.
- Semua analisis dilakukan tanpa menggunakan bantuan LLM (ChatGPT, Gemini, dsb), sesuai aturan studi kasus.

---

