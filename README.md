# 📈 Prediksi Harga Saham TLKM Menggunakan Metode Hybrid LSTM-GRU, BiLSTM, dan BiGRU

Proyek ini merupakan implementasi dari penelitian tugas akhir yang bertujuan memprediksi harga saham **Telkom Indonesia (TLKM)** menggunakan pendekatan **deep learning**. Model yang diuji meliputi:
- Hybrid LSTM-GRU
- BiLSTM
- BiGRU

---

## 🎯 Tujuan
Menganalisis performa berbagai arsitektur deep learning dalam memprediksi harga saham berbasis time series, dan membandingkan hasilnya menggunakan metrik evaluasi RMSE, MAPE, dan R².

---

## 📂 Dataset
- **Sumber**: Yahoo Finance
- **Periode**: Juni 2014 - Juni 2024
- **Fitur**: Open, High, Low, Close, Adj Close

---

## 🛠 Tools & Teknologi
- Python
- TensorFlow, Keras
- Scikit-learn
- Pandas, Numpy, Matplotlib
- Google Colab

---

## ✅ Langkah Analisis
1. **EDA**:
   - Analisis deskriptif menggunakan metode statistik 
2. **Data Preprocessing**:
   - Cleaning Data
   - Normalisasi data dengan MinMaxScaler
   - Membuat Sliding Windows
3. **Modeling**:
   - membuat model Hybrid LSTM-GRU, BiLSTM, BiGRU
4. **Evaluasi**:
   - RMSE, MAPE, dan R²
5. **Visualisasi**:
   - Grafik harga aktual vs prediksi

---

## ✅ Insight
- **Model Terbaik**: Hybrid LSTM-GRU
- **RMSE**: 0.0107
- **MAPE**: 0.0167
- **R²**: 99.54%

📊 **Visualisasi Hasil**
![Grafik Prediksi](grafik_prediksi.png)

---

