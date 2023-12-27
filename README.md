
# Klasifikasi Batu-Gunting-Kertas dengan MobileNet dan Flask

## Gambaran Umum

Proyek ini bertujuan untuk membuat model machine learning yang handal untuk mengklasifikasikan gambar batu, gunting, dan kertas menggunakan arsitektur MobileNet. Model yang telah dilatih akan dideploy menggunakan Flask, memberikan antarmuka web yang ramah pengguna untuk membuat prediksi secara real-time.

## Persyaratan

Pastikan Anda telah menginstal dependensi berikut di sistem Anda:

- Python 3.x
- Flask
- TensorFlow
- OpenCV
- NumPy

Anda dapat menginstalnya menggunakan perintah berikut:

```bash
pip install -r requirements.txt
```

## Instalasi

1. Klona repositori:

```bash
git clone https://github.com/yourusername/rock-paper-scissors-classifier.git
cd rock-paper-scissors-classifier
```

2. Instal dependensi:

```bash
pip install -r requirements.txt
```

## Dataset

Dataset pelatihan terdiri dari gambar batu, gunting, dan kertas yang telah dipilih dengan cermat. Anda dapat menemukan dataset [di sini](https://www.kaggle.com/competitions/rock-paper-scissors/code). Susun dataset seperti berikut:

```plaintext
dataset/
|-- rock/
|   |-- rock1.jpg
|   |-- rock2.jpg
|   |-- ...
|-- paper/
|   |-- paper1.jpg
|   |-- paper2.jpg
|   |-- ...
|-- scissors/
|   |-- scissors1.jpg
|   |-- scissors2.jpg
|   |-- ...
```

## Pelatihan

Arsitektur MobileNet :
![mobtiny_fig](https://github.com/agusfahmi/Image-Classification-Deploy/assets/85145157/7b4841d6-6f6d-445f-8c40-0911f7aaccf0)

Evaluasi Model :

![ac](https://github.com/agusfahmi/Image-Classification-Deploy/assets/85145157/af491738-9b2f-4285-9e3d-944e73ba7f6f)

Hasil prediksi sampel 10 citra :
![pr](https://github.com/agusfahmi/Image-Classification-Deploy/assets/85145157/ee1eff36-906b-47f1-b056-6ff95d6ce8a2)


## Aplikasi Flask

Jalankan aplikasi Flask untuk mendeploy model:

```bash
flask run
```

Akses antarmuka web di [http://127.0.0.1:5000/](http://127.0.0.1:5000/) untuk berinteraksi dengan klasifikasi Batu-Gunting-Kertas.

## Penggunaan

1. Unggah gambar batu, gunting, atau kertas pada antarmuka web.
2. Klik tombol "Prediksi" untuk mendapatkan hasil prediksi dari model.

## Demo

<img width="694" alt="Cuplikan layar 2023-12-14 140105" src="https://github.com/agusfahmi/Image-Classification-Deploy/assets/85145157/021ae004-9209-4b80-b602-e9b1f1112dfc">






