# Investigate-Hotel-Business-using-Data-Visualization

**Tool** : Jupyter Notebook

**Programming Languange** : Python

**Libraries** : Pandas, NumPy, Matplotlib, Seaborn

**Dataset** : <a href="Dataset/hotel_bookings_data.csv"> Dataset Investigate-Hotel-Business-using-Data-Visualization</a>


## Problem Statement & Background ##

### Backgrounder ###

Sangat penting bagi suatu perusahaan untuk selalu menganalisa performa bisnisnya. Pada kesempatan kali ini akan lebih mendalami bisnis dalam bidang perhotelan. Fokus yang dituju adalah untuk mengetahui bagaimana perilaku pelanggan kita dalam melakukan pemesanan hotel, dan hubungannya terhadap tingkat pembatalan pemesanan hotel. Hasil dari insight yang ditemukan akan di sajikan dalam bentuk data visualisasi agar lebih mudah dipahami dan bersifat lebih persuasif.

### Business Objective ###

1. Menentukan jenis hotel yang paling sering di kunjungi oleh pelanggan
2. Periode hotel yang sering di kunjungi

## Stage 0 - Data Preprocessing ##

<img src="Stage 0/Handling Data Null.PNG" />

### Objective ###

1. Mengecek nilai null dan missing value pada data
2. Mengecek data duplikat
3. Mengubah tipe data
4. Mengecek nilai outlier pada data

## Data Analysis ##

## Stage 1 - Averaging Booking Hotel Period ##

<img src="Stage 1/Average Booking Hotel.PNG" />

### Insight ###

1. Kedua hotel memiliki jumlah tamu lebih banyak pada periode liburan dibandingkan periode biasanya.

2. Pengunjung city hotel relatif lebih banyak di bandingkan pengunjung resort hotel.

3. Terjadi penurunan drastis pengunjung atau tamu city hotel pada periode bulan Agustus – September.

4. Periode liburan bulan May – Juli tamu atau pengunjung di kedua hotel naik, dengan asumsi bahwa pada periode ini adalah periode libur sekolah sehingga banyak tamu berlibur bersama keluarga.

## Stage 2 - Impact Analysis of Stay Duration on Hotel Bookings Cancellation Rates ##

<img src="Stage 2/Trend Book and Stay Duration.PNG" />

### Insight ###

1. Semakin lama tamu memesan durasi menginap maka presentase pembatalan pemesanan hotel menjadi meningkat / semakin kecilnya proses pembatalan.

2. Hotel di perkotaan cenderung memiliki trend yang sangat positif dibanding dengan hotel resor dilihat dari total durasi penginapan dan minimnya presentase pembatalan pemesanan hotel.

## Stage 3 - Impact Analysis of Lead Time on Hotel Bookings Cancellation Rate ##

<img src="Stage 3/Ratio Percentage Cancelation Rates.PNG" />

### Insight ###

1. Tingkat pembatalan pemesanan paling rendah ada pada pemesanan yang memiliki waktu tunggu kurang dari 30 hari dan berlaku untuk kedua jenis hotel. 

2. Hotel resort cukup stagnan dengan nilai 40% rasio pembatalan, sedangkan hotel jenis perkotaan memiliki rasio yang cukup tinggi 60% ketika waktu tunggu sekitar 1 tahun.

3. Hal ini bisa terjadi akibat perubahan rencana atau situasi dari tiap tiap pengunjung yang tidak bisa di prediksi. Semakin pendek waktu pemesanan maka tingkat perubahan rencana secara mendadak semakin minim, pihak hotel sebaiknya menanyakan secara berkala kepada pengunjung hotel yang melakukan pemesanan diatas dari 1 bulan atau lebih dari jatuh tempo hari penginapan

## Summary ##

Kedua hotel memiliki peningkatan jumlah pengunjung pada periode liburan, 

**Saran** : 

1. Sebaiknya pada periode tersebut pihak hotel dapat memberikan diskon lebih dan promo menarik diluar dari periode liburan untuk meningkatkan antusias pengunjung untuk menginap di hotel misalkan pada libur nasional dll.

Semakin lama pengunjung menginap maka semakin minim juga presentase pengunjung untuk melakukan cancel booking hal ini didasari dengan presentase tren dari kedua hotel

**Saran** : 

1. Dengan adanya promo menarik mengenai lama durasi pengunjung untuk menginap , maka akan membuat pengunjung menjadi lebih tertarik untuk melakukan penginapan dengan jangka yang lama.

2. Tingkat pembatalan pemesanan paling rendah ada pada pemesanan yang memiliki waktu tunggu kurang dari 30 hari dan berlaku untuk kedua jenis hotel. 

3. Hotel resort cukup stagnan dengan nilai 40% rasio pembatalan, sedangkan hotel jenis perkotaan memiliki rasio yang cukup tinggi 60% ketika waktu tunggu sekitar 1 tahun.


