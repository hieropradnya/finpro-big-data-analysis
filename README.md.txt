Analisis dan Prediksi Penjualan Makanan di Warung Mie Sam Ndut Lawang Deskripsi Proyek


Deskripsi Proyek

Proyek ini bertujuan untuk melakukan analisis dan prediksi penjualan produk mie menggunakan dataset yang berisi informasi tentang transaksi penjualan di warung Indomie. Analisis yang dilakukan meliputi visualisasi data, identifikasi produk terlaris, serta prediksi penjualan menggunakan Random Forest Regressor.

Proyek ini menggunakan berbagai teknik analisis data dan machine learning, termasuk:

    Visualisasi distribusi penjualan dan tren penjualan
    Analisis produk terlaris dan tidak terlaris
    Segmentasi pelanggan berdasarkan frekuensi pembelian
    Prediksi penjualan dengan model Random Forest

Fitur

    Visualisasi:
        Distribusi jumlah produk terjual berdasarkan jenis
        Produk terlaris dan tidak terlaris
        Distribusi jumlah pembelian
        Tren penjualan harian
        Omset harian
        Segmentasi pelanggan
    Prediksi Penjualan:
        Menggunakan Random Forest Regressor untuk memprediksi penjualan 7 hari ke depan berdasarkan data penjualan sebelumnya.

Teknologi yang Digunakan

    Python
    Pandas: Untuk manipulasi data
    Matplotlib & Seaborn: Untuk visualisasi data
    Scikit-learn: Untuk implementasi model Random Forest
    Numpy: Untuk perhitungan numerik

Instalasi

    Clone repository ini ke lokal Anda:

git clone https://github.com/username/repository-name.git

Install dependencies yang diperlukan:

Pastikan Anda memiliki Python versi terbaru. Kemudian install dependensi yang diperlukan dengan menggunakan pip:

    pip install -r requirements.txt

Cara Menggunakan

    Memuat Data: Anda bisa mengganti file dataset.csv dengan file dataset Anda yang sesuai.

    Pratinjau Data: Untuk melihat pratinjau data yang dimuat, jalankan kode berikut untuk melihat 5 baris pertama:

df.head()

Analisis Data: Anda bisa melakukan berbagai analisis dan visualisasi data dengan menjalankan kode visualisasi yang sudah disediakan di dalam notebook atau script Python.

Membangun dan Melatih Model Prediksi: Untuk melatih model Random Forest dan memprediksi penjualan 7 hari ke depan, Anda bisa menggunakan kode berikut:

    model = RandomForestRegressor(n_estimators=100, random_state=42)
    model.fit(X_train, y_train)

    Setelah pelatihan, model akan memberikan prediksi penjualan yang dapat digunakan untuk perencanaan bisnis lebih lanjut.

Hasil

Hasil dari model prediksi penjualan menunjukkan estimasi penjualan untuk 7 hari ke depan, yang dapat digunakan untuk analisis tren dan perencanaan persediaan. Prediksi tersebut ditampilkan dalam bentuk visualisasi yang menunjukkan perbandingan antara penjualan aktual dan prediksi.