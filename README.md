# Project B09: Deteksi Anomali Kondisi dan Kinerja Server

Ujian Tengah Semester Pembelajaran Mesin, Program Studi Teknik Informatika,
Universitas Mikroskil.

## Identitas

- Project ID: B09
- Nama kelompok: Kelompok 1
- Anggota:
  - Nailah Assyifa (231112334)
  - Miranda Nadilla Putri (231112195)
  - Silvani Chayadi (231112945)

## Deskripsi masalah

Server data center menghasilkan metrik penggunaan resource, jaringan, suhu,
dan daya secara terus-menerus. Server yang menyimpang dari pola normal bisa
mengalami gangguan layanan atau memboroskan energi, dan memeriksanya satu per
satu memakan waktu. Proyek ini mencari server yang berperilaku menyimpang
tanpa label anomali, memakai metode unsupervised: Isolation Forest, Local
Outlier Factor, One-Class SVM, dan K-Means. Kolom `failure_risk_level = High`
hanya dipakai sebagai label pembanding saat evaluasi, bukan sebagai fitur.

## Isi repository

- `UTS_Project_B09_Milestone1.ipynb` : notebook utama (EDA, preprocessing,
  baseline, model kandidat, validasi, ensemble, PCA dan clustering)
- `hasil_milestone1/` : tabel hasil dan catatan eksperimen
- `Laporan_UTS_ML_Kel1_B09_Final.pdf` : laporan UTS

## Dataset

Hyperscale Data Center Dataset (`green_ai_datacenter.csv`), data sintetis
dengan 100.000 baris dan 35 kolom. Berkas tidak disertakan karena ukurannya
besar. Unduh di:
https://www.kaggle.com/datasets/deeplumiere/hyperscale-data-center-dataset?select=green_ai_datacenter.csv

## Petunjuk penggunaan

1. Unduh `green_ai_datacenter.csv` dari tautan di atas.
2. Buka notebook di Google Colab (Python 3, CPU cukup).
3. Jalankan semua sel dari atas secara berurutan dan unggah CSV saat sel B
   memintanya. Jangan menjalankan sel secara lepas karena sel-sel bergantung
   pada variabel sebelumnya.
4. Sel W dan AI menyimpan tabel hasil ke folder `hasil_milestone1/`.

Seed yang dipakai 42. Waktu untuk seluruh notebook sekitar 10 sampai 20 menit.
