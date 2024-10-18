# Model Clustering untuk Segmentasi Nasabah FundFusion #

Deskripsi Proyek
Proyek ini bertujuan untuk membangun model clustering untuk mengidentifikasi segmen nasabah FundFusion berdasarkan demografi dan perilaku mereka. Dengan memahami karakteristik unik dari setiap segmen, diharapkan dapat meningkatkan efektivitas strategi pemasaran dan penawaran produk.

Permasalahan
Saat ini, belum ada strategi yang tepat untuk memasarkan jenis produk yang sesuai dengan segmen bakal calon nasabah.

Tujuan
Membuat model clustering untuk mengetahui kepemilikan produk berdasarkan demografi nasabah.
Mencapai Silhouette Score >0.7 untuk memastikan kualitas clustering yang baik.

Dataset
Dataset yang digunakan berisi informasi demografi dan produk yang dimiliki oleh nasabah FundFusion. Variabel yang digunakan meliputi:
  Informasi Nasabah: GCIF, Area, Jalur_Pembukaan, Vintage, Usia, Jenis_Kelamin, Status_Perkawinan, Jumlah_Anak, Pendidikan, Pendapatan_Tahunan, Total_Relationship_Balance
  Informasi Produk: Produk_Tabungan, Produk_Deposito, Produk_Kartu_Kredit, Produk_Kredit_Rumah, Produk_Kredit_Kendaraan, Produk_Kredit_Dana_Tunai, Total_Kepemilikan_Produk   

Eksperimen
Clustering berdasarkan demografi: Menganalisis tren kepemilikan produk pada setiap segmen demografi.
Clustering berdasarkan kelompok produk: Menganalisis profil demografis pengguna pada setiap kelompok produk.

Hasil yang Diharapkan
Identifikasi segmen nasabah: Mengelompokkan nasabah menjadi beberapa segmen yang berbeda berdasarkan karakteristik mereka.
Pemahaman kebutuhan nasabah: Memahami kebutuhan dan preferensi masing-masing segmen.
Peningkatan efektivitas pemasaran: Merancang strategi pemasaran yang lebih efektif dan tertarget untuk setiap segmen.
Peningkatan penjualan produk: Meningkatkan penjualan produk dengan menawarkan produk yang sesuai dengan kebutuhan masing-masing segmen.

Teknologi yang Digunakan
Bahasa Pemrograman:
Python: Sebagai bahasa pemrograman utama untuk analisis data dan machine learning.

Library:
- Pandas
- NumPy
- Matplotlib dan Seaborn
- Scikit-learn

Algoritma Clustering
K-Means
K-Medoids

Metode Evaluasi
Elbow Method: Untuk menentukan jumlah cluster yang optimal dengan melihat titik belok pada plot inersia.
Silhouette Score: Untuk mengukur kualitas clustering dengan melihat kohesi dan separasi antar cluster.
