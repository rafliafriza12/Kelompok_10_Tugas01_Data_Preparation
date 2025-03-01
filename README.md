# Kelompok_10_Tugas01_Data_Preparation

## Deskripsi Proyek
Repositori ini berisi tugas kelompok untuk mata kuliah **Pembelajaran Mesin**, yang bertujuan untuk memahami proses **data preparation** sebelum digunakan dalam analisis atau pelatihan model machine learning. Dataset yang digunakan adalah **Earthquakes in Indonesia** dari Kaggle.

## Dataset
- **Nama Dataset**: Earthquakes in Indonesia
- **Sumber**: [Kaggle](https://www.kaggle.com/datasets/kekavigi/earthquakes-in-indonesia?select=katalog_gempa.csv)
- **Format Data**: CSV
- **Jumlah Sampel**: 92.887
- **Jumlah Fitur**: 13
- **Deskripsi**: Dataset ini berisi catatan kejadian gempa bumi di Indonesia, termasuk informasi tanggal, lokasi, kedalaman, magnitudo, dan mekanisme patahan.

## Tahapan Proses
1. **Data Loading**
   - Dataset dimuat menggunakan `pandas.read_csv()`
   - Melihat informasi awal dataset (`df.info()`, `df.head()`)

2. **Data Understanding**
   - Melihat distribusi data dengan histogram dan boxplot
   - Menghitung jumlah missing values di setiap kolom
   - Menganalisis korelasi antar fitur

3. **Data Preparation**
   - Memisahkan kolom tanggal menjadi tahun, bulan, dan hari
   - Mengubah data kategorikal menjadi numerik menggunakan Label Encoding
   - Membagi dataset menjadi tiga:
     - **df**: Dataset lengkap tanpa perubahan signifikan
     - **df1**: Dataset umum dengan kolom redundan dihapus
     - **df2**: Dataset khusus yang hanya berisi data dengan fitur lengkap


## Contributor (Kelompok 10)
- [Muhammad Habil Aswad] (2208107010013)
- [Rafli Afriza Nugraha] (2208107010028)
- [Muhammad Khalid Al Ghifari] (2208107010044)
- [Muhammad Ridho] (2208107010064)
- [Muhammad Ilzam] (2208107010087)


