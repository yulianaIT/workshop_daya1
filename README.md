# Nama Proyek Data

Deskripsi singkat proyek (1–2 kalimat).

## Tujuan
- Menjelaskan tujuan analisis
- Menyebutkan pertanyaan bisnis/riset

## Dataset
- **Nama**: Iris Species  
- **Sumber**: [UCI ML Repository via Kaggle](https://www.kaggle.com/datasets/uciml/iris)  
- **Lisensi**: Public Domain  
- **Deskripsi**: Dataset klasifikasi 3 spesies bunga Iris berdasarkan 4 fitur morfologis.

## Struktur Proyek
- `data/raw/`         : data mentah dari sumber eksternal (mis. iris.csv)
- `data/interim/`     : data hasil langkah persiapan awal
- `data/processed/`   : data siap pakai untuk training / evaluasi
- `notebooks/`        : eksplorasi data & eksperimen awal
- `src/config/`       : konfigurasi proyek (config, logging)
- `src/data/`         : script loading, split, dan persiapan dataset
- `src/models/`       : script training, evaluasi, dan prediksi model
- `src/pipelines/`    : pipeline end-to-end untuk training
- `src/utils/`        : fungsi pendukung (seed, metrics, dll.)
- `experiments/`      : konfigurasi & catatan tiap eksperimen
- `models_artifacts/` : checkpoint dan model final
- `reports/`          : hasil analisis, gambar, dan ringkasan
- `scripts/`          : script command-line (train, evaluate, dll.)

## Analisis
- [Notebook EDA di Kaggle](https://www.kaggle.com/username/notebook-name)
