# Proyek Klasifikasi Gambar : Rice Image Dataset

## Deskripsi Proyek
Proyek ini bertujuan untuk mengklasifikasi gambar dari 5 bentuk beras menggunakan model CNN

## 📂 Struktur Direktori
```
submission/
├───tfjs_model
| ├───group1-shard1of4.bin
| ├───group1-shard2of4.bin
| ├───group1-shard3of4.bin
| ├───group1-shard4of4.bin
| └───model.json
├───tflite
| ├───model.tflite
| └───labels.txt
├───saved_model
| ├───saved_model.pb
| └───variables
├───notebook.ipynb
├───README.md
└───requirements.txt
```

## Setup Environment
### Membuat dan mengaktivasikan virtual environment:
```bash
python -m venv venv
venv\Scripts\activate
```

### Install library
```bash
pip install -r requirements.txt
```
