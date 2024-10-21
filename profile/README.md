# Atur RupiahKu

**Atur RupiahKu** adalah aplikasi manajemen keuangan yang dirancang untuk membantu masyarakat Indonesia dalam mengelola keuangan pribadi dengan lebih efektif dan efisien.Dibangun dengan pendekatan statistika dan data sains, aplikasi ini menawarkan tiga fitur utama yang dirancang untuk memandu pengguna menuju kesejahteraan finansial. Kami percaya bahwa dengan pengelolaan keuangan yang baik adalah salah satu kunci untuk mendukung **visi Indonesia Emas 2045**- menjadi negara maju dengan ekonomi yang berkelanjutan, tangguh, dan inklusif. 

## Fitur Aplikasi

### 1. Financial Forecast
Fitur ini membantu pengguna memprediksi kondisi keuangan mereka untuk beberapa hari ke depan berdasarkan data historis pendapatan dan pengeluaran. Kami menggunakan model **XGBoost** untuk melakukan forecasting keuangan pada dua kasus utama:
- **Kasus Ojek Online (Penghasilan Tidak Tetap):** Dengan memanfaatkan data bangkitan, model **XGBoost** menghasilkan error sebesar **1,7k**.
- **Kasus Mahasiswa (Penghasilan Bulanan):** Dengan model yang sama, error prediksi untuk mahasiswa yang mendapatkan penghasilan bulanan dari orang tua mencapai **69k**.

Fitur ini bertujuan untuk membantu pengguna dalam merencanakan keuangan dengan lebih baik, menghindari defisit, dan mengoptimalkan penggunaan pendapatan mereka.

Repo: [Explore repo untuk fitur ini](https://github.com/AturRupiahKu/forecasting-keuangan)

### 2. Loan Risk
Fitur ini menghitung risiko gagal bayar pinjaman berdasarkan beberapa variabel seperti gaji, jumlah pinjaman, dan tingkat bunga. Kami menggunakan model **Light Gradient Boosting Machine (LGBM)** yang terbukti memberikan akurasi terbaik dengan **F1 Test Score sebesar 92%**. Data yang digunakan telah di-scale dan disesuaikan dengan kondisi keuangan di Indonesia.

Fitur ini bertujuan membantu pengguna dalam memahami kemampuan mereka membayar pinjaman, sehingga dapat mengurangi risiko gagal bayar yang dapat berdampak negatif pada stabilitas keuangan pribadi dan nasional.

Dataset: [Link Kaggle Dataset](https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval?select=Loan.csv) 
Repo: [Explore repo untuk fitur ini](https://github.com/AturRupiahKu/rekomendasi-resiko-pinjaman)

### 3. Video Edukasi dan Platform Konsultasi
Fitur ini menyediakan berbagai video edukasi keuangan yang interaktif dan mudah dipahami, serta platform marketplace untuk menyewa konsultan keuangan. Dengan adanya fitur ini, pengguna bisa belajar tentang pengelolaan keuangan secara mandiri, sekaligus mendapatkan bantuan profesional jika diperlukan.

Fitur ini bertujuan untuk meningkatkan literasi keuangan masyarakat Indonesia, sekaligus membuka lapangan pekerjaan baru bagi konsultan keuangan yang ingin bergabung dalam platform kami.


## Dampak dan Kontribusi
Aplikasi **Atur RupiahKu** tidak hanya membantu masyarakat Indonesia dalam mengelola keuangan, tetapi juga mendukung tercapainya target ekonomi **Indonesia Emas 2045** dengan:
- Meningkatkan literasi keuangan masyarakat untuk mengelola pendapatan dan pengeluaran secara lebih bijaksana.
- Membantu memprediksi kemampuan pembayaran pinjaman, sehingga mengurangi risiko gagal bayar.
- Menciptakan lapangan kerja baru melalui fitur marketplace konsultan keuangan.

Kami berkomitmen untuk terus mengembangkan aplikasi ini demi meningkatkan kesejahteraan masyarakat dan mendukung pertumbuhan ekonomi yang inklusif, berkelanjutan, dan tangguh.

## UI Tampilan Atur RupiahKu

Berikut adalah tampilan UI dari aplikasi Atur RupiahKu. Anda dapat melihatnya secara lengkap di PDF berikut:

[Tampilan UI](https://github.com/Atur-RupiahKu/Atur-RupiahKu/blob/main/Atur%20RupiahKu%20Mockup.pdf)
<embed src="https://github.com/Atur-RupiahKu/Atur-RupiahKu/blob/main/Atur%20RupiahKu%20Mockup.pdf" width="800px" height="600px" />

## Tentang Kami
Tim **Atur RupiahKu** terdiri dari tiga mahasiswa Institut Teknologi Sepuluh Nopember (ITS) Surabaya sebagai berikut.
1. Fadhel - Mahasiswa S1 Sains Data
2. Saeful Fikri - Mahasiswa S1 Statistika 
3. Abdillah Ilham - Mahasiswa S1 Statistika
Kami berkomitmen untuk menciptakan solusi berbasis teknologi yang membantu pengguna dalam mencapai kesejahteraan finansial.

Jelajahi repositori kami untuk informasi lebih lanjut:
- [Forecasting Kondisi Keuangan](https://github.com/AturRupiahKu/forecasting-keuangan)
- [Rekomendasi Risiko Pinjaman](https://github.com/AturRupiahKu/rekomendasi-resiko-pinjaman)

## Kontak
Email: fiqbalh12@gmail.com

