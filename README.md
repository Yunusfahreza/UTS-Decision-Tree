# UTS-Decision-Tree
# Klasifikasi Sumber Polusi Udara

Proyek ini bertujuan untuk membangun model klasifikasi menggunakan **Decision Tree** untuk memprediksi *label sumber polusi udara* berdasarkan data kualitas udara seperti PM2.5, NOx, dan VOCs. Proyek ini mencakup proses pembersihan data, rekayasa fitur, preprocessing, pelatihan model, optimasi hyperparameter, dan evaluasi model dengan berbagai visualisasi.

---

## 📁 Dataset

Dataset yang digunakan harus dalam format `.csv` dan wajib memiliki kolom sebagai berikut:

- `PM2.5`
- `NOx`
- `VOCs`
- `Location_Type`
- `Source_Label` *(target/label yang akan diprediksi)*

Contoh data disimpan dalam file `air_quality_data.csv`.

---

## 🎯 Tujuan

Tujuan dari proyek ini adalah untuk:

- Mengklasifikasikan tingkat sumber polusi udara (misalnya: *Tinggi*, *Sedang*, *Rendah*)
- Melatih model Decision Tree
- Mengevaluasi kinerja model menggunakan:
  - Classification Report
  - Confusion Matrix
  - Feature Importance
  - Permutation Importance
  - Visualisasi pohon keputusan

---

## 🧰 Tools dan Library yang Digunakan

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Graphviz (untuk visualisasi pohon)

