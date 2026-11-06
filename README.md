# Project B09: Deteksi Anomali Kondisi dan Kinerja Server

Ujian Tengah Semester Pembelajaran Mesin, Universitas Mikroskil (Kelompok 1).

Kami mencari server yang berperilaku menyimpang dari data metrik server
(CPU, suhu, daya, dan lain-lain) tanpa label anomali, memakai metode
unsupervised: Isolation Forest, LOF, One-Class SVM, dan K-Means.
Kolom `failure_risk_level = High` hanya dipakai sebagai label pembanding
saat evaluasi, bukan sebagai fitur.

## Isi repo

- `UTS_Project_B09_Milestone1.ipynb` : notebook utama
- `hasil_milestone1/` : tabel hasil dan catatan eksperimen
- `Laporan_UTS_ML_Kel1_B09.pdf` : laporan uts

## Dataset

Hyperscale Data Center Dataset (file `green_ai_datacenter.csv`), tidak
disertakan karena ukurannya besar. Unduh di
https://www.kaggle.com/datasets/deeplumiere/hyperscale-data-center-dataset?select=green_ai_datacenter.csv

## Cara menjalankan

1. Unduh CSV dari link di atas.
2. Buka notebook di Google Colab.
3. Jalankan semua sel dari atas dan unggah CSV saat diminta.

Seed yang dipakai 42. Sekitar 10 sampai 20 menit untuk seluruh notebook.

## Anggota

- Nailah Assyifa (231112334)
- Miranda Nadilla Putri (231112195)
- Silvani Chayadi (231112945)
