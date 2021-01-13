# LSTM-Pytorch
Covid-19’s death prediction in Indonesia using LSTM Time Series in Pytorch

This code was used as my final project in Deep Learning Course in Brawijaya University

### What is this project about
Projek ini merupakan prediksi jumlah kematian akibat Covid-19 di Indonesia berdasarkan data Covid-19 di Indonesia oleh 'kawalcovid19'. Prediksi dilakukan dengan menggunakan algoritma LSTM Time Series yang dikerjakan dengan menggunakan Library Pytorch. Tentu saja projek ini tidak digunakan untuk memprediksi nilai yang sebenarnya, namun digunakan sebagai pembelajaran dan pengimplementasian akan algoritma LSTM Time Series dalam suatu kasus nyata.

### What are we doing here
Di projek ini dilakukan 5 kali perhitungan, yaitu perhitungan untuk memprediksi 28 data terakhir, 14 data terakhir, 7 data terakhir, 2 data terakhir, serta memprediksi 28 data kedepannya. Perhitungan untuk memprediksi n data terakhir selanjutnya digunakan sebagai perbandingan dengan data sebenarnya dan dicari nilai errornya menggunakan Mean Square Error. Dikarenakan dilakukan 5 kali perhitungan, maka tiap ganti perhitungan dilakukan proses komputasi dari awal, dari mulai dari training, modelling, dan proses lainnya, sehingga secara total akan memakan waktu komputasi yang lama

### About Dataset
Dataset diambil dari Sinta Ristekbrin (Science and Technology Kementerian Riset dan Teknologi / Badan Riset dan Inovasi Nasional) yang dimiliki oleh 'kawalcovid19'. Dataset memiliki data lengkap tentang kasus Covid-19 di Indonesia mulai dari kasus, kesembuhan, dan kematian, untuk tiap data baru, data total, dan data aktif saat ini. Di projek ini, diambil satu sheet dari dataset, yaitu sheet 'Statistik Harian', dan disimpan dalam google drive, sehingga pada kode diambil dataset berasal dari drive. Dataset dimulai dari tanggal 2 Maret 2020 hingga ketika projek ini dibuat hingga tanggal 7 Desember 2020 sebanyak 280 data.

### Step by step
Will be updated soon

### How it works
Will be updated soon

### References
Big shout out to [stackabuse](https://stackabuse.com/time-series-prediction-using-lstm-with-pytorch-in-python/) by Usman Malik yang telah menginspirasi saya untuk membuat projek ini dan dan menjadi referensi utama saya dalam membuat projek ini.
