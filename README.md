# 📊 Submission: Klasifikasi - Dicoding

Proyek ini merupakan bagian dari submission kelas Machine Learning terapan di platform Dicoding. Fokus utama dari proyek ini adalah membangun model klasifikasi berdasarkan hasil clustering dari dataset penjualan minuman.

## 📝 Deskripsi Proyek

Notebook ini mengimplementasikan tahapan **klasifikasi supervised learning** menggunakan dataset hasil clustering yang telah dilakukan pada tahap sebelumnya. Proyek ini bertujuan untuk:

- Mengklasifikasikan data ke dalam cluster yang telah dibentuk sebelumnya.
- Mengevaluasi performa model klasifikasi menggunakan metrik akurasi dan classification report.

## 📁 Dataset

Dataset yang digunakan adalah `hasil_clustering_akhir.csv`, yang merupakan hasil dari proses clustering pada dataset penjualan minuman. Dataset ini memiliki beberapa fitur numerik dan kategorikal yang telah diproses sebelumnya.

**Fitur utama** dalam dataset:
- `store_id`
- `product_id`
- `price`
- `quantity`
- `revenue`
- `cluster` (label target hasil clustering)

## ⚙️ Tahapan Proyek

1. **Import Library & Load Data**  
   Memuat pustaka penting dan membaca dataset hasil clustering.

2. **Pra-Pemrosesan Data**  
   - Memisahkan fitur dan label  
   - Melakukan splitting data (train-test)  
   - Normalisasi fitur numerik  

3. **Pelatihan Model Klasifikasi**  
   Model yang digunakan:
   - Decision Tree
   - Random Forest
   - K-Nearest Neighbors (KNN)
   - Support Vector Machine (SVM)

4. **Evaluasi Model**  
   - Mengukur akurasi  
   - Menampilkan classification report (precision, recall, f1-score)  
   - Menentukan model terbaik berdasarkan skor evaluasi  

5. **Visualisasi**  
   Visualisasi matriks kebingungan dan distribusi label prediksi untuk model terbaik.

## 📈 Hasil Evaluasi

Model terbaik yang diperoleh dalam eksperimen ini adalah **Random Forest Classifier**, dengan hasil evaluasi sebagai berikut:

- **Akurasi**: *(Isi nilai akurasi terbaik di sini)*  
- **Precision, Recall, F1-score**: Disajikan dalam classification report di notebook.

## 🧠 Kesimpulan

Model klasifikasi mampu mengenali pola dari data hasil clustering dengan cukup baik, khususnya dengan algoritma Random Forest yang memberikan hasil evaluasi terbaik. Proyek ini menunjukkan pentingnya tahapan preprocessing dan pemilihan model dalam pipeline klasifikasi.

## 🚀 Tools & Teknologi

- Python  
- Scikit-learn  
- Pandas, NumPy, Matplotlib, Seaborn  
- Google Colab
