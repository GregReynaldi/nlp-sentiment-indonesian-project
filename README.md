# Project 6 - Analisis Sentimen Tweet Bahasa Indonesia

Proyek ini merupakan implementasi analisis sentimen otomatis pada data tweet berbahasa Indonesia menggunakan berbagai pendekatan Machine Learning dan Deep Learning. Tujuannya adalah untuk mengembangkan model yang dapat secara akurat mengklasifikasikan tweet ke dalam kategori sentimen positif, negatif, atau netral.

## Deskripsi Proyek

Proyek ini dirancang untuk mengatasi tantangan dalam analisis sentimen Bahasa Indonesia, yang memiliki karakteristik linguistik unik seperti slang, kode campur, dan emotikon yang sering digunakan dalam media sosial. Penelitian ini membandingkan kinerja berbagai metode analisis sentimen, mulai dari pendekatan tradisional hingga model deep learning modern.

Berikut adalah metode-metode yang diimplementasikan:
- **Machine Learning Klasik**: Random Forest, Naive Bayes, XGBoost dengan ekstraksi fitur CountVectoriz
- **Deep Learning**: Jaringan saraf tiruan berbasis CNN (Convolutional Neural Network), LSTM (Long Short-Term Memory), dan Simple RNN
- **Transformers**: Model berbasis arsitektur Transformer yang mampu menangkap konteks jangka panjang dalam teks
- **Ensemble Methods**: Voting Classifier yang menggabungkan hasil dari beberapa model untuk meningkatkan akurasi prediksi

Dataset yang digunakan terdiri dari tweet berbahasa Indonesia yang telah diberi label sentimen, yang melalui proses pra-pemrosesan untuk membersihkan dan menstandarisasi teks sebelum dianalisis.

## Struktur Proyek

```
├── code_project_final.ipynb   # Notebook utama dengan semua metode ML dan DL
├── code_project_transformers.ipynb # Notebook khusus implementasi Transformer
├── tweet.csv                  # Data tweet yang digunakan untuk analisis
```

## Cara Menggunakan

1. Clone repository ini
2. Install dependensi dengan menjalankan:
   ```
   pip install -r requirements.txt
   ```
3. Jalankan notebook sesuai kebutuhan: `code_project_final.ipynb` atau `code_project_transformers.ipynb`

## Prasyarat

- Python 3.10
- Jupyter Notebook
- Library yang tercantum dalam requirements.txt

## Hasil

Hasil evaluasi model (confusion matrix, accuracy) dapat dilihat di dalam notebook dan PDF File.

## Kontributors
- Gregorius Reynaldi Pratama