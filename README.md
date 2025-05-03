
# 🧠 Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## 💼 Business Understanding

Perusahaan Edutech menghadapi tantangan tingginya tingkat *attrition* atau karyawan keluar, yang menyebabkan peningkatan biaya rekrutmen dan pelatihan, serta gangguan terhadap stabilitas operasional.

### Permasalahan Bisnis:
- Tingginya tingkat keluar karyawan (*attrition rate*).
- HR kesulitan memahami faktor-faktor utama yang menyebabkan karyawan keluar.
- Belum tersedia alat bantu visualisasi dan prediksi untuk membantu pengambilan keputusan.

### Cakupan Proyek:
- Melakukan analisis data karyawan untuk mengeksplorasi pola dan faktor penyebab *attrition*.
- Membangun model prediksi *attrition* menggunakan machine learning.
- Menyediakan dashboard bisnis interaktif menggunakan Metabase.

---

## 📊 Sumber Data

Dataset yang digunakan berasal dari Kaggle:  
🔗 [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## 🛠️ Setup Environment

### 1. Persiapkan lingkungan Python

Pastikan kamu menggunakan Python 3.7 atau lebih baru. Disarankan menggunakan virtual environment seperti `venv` atau `conda`.

### 2. Install dependensi

Jalankan perintah berikut di terminal:

```bash
pip install pandas scikit-learn joblib seaborn matplotlib
```

Jika menggunakan Google Colab, tidak perlu install manual karena library tersebut sudah tersedia.

### 3. Menjalankan Notebook

Jalankan notebook Jupyter berikut untuk melakukan analisis dan modeling:

📄 `Notebook_EDA_Complete.ipynb`

Pastikan file `employee_data.csv` ada di direktori yang sama sebelum menjalankan notebook.

### 4. Menjalankan Dashboard di Metabase

Metabase digunakan untuk membuat dashboard berbasis visualisasi dari data yang sama.

Langkah-langkah:
- Pastikan Metabase sudah terinstal dan berjalan di lokal atau server.
- Upload data `employee_data.csv` ke Metabase.
- Buat dashboard dengan visualisasi seperti:
  - Distribusi Attrition
  - Rata-rata MonthlyIncome
  - Distribusi berdasarkan JobRole, Gender, OverTime, dll.
- Gunakan akun:
  - **Username**: `root@mail.com`
  - **Password**: `root123`

---

## ✅ Hasil Analisis

Faktor-faktor utama yang berkorelasi dengan attrition:
- **OverTime**: Lembur berkepanjangan meningkatkan kemungkinan keluar.
- **JobSatisfaction**: Semakin rendah kepuasan kerja, semakin besar kemungkinan keluar.
- **DistanceFromHome**: Jarak rumah yang jauh turut memperbesar risiko.
- **MonthlyIncome**: Gaji rendah cenderung dikaitkan dengan attrition.

Model prediksi menggunakan Random Forest menunjukkan akurasi yang baik dan dapat dijadikan dasar pengambilan keputusan.

---

## 💡 Rekomendasi

- Kontrol lembur dan pantau jam kerja secara berkala.
- Adakan program engagement untuk meningkatkan kepuasan kerja.
- Evaluasi dan revisi skema kompensasi secara rutin.
- Berikan opsi kerja fleksibel untuk karyawan yang tinggal jauh.
