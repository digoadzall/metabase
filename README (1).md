# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding
Perusahaan Edutech mengalami masalah tingginya angka attrition rate (tingkat karyawan keluar).
Tingginya attrition menyebabkan biaya rekrutmen dan pelatihan bertambah serta mengganggu produktivitas perusahaan.

### Permasalahan Bisnis

- Tingginya tingkat keluar karyawan (attrition rate).
- HR kesulitan dalam memonitor faktor-faktor yang menyebabkan karyawan keluar.
- Tidak adanya alat bantu visualisasi untuk memahami kondisi karyawan.

### Cakupan Proyek
- Melakukan analisis data employee untuk mencari faktor yang mempengaruhi attrition.
- Membuat dashboard bisnis untuk membantu HR dalam memonitor faktor-faktor tersebut.
- Membangun model machine learning sederhana untuk memprediksi kemungkinan attrition karyawan.

### Persiapan

Sumber data: Data employee yang memuat informasi karyawan seperti usia, jenis kelamin, jabatan, departemen, gaji, serta status attrition.

Setup environment:
```
- Python 3.x
- Libraries: pandas, scikit-learn, joblib
- Metabase untuk pembuatan dashboard
```

## Business Dashboard

Business dashboard dibuat menggunakan Metabase.
Dashboard ini menampilkan beberapa visualisasi penting seperti:
- Jumlah total karyawan.
- Distribusi usia karyawan.
- Jumlah karyawan berdasarkan job role.
- Persentase karyawan yang mengalami attrition.
- Rata-rata jarak rumah ke kantor.
- Faktor-faktor utama yang mempengaruhi tingginya attrition.

Akun untuk akses Metabase:
Username: root@mail.com
Password: root123
Dashboard ini membantu tim HR dalam memantau kondisi tenaga kerja dan mengambil keputusan berbasis data.
  
## Conclusion
Berdasarkan analisis yang dilakukan, faktor-faktor yang berhubungan dengan tingginya attrition antara lain:
- OverTime: Karyawan yang lembur lebih sering mengalami attrition.
- JobSatisfaction: Karyawan dengan tingkat kepuasan kerja rendah lebih rentan keluar.
- DistanceFromHome: Karyawan dengan jarak tempuh jauh lebih rentan mengalami attrition.
- MonthlyIncome: Gaji yang lebih rendah berkorelasi dengan tingkat keluar yang lebih tinggi.
- Model machine learning berbasis Random Forest yang dibangun menunjukkan performa akurasi yang cukup baik dalam memprediksi kemungkinan attrition.

### Rekomendasi Action Items (Optional)

- Meningkatkan kepuasan kerja melalui program employee engagement dan survey rutin.
- Mengelola jam kerja lembur agar tidak terlalu berlebihan.
- Memberikan kompensasi tambahan atau opsi kerja fleksibel bagi karyawan dengan jarak rumah yang jauh.
- Meningkatkan kesejahteraan dengan penyesuaian gaji atau bonus untuk mempertahankan karyawan berpotensi.
