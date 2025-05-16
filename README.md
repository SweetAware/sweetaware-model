# 🍬 SweetAware - Machine Learning Model

Repository ini berisi pengembangan model machine learning untuk proyek **SweetAware**, yang bertujuan memprediksi potensi diabetes berdasarkan faktor-faktor gaya hidup dan kesehatan pengguna.

## 📊 Dataset

Dataset yang digunakan:  
[Diabetes Prediction Dataset - Kaggle](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)

Dataset ini mencakup berbagai fitur seperti usia, jenis kelamin, tingkat aktivitas, konsumsi alkohol, tekanan darah, dan lain-lain, yang berkaitan dengan risiko diabetes.

## 🔍 Tujuan

Mengembangkan dan melatih model prediktif untuk:
- Mendeteksi risiko diabetes secara dini.
- Mendukung sistem rekomendasi kesehatan dalam aplikasi SweetAware.

## 🧠 Model & Teknologi

Model dikembangkan menggunakan:
- Python
- TensorFlow & Keras
- Scikit-learn

Langkah utama dalam pipeline:
1. Load dan eksplorasi data
2. Encoding fitur kategorikal
3. Normalisasi data
4. Split data (train-test)
5. Pelatihan model Neural Network
6. Evaluasi performa model

## 📁 Struktur Notebook

Notebook utama berisi:
- Persiapan data (`pandas`, `LabelEncoder`, `StandardScaler`)
- Implementasi Neural Network menggunakan Keras
- Evaluasi akurasi dan prediksi

## 🚀 Cara Menjalankan

1. Clone repository ini.
2. Pastikan sudah menginstal dependensi berikut:

```bash
pip install -r requirements.txt
