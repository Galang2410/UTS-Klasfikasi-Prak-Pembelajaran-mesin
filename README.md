# 🍊 Klasifikasi Jeruk vs Anggur Menggunakan Naive Bayes

## 🗂️ Dataset
Dataset yang digunakan diambil dari Kaggle: [Oranges vs Grapefruit](https://www.kaggle.com/datasets/joshmcadams/oranges-vs-grapefruit).  
Nama file yang digunakan: `citrus.csv`.

Kolom dalam dataset:
- `name`: nama buah (orange / grapefruit)
- `diameter`: diameter buah
- `weight`: berat buah
- `red`, `green`, `blue`: komponen warna buah

## 🧪 Langkah-langkah Pengerjaan

### 1. Import Library
Menggunakan library Python seperti `pandas`, `sklearn`, dan `seaborn` untuk analisis dan visualisasi data.

### 2. Load dan Eksplorasi Data
- Membaca data dari file `citrus.csv`
- Mengecek jumlah data dan label yang tersedia
- Menampilkan nilai statistik deskriptif

### 3. Preprocessing
- Memastikan hanya dua kelas: `'orange'` dan `'grapefruit'`
- Memisahkan fitur (`X`) dan label (`y`)
- Mengubah label dari string ke bentuk numerik (menggunakan `LabelEncoder`)

### 4. Splitting Data
- Data dibagi menjadi data latih (80%) dan data uji (20%)

### 5. Training Model
- Menggunakan algoritma **Gaussian Naive Bayes**
- Model dilatih menggunakan data latih

### 6. Evaluasi Model
- Menggunakan data uji untuk prediksi
- Mengukur akurasi
- Menampilkan confusion matrix dan classification report

---

##  Hasil Evaluasi

Contoh hasil (dapat berbeda-beda tergantung pembagian data):
- Akurasi: **~92%**
- Confusion Matrix:
[[919  69]
 [ 91 921]]