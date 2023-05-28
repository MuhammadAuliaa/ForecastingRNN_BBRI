# ForecastingRNN_BBRI

ForecastingRNN_BBRI adalah proyek sederhana untuk melakukan prediksi harga saham menggunakan Recurrent Neural Networks (RNN) untuk saham BBRI (Bank Rakyat Indonesia). Proyek ini menggunakan data historis harga saham untuk melatih model RNN dan menghasilkan prediksi harga saham di masa depan.

## Fitur
- Mengunduh data historis harga saham BBRI menggunakan library yfinance.
- Melakukan pra-pemrosesan data dengan normalisasi dan membaginya menjadi dataset pelatihan dan pengujian.
- Membangun dan melatih model RNN menggunakan TensorFlow dan Keras.
- Mengevaluasi performa model menggunakan Mean Squared Error (MSE).
- Menghasilkan prediksi harga saham untuk dataset pengujian.
- Menampilkan visualisasi harga saham aktual dan prediksi menggunakan matplotlib dan mplfinance.

## Persyaratan 
- Python 3.7 atau versi lebih baru
- Library yfinance
- Library pandas
- Library numpy
- Library tensorflow
- Library scikit-learn
- Library matplotlib
- Library mplfinance
