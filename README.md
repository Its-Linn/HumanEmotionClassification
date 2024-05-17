# HumanEmotionClassification
Klasifikasi Gambar Emosi Manusia Dengan Convolutional Neural Network (Model VGG 19)

## Link Dataset
https://drive.google.com/drive/folders/1SVMmxeSJP6G3l6BA8RRa4lYzr484vkhq?usp=sharing

## Pre-processing
1. Menggunakan Preprocessor dari Model VGG 19
2. membagi dataset menjadi Validasi, Test dan Train dengan ImageDataGenerator

## Modeling
1. Membuat Baseline Model VGG19
2. Menambahkan Extra Layer di atas Model VGG19
3. Plotting, dadn menambahkan Callback seperti Early Stopping dan Reduce Learning Rate untuk Mencegah Underfitting
4. Fitting Model Dengan Dataset
