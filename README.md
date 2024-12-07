# Model Clustering untuk Segmentasi Nasabah FundFusion 🏦

## Deskripsi Proyek 📓
Proyek ini bertujuan untuk membangun model clustering untuk mengidentifikasi segmen nasabah FundFusion berdasarkan demografi dan perilaku mereka. Dengan memahami karakteristik unik dari setiap segmen, diharapkan dapat meningkatkan efektivitas strategi pemasaran dan penawaran produk.

## Permasalahan 
Saat ini, belum ada strategi yang tepat untuk memasarkan jenis produk yang sesuai dengan segmen bakal calon nasabah.

## Tujuan
- Membuat model clustering untuk mengetahui kepemilikan produk berdasarkan demografi nasabah.
- Mencapai Silhouette Score >0.7 untuk memastikan kualitas clustering yang baik.

Dataset
Dataset yang digunakan berisi informasi demografi dan produk yang dimiliki oleh nasabah FundFusion. Variabel yang digunakan meliputi:
  - Informasi Nasabah: GCIF, Area, Jalur_Pembukaan, Vintage, Usia, Jenis_Kelamin, Status_Perkawinan, Jumlah_Anak, Pendidikan, Pendapatan_Tahunan, Total_Relationship_Balance
  - Informasi Produk: Produk_Tabungan, Produk_Deposito, Produk_Kartu_Kredit, Produk_Kredit_Rumah, Produk_Kredit_Kendaraan, Produk_Kredit_Dana_Tunai, Total_Kepemilikan_Produk   

Eksperimen
Clustering berdasarkan demografi: Menganalisis tren kepemilikan produk pada setiap segmen demografi.
Clustering berdasarkan kelompok produk: Menganalisis profil demografis pengguna pada setiap kelompok produk.

Hasil yang Diharapkan
- Identifikasi segmen nasabah: Mengelompokkan nasabah menjadi beberapa segmen yang berbeda berdasarkan karakteristik mereka.
- Pemahaman kebutuhan nasabah: Memahami kebutuhan dan preferensi masing-masing segmen.
- Peningkatan efektivitas pemasaran: Merancang strategi pemasaran yang lebih efektif dan tertarget untuk setiap segmen.
- Peningkatan penjualan produk: Meningkatkan penjualan produk dengan menawarkan produk yang sesuai dengan kebutuhan masing-masing segmen.

Teknologi yang Digunakan
Bahasa Pemrograman:
Python: Sebagai bahasa pemrograman utama untuk analisis data dan machine learning.

Library:
- Pandas
- NumPy
- Matplotlib dan Seaborn
- Scikit-learn

Algoritma Clustering
- K-Means
- K-Medoids

Metode Evaluasi
- Elbow Method: Untuk menentukan jumlah cluster yang optimal dengan melihat titik belok pada plot inersia.
- Silhouette Score: Untuk mengukur kualitas clustering dengan melihat kohesi dan separasi antar cluster.



❕Analisis Hasil Deployment ❕
  - Clustering berhasil dilakukan dengan Silhoutte Score tertinggi diperoleh 0.5 pada cluster ke-3, yang dimana score ini tidak sesuai obyektif pada Deployment yaitu >0.7
  - Nasabah terbagi tiga cluster. Cluster nol dengan rentang usia nasabah 53-70 tahun cenderung memiliki produk yang sedikit, cluster satu dengan rentang usia 20-37 tahun memiliki jumlah produk yang  bervariasi, dan cluster dua dengan rentang usia nasabah 38 - 52 tahun cenderung memiliki jumlah produk yang paling banyak.
  - Nasabah pada cluster 1 cenderung memiliki produk terbanyak diikuti cluster 2 dan cluster 0.
  - Ketiga cluster memiliki lokasi, vintage, pendidikan, dan jenis kelamin yang cenderung sama yaitu lokasi Jakarta, vintage 2-3 tahun, pendidikan sarjana, dan jenis kelamin laki-laki.

PPT : https://docs.google.com/presentation/d/1dS7Pnw5teLe2fx4Lcz-mIInxFhx56gYbNJD6DK2-Fqw/edit?usp=sharing
