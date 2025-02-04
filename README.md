# Prediksi Harga Saham INDOFOOD Menggunakan Model ARCH
## Deskripsi Penelitian
Penelitian ini bertujuan untuk memprediksi harga saham PT. Indofood Sukses Makmur Tbk (INDF) menggunakan Model Autoregressive Conditional Heteroskedasticity (ARCH). Data yang digunakan mencakup periode dari Januari 2020 hingga Oktober 2024, yang diambil dari sumber keuangan terpercaya seperti Yahoo Finance atau Bloomberg. Analisis ini bertujuan untuk memahami pola dan tren harga saham serta memprediksi volatilitas harga saham INDF.

## Struktur Dataset
Dataset terdiri dari atribut-atribut berikut:
* Tanggal perdagangan
* Harga pembukaan
* Harga penutupan
* Harga tertinggi
* Harga terendah
* Volume perdagangan
* Return harian

## Langkah-langkah Penelitian
1. Import Library: Mengimpor pustaka yang diperlukan seperti forecast, ``tseries``, ``TSA``, dll.
2. Import Dataset: Memuat data historis harga saham INDF.
3. Pemrosesan Data: Mengubah data menjadi time series dan memastikan konsistensi tanggal.
4. Plot Data: Visualisasi data untuk melihat tren dan pola.
5. Uji Kestasioneran Data: Menggunakan ACF, PACF, dan ADF test.
6. Differencing: Mengubah data menjadi stasioner jika diperlukan.
7. Model ARIMA: Mengidentifikasi dan memilih model ARIMA terbaik.
8. Uji Diagnostik Model: Menguji residu model ARIMA.
9. Model ARCH: Membangun model ARCH berdasarkan residu ARIMA.
10. Prediksi: Melakukan prediksi harga saham INDF menggunakan model ARCH.

## Hasil
Model terbaik yang dipilih adalah ARIMA(0,1,3) dengan ARCH(8). Prediksi menunjukkan bahwa harga saham INDF diperkirakan akan mengalami kenaikan yang konstan dalam periode 1 November hingga 30 November 2024.

## Persyaratan
* R
* RStudio(opsional)

## Cara Menjalankan
1. Clone repository ini.
2. Instal pustaka yang diperlukan dengan menggunakan ``install.packages()``.
3. Jalankan skrip R atau notebook R Markdown yang disediakan untuk melakukan analisis dan prediksi.



