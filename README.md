# Tyre Analysis Ytd 2023

## Informasi Umum

**Nama Toko**: Ringga Setiadi
**Dept**: Operational Control

## Deskripsi Proyek
Project ini berfokus pada analisis data tyre Hino FM260JD & FM280JD untuk mendapatkan pola trend scrap normal maupun abnormal, serta pengaruh lifetime scrap abnormal **Impact** terhadap 3 faktor penyebab utama yaitu jalan rusak, tekanan ban, dan prilaku driver. namun secara data yang disajikan akan melihat korelasi antara lifetime dengan kecenderungan ban mengisi angin tiap kali pengecekan. dua dataset utama yang digunakan adalah 'pressure_temperature_daily_ytd_2023.csv' dan 'tyre_hystorical_ytddes23'.

## Pertanyaan Projek
1. Adakah korelasi antara suhu luar, suhu tyre dengan pengaruh penambahan pressure dan kerusakan tyre secara normal dan abnormal? serta apakah penambahan pressure dapat mempengaruhi kerusakan tyre?
2. Apabila berkorelasi suhu terbaik untuk penambahan tyre di suhu berapa? dan ideal penambahan pressure di kondisi apa untuk menanggulangi kerusakan tyre abnormal?

## Dashboard
Dashboard interaktif dibuat dengan menggunakan streamlit untuk memvisualisasikan hasil analisis data secara interaktif. Dashboard dapat di akses .....

## Setup Environment
Anda perlu membuat environment khusus menggunakan Conda dan menginstall dependensi yang diperlukan. Ikuti langkah-langkah berikut:
```sh
conda create --name main-ds python=3.11
conda activate main-ds
pip install streamlit pandas numpy matplotlib seaborn
```
## Run steamlit app
```
streamlit run dashboard_tyre_ytd2023.py
```
