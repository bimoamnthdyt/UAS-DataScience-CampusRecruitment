UAS Data Science - Campus Recruitment Placement Prediction

📌 Deskripsi Proyek

Proyek ini merupakan tugas Ujian Akhir Semester (UAS) mata kuliah Data Science yang bertujuan untuk menganalisis faktor-faktor akademik dan employability yang mempengaruhi keberhasilan penempatan kerja (placement) mahasiswa melalui program Campus Recruitment.

Permasalahan utama:
- Tidak semua mahasiswa berhasil mendapatkan placement
- Tingkat keberhasilan placement berbeda-beda
- Belum tersedia model prediksi berbasis data

Melalui pendekatan Machine Learning, proyek ini membangun model klasifikasi untuk memprediksi status placement mahasiswa.

🎯 Tujuan Bisnis
1. Meningkatkan tingkat keberhasilan placement mahasiswa
2. Mengidentifikasi faktor akademik dan employability yang paling berpengaruh
3. Memberikan rekomendasi strategis untuk peningkatan kualitas lulusan

---

🎯 Tujuan Data Science
1. Membangun model klasifikasi untuk memprediksi status placement
2. Mengukur kontribusi masing-masing variabel
3. Mengevaluasi performa model secara kuantitatif


📊 Dataset
Dataset berisi data historis mahasiswa dengan variabel:
- Jenis kelamin
- Nilai rata-rata SMP & SMA
- Lembaga pendidikan
- Jurusan SMA
- IPK
- Program studi
- Pengalaman kerja
- Nilai tes kemampuan kerja
- Pendidikan pascasarjana
- Status placement (Target)
- Gaji

Target variabel:
- **Status Kelulusan (Placed / Not Placed)**

---

🛠️ Tahapan Data Science
1. Data Understanding
2. Data Cleaning
3. Data Preprocessing
   - Imputasi missing values
   - Encoding variabel kategorikal
   - Scaling fitur numerik
4. Data Splitting (Train-Test 80:20)
5. Modeling
6. Evaluasi Model
7. Interpretasi Hasil

---

🤖 Model yang Digunakan
- Logistic Regression
- Random Forest Classifier

---

📈 Evaluasi Model
Metode evaluasi yang digunakan:
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve
- AUC Score

Model terbaik dipilih berdasarkan performa akurasi dan ROC-AUC tertinggi.

---
💡 Insight Hasil Analisis

Berdasarkan hasil pemodelan:
- IPK memiliki pengaruh signifikan terhadap keberhasilan placement
- Nilai akademik SMA dan tes kemampuan kerja berkontribusi terhadap peluang diterima
- Pengalaman kerja meningkatkan kemungkinan placement
- Faktor akademik menjadi determinan utama dibanding faktor lainnya

---

🏫 Rekomendasi untuk Perguruan Tinggi
1. Monitoring performa IPK mahasiswa sejak awal perkuliahan
2. Meningkatkan program pelatihan tes kemampuan kerja
3. Memperluas program magang dan pengalaman industri
4. Memberikan pendampingan khusus bagi mahasiswa dengan risiko tidak placement

---

🧰 Tools & Library
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

📌 Kesimpulan
Model Machine Learning berhasil memprediksi status placement mahasiswa dengan performa yang baik. Faktor akademik terutama IPK menjadi variabel paling dominan dalam menentukan keberhasilan placement.

Proyek ini menunjukkan bahwa pendekatan Data Science dapat membantu perguruan tinggi dalam pengambilan keputusan strategis berbasis data.

---

👨‍💻 Author
Nama: Bimo Amanta Hidayat 
Mata Kuliah: Data Science  
Tugas: UAS  
