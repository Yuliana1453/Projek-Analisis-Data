# Bike Sharing Dashboard 🚲

Dashboard ini dibuat untuk menganalisis data peminjaman sepeda berdasarkan waktu, cuaca, suhu, dan tipe hari.

## 📦 Berkas yang Disertakan

- `dashboard.py` – Script untuk dashboard Streamlit
- `day.csv` – Dataset harian peminjaman sepeda
- `hour.csv` – Dataset per jam (untuk visualisasi jam)
- `requirements.txt` – Daftar library Python yang digunakan
- `README.md` – Petunjuk penggunaan dashboard ini

## ▶️ Cara Menjalankan

### Setup Environment - Anaconda
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

### Setup Environment - Shell/Terminal
```
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```

### Run steamlit app
```
streamlit run dashboard.py
```
