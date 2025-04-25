# Gradient Boosted Trees Regression & Feature Selection

## 📌 Objective
Membangun dan mengevaluasi model regresi menggunakan **Gradient Boosted Trees (GBT)** untuk memprediksi harga rumah berdasarkan fitur-fitur yang tersedia dalam dataset. Proyek ini juga mengeksplorasi metode feature selection menggunakan **MRMR** untuk mengurangi dimensionalitas dan meningkatkan performa prediksi.

## 📚 Dataset
Dataset properti dengan berbagai fitur numerik yang menggambarkan atribut seperti luas area, jumlah kamar, dan lainnya. Target yang diprediksi adalah harga atau nilai properti.

## 🛠️ Tools & Libraries
- Python
- pandas, numpy
- seaborn, matplotlib
- scikit-learn (train_test_split, mean_squared_error)
- xgboost
- mrmr_selection

## 🔍 Modeling Steps
1. Preprocessing dan visualisasi data.
2. Seleksi fitur menggunakan **MRMR (Minimum Redundancy Maximum Relevance)**.
3. Feature scalling dan pembagian data menjadi train dan test set.
4. Pelatihan model Gradient Boosted Trees menggunakan Gradient Boosting Regressor dan XGBoost.
5. Evaluasi performa model dengan metrik RMSE, MAE dan MAPE.
6. Hyperparameter tuning untuk mengoptimalkan performa model.
7. Tentukan model terbaik.

## 📈 Hasil Evaluasi
Model XGBRegressor tanpa hyperparameter sebagai model terbaik karena memiliki rmse paling kecil.

## 🚀 Cara Menjalankan

1. Unduh notebook ini atau buka di Google Colab.
2. Jalankan setiap sel secara berurutan.
3. Perhatikan perbandingan hasil prediksi dan performa model.

