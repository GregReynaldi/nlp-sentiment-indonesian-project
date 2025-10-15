# Analisis Sentimen Tweet Bahasa Indonesia

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-%E2%9C%94-green.svg)](https://scikit-learn.org/)
[![Deep Learning](https://img.shields.io/badge/Deep%20Learning-%E2%9C%94-red.svg)](https://www.tensorflow.org/)
[![Transformers](https://img.shields.io/badge/Transformers-%E2%9C%94-purple.svg)](https://huggingface.co/)

</div>

## 📊 Project Overview

Proyek ini merupakan implementasi **analisis sentimen otomatis** pada data tweet berbahasa Indonesia menggunakan berbagai pendekatan Machine Learning dan Deep Learning. Tujuan utamanya adalah mengembangkan model yang dapat secara akurat mengklasifikasikan tweet ke dalam kategori sentimen positif, negatif, atau netral.

Analisis sentimen Bahasa Indonesia memiliki tantangan unik karena karakteristik linguistiknya, termasuk penggunaan slang, kode campur, emotikon, dan struktur kalimat yang berbeda dari bahasa Inggris. Proyek ini membandingkan kinerja berbagai metode untuk mengatasi tantangan tersebut.

## ✨ Key Features

- Implementasi **berbagai algoritma Machine Learning dan Deep Learning** untuk analisis sentimen Bahasa Indonesia
- Perbandingan performa model klasik, jaringan saraf tiruan, dan model berbasis Transformer
- Penggunaan **ensemble methods** untuk meningkatkan akurasi prediksi
- Proses **pra-pemrosesan teks** khusus untuk Bahasa Indonesia (pembersihan, normalisasi, dan transformasi)
- Model-model yang telah dilatih dan siap digunakan (disimpan dalam format .pkl)
- Dokumentasi lengkap dan contoh penggunaan

## 🛠️ Technologies Used

| Kategori | Teknologi | Keterangan |
|----------|-----------|------------|
| **Bahasa Pemrograman** | Python 3.10 | Bahasa utama proyek |
| **Machine Learning** | scikit-learn, XGBoost, CatBoost | Implementasi model klasik |
| **Deep Learning** | TensorFlow, Keras | Jaringan saraf tiruan |
| **NLP** | NLTK, Transformers (Hugging Face) | Pengolahan teks dan model berbasis Transformer |
| **Visualisasi** | Matplotlib, Seaborn | Visualisasi hasil dan evaluasi model |
| **Data Manipulation** | NumPy, Pandas | Pengolahan dan analisis data |
| **Lingkungan Pengembangan** | Jupyter Notebook | Pengembangan dan demonstrasi |

## 📁 Project Structure

```
├── CONTRIBUTING.md               # Panduan untuk kontributor
├── LICENSE                       # Lisensi proyek
├── Project 1 - Gregorius Reynaldi Pratama.pdf # Laporan proyek dalam format PDF
├── code_project_final.ipynb      # Notebook utama dengan semua metode ML dan DL
├── code_project_transformers.ipynb # Notebook khusus implementasi Transformer
├── hasil.txt                     # Hasil sementara analisis
├── requirements.txt              # Daftar dependensi proyek
└── tweet.csv                     # Data tweet utama yang digunakan untuk analisis
```

## 📈 Methodology

Proyek ini mengimplementasikan berbagai metode analisis sentimen, meliputi:

### 1. Machine Learning Klasik
- **Random Forest**: Ensemble learning yang membangun banyak decision tree dan menggabungkan hasilnya
- **Naive Bayes**: Model probabilistik berdasarkan teorema Bayes dengan asumsi independensi antar fitur
- **XGBoost**: Gradient boosting framework yang efisien dan powerful

Semua model klasik menggunakan **CountVectorizer** untuk ekstraksi fitur dari teks.

### 2. Deep Learning
- **CNN (Convolutional Neural Network)**: Jaringan yang efektif untuk mengenali pola lokal dalam teks
- **LSTM (Long Short-Term Memory)**: Tipe RNN yang mampu menangani dependensi jangka panjang dalam data urutan
- **Simple RNN**: Jaringan saraf berulang dasar untuk memproses data urutan

### 3. Transformers
- Model berbasis arsitektur Transformer yang mampu menangkap konteks jangka panjang dalam teks melalui mekanisme attention
- Menggunakan pre-trained model yang di-fine-tuning untuk tugas analisis sentimen Bahasa Indonesia

### 4. Ensemble Methods
- **Voting Classifier**: Menggabungkan hasil prediksi dari beberapa model untuk meningkatkan akurasi dan stabilitas

## 🚀 Getting Started

### Prasyarat
- Python 3.10
- Jupyter Notebook
- Semua library yang tercantum dalam requirements.txt

### Installation

1. Clone repository ini
   ```bash
   git clone https://github.com/GregReynaldi/nlp-sentiment-indonesian-project
   ```

2. Install dependensi dengan menjalankan:
   ```bash
   pip install -r requirements.txt
   ```

3. Jalankan Jupyter Notebook
   ```bash
   jupyter notebook
   ```

## 💡 Usage

1. Buka notebook yang diinginkan:
   - `code_project_final.ipynb` untuk melihat semua metode Machine Learning dan Deep Learning
   - `code_project_transformers.ipynb` untuk melihat implementasi khusus Transformer

2. Ikuti langkah-langkah dalam notebook untuk:
   - Memuat dan memproses data
   - Melatih model
   - Mengevaluasi performa model
   - Menggunakan model untuk prediksi

3. Menggunakan model yang telah dilatih:
   ```python
   import pickle
   
   # Memuat model
   with open('model_voting.pkl', 'rb') as file:
       model = pickle.load(file)

## 📊 Results

Hasil evaluasi model (confusion matrix, accuracy, precision, recall, F1-score) dapat dilihat secara detail di dalam notebook dan laporan PDF (`Project 1 - Gregorius Reynaldi Pratama.pdf`).

## 🤝 Contributing

Kontribusi sangat diterima! Silakan lihat [CONTRIBUTING.md](CONTRIBUTING.md) untuk panduan详细 tentang cara berkontribusi pada proyek ini.

## 📄 License

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

## 🙏 Acknowledgments

- Terima kasih kepada semua sumber data dan referensi yang digunakan dalam proyek ini
- Terima kasih kepada komunitas open source yang telah menyediakan berbagai library dan alat yang digunakan

## 👨‍💻 Author

- **Gregorius Reynaldi Pratama**

---

<div align="center">
  <strong>Analisis Sentimen Tweet Bahasa Indonesia</strong> • Dibangun dengan 💙 untuk pengembangan NLP Bahasa Indonesia
</div>