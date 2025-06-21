# 🌸 Iris Exploration

## Project Title  
**Iris Exploration** – aplikasi web interaktif untuk eksplorasi data dan prediksi spesies bunga Iris.

---

## Description  
Aplikasi ini memungkinkan pengguna untuk:  
- Menjelajahi dataset Iris,  
- Melihat visualisasi (scatter plot, histogram, heatmap),  
- Memprediksi jenis bunga Iris (*setosa*, *versicolor*, atau *virginica*) berdasarkan input fitur sepal dan petal menggunakan model machine learning.

---

## Technologies Used  
- **Python**  
- **Streamlit** – antarmuka web  
- **scikit-learn** – model klasifikasi  
- **pandas**, **numpy** – manipulasi data  
- **matplotlib**, **seaborn** – visualisasi  
- **pickle** – menyimpan dan memuat model (`generate_iris.pkl`)

---

## Features  
- 📊 Tampilkan seluruh dataset Iris beserta statistik dasar  
- 📈 Visualisasi data (scatter plot, histogram, heatmap korelasi)  
- ✍️ Input manual panjang/lebar sepal & petal  
- 🔍 Prediksi spesies bunga lengkap dengan probabilitasnya

---

## Setup Instructions  
1. **Clone repo**  
   ```bash
   git clone https://github.com/PrimeFox59/iris_exploration.git
   cd iris_exploration

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```
3. **Jalankan aplikasi**

   ```bash
   streamlit run iris_app.py
   ```
4. **Akses aplikasi**:

   * **Lokal**: buka `http://localhost:8501`
   * **Online**: [iris-exploration‑prima.streamlit.app](https://iris-exploration-prima.streamlit.app/)

---

## AI Support Explanation

Model klasifikasi disimpan sebagai `generate_iris.pkl`. Ketika pengguna memasukkan input sepal dan petal:

1. Aplikasi memuat model dari file pickle.
2. Model menghitung prediksi spesies dan probabilitasnya.
3. Hasil ditampilkan secara real-time lengkap dengan interpretasi visual.
