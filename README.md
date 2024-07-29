# PerbandinganAlgoritmaApriori&Fp-Growth

## Angota Kelompok:
1. M. Hadi Syatiri
2. Naufal Dekha Widana

## Note:
File Tugbes Bisa diakses pada Tugbes Data Mining Kelompok 5

## Pendahuluan
- **Latar Belakang**: Perkembangan teknologi informasi telah menghasilkan pertumbuhan data yang besar dalam basis data. Data mining menjadi metode penting untuk mengubah data ini menjadi informasi berharga yang mendukung pengambilan keputusan bisnis. Association Rule Mining adalah teknik data mining yang menemukan hubungan menarik antar item dalam basis data transaksi, berguna dalam berbagai aplikasi seperti analisis keranjang belanja dan deteksi penipuan. Dua algoritma yang sering digunakan untuk ini adalah Apriori dan FP-Growth.
- **Tujuan**: Proyek ini bertujuan memberikan panduan komprehensif tentang perbandingan algoritma Apriori dan FP-Growth, dengan fokus khusus pada kinerja waktu komputasi.
- **Manfaat**: Proyek ini dirancang untuk memberikan wawasan mendalam tentang perbandingan algoritma Apriori dan FP-Growth, membantu praktisi data memilih algoritma yang paling efisien dari segi waktu komputasi, dan mengoptimalkan proses data mining untuk mempercepat pengambilan keputusan berbasis data.

## Tahap Analisis
Proses analisis menggunakan metodologi IBM Data Science
### 1. Understanding the Business
Pada tahap ini, tujuan utama adalah memahami masalah yang ingin dipecahkan, yaitu mengetahui perbandingan antara algoritma Apriori dan FP-Growth. Dengan memahami masalah ini, kita dapat menetapkan tujuan yang jelas untuk proyek data science dan memastikan bahwa semua langkah yang diambil akan mengarah pada penyelesaian masalah tersebut.
### 2. Analytic Approach
Langkah ini melibatkan perumusan pendekatan analitis untuk mencapai tujuan. Pendekatan analitis yang dipilih adalah menggunakan algoritma Association Rule Mining, yaitu Apriori dan FP-Growth, untuk membandingkan efisiensi eksekusi waktu komputasi antara kedua algoritma tersebut.
### 3. Data Requirements
Pada tahap ini, kita akan menentukan data yang diperlukan untuk analisis. Data yang diperlukan meliputi:
1. Member_number
2. Date
3. ItemDescription
### 4. Data Collection
Pada tahap ini, dilakukan proses mengumpulkan data yang telah diidentifikasi. Data ini bisa berasal dari sistem point of sale (POS) supermarket yang mencatat setiap transaksi penjualan. Data ini harus lengkap dan akurat untuk menghasilkan analisis yang berguna.
### 5. Data Understanding
Setelah data dikumpulkan, tahap berikutnya adalah memahami data tersebut. Data yang telah dikumpulkan dianalisis untuk memahami struktur dan kualitasnya. Ini termasuk:
1. Mengumpulkan data mentah dari Kaggle dalam bentuk file CSV.
2. Melihat beberapa baris pertama dari dataset untuk memahami struktur kolom dan nilai.
3. Melakukan visualisasi data untuk eksplorasi lebih lanjut.
### 6. Data Preparation
Beberapa langkah dalam persiapan data meliputi:
1. Encoding: Mengubah data transaksi ke dalam format one hot encoding.
2. Mengonversi data transaksi menjadi format yang sesuai untuk algoritma Apriori dan FP-Growth.
### 7. Modeling
Tahap modeling adalah inti dari proses data science. Pada tahap ini, algoritma Apriori dan FP-Growth digunakan untuk analisis asosiasi. Tahap ini melibatkan:
1. Menjalankan algoritma untuk menemukan frequent itemsets dan association rules.
2. Menginterpretasikan hasil untuk menemukan pola menarik.
### 8. Evaluation
Setelah mendapatkan hasil dari model, langkah penting berikutnya adalah mengevaluasi seberapa efektifnya. Pada tahap ini, akan diukur waktu eksekusi dari algoritma Apriori dan FP-Growth. Selanjutnya, kami akan membandingkan keduanya untuk mengidentifikasi kelebihan dan kekurangan masing-masing dalam hal efisiensi waktu eksekusi.
### 9. Deployment
Perbandingan antara Apriori dan FP-Growth dalam hal deployment akan menyoroti bagaimana masing-masing algoritma berperforma dalam lingkungan produksi nyata. FP-Growth cenderung lebih diunggulkan karena kemampuannya dalam menangani dataset besar dengan lebih efisien daripada Apriori, yang memerlukan lebih banyak waktu eksekusi karena pemindaian database yang berulang. Oleh karena itu, dalam konteks deployment, FP-Growth bisa menjadi pilihan yang lebih baik jika skalabilitas dan efisiensi waktu menjadi faktor kunci.
