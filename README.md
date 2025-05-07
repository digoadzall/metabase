
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

Dataset yang digunakan berasal dari github:  
🔗 [[IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)](https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee)

---

## 🛠️ Setup Environment

### 1. Persiapkan lingkungan Python

Di Google Colab, kitak tidak usah perlu khawatir tentang mengaktifkan virtual environment. Colab sudah menggunakan Python versi 3.x secara default. kita bisa mengecek versi Python yang sedang digunakan dengan menjalankan perintah ini di Colab:

!python --version

setelah melihat versi 3.7 mari kita lanjutkan ke selanjutnya

### 2. Install dependensi

Jalankan perintah berikut di terminal:

```bash
pip install pandas scikit-learn joblib seaborn matplotlib
```

Jika menggunakan Google Colab, tidak perlu install manual karena library tersebut sudah tersedia.

### 3. Menjalankan Notebook

Jalankan notebook Jupyter berikut untuk melakukan analisis dan modeling:

📄 `Untitled7.ipynb`

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

Berdasarkan visualisasi yang ditampilkan di dashboard Metabase, beberapa temuan utama terkait attrition karyawan adalah:

- **OverTime**: Karyawan yang melakukan lembur (*OverTime = Yes*) memiliki tingkat keluar yang jauh lebih tinggi dibanding yang tidak lembur.
- **YearsAtCompany**: Mayoritas karyawan yang keluar memiliki masa kerja singkat, terutama di bawah 3 tahun. Hal ini menunjukkan tantangan dalam retensi karyawan baru.
- **MonthlyIncome**: Karyawan dengan pendapatan bulanan yang lebih rendah cenderung lebih sering mengalami attrition.
- **Gender**: Terdapat perbedaan attrition antar gender, dengan karyawan laki-laki menunjukkan angka keluar yang lebih tinggi.
- **JobRole**: Posisi seperti *Sales Executive* dan *Laboratory Technician* memiliki jumlah karyawan keluar yang lebih tinggi dibanding peran lain.
- **Age**: Rentang usia 30–40 tahun mendominasi populasi attrition, meskipun tidak menunjukkan pola yang ekstrem secara distribusi.

---

## 💡 Rekomendasi

- **Kelola lembur**: Batasi lembur dan pastikan ada keseimbangan kerja-hidup yang sehat.
- **Retensi karyawan baru**: Berikan perhatian khusus untuk karyawan dengan masa kerja <3 tahun, seperti program onboarding atau mentorship.
- **Evaluasi kompensasi**: Lakukan evaluasi periodik terhadap struktur gaji, terutama bagi karyawan dengan penghasilan rendah.
- **Program kesejahteraan**: Bangun inisiatif yang mendorong kepuasan kerja dan mendukung pengembangan karier.
- **Pendekatan personalisasi**: Lakukan analisis lebih lanjut berdasarkan usia, gender, dan peran untuk membuat kebijakan HR yang lebih relevan.
