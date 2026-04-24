# Web Scraping & Big Data Analysis

Repositori ini berisi implementasi tugas *web scraping* untuk pengumpulan data dari sumber web tertentu, yang kemudian diproses untuk kebutuhan analisis *Big Data*. Proyek ini mencakup seluruh alur kerja mulai dari pengambilan data mentah hingga penyimpanan dalam format yang terstruktur.

## 📁 Struktur Proyek

- `scraping.py` / `notebook.ipynb`: Skrip utama untuk melakukan scraping.
- `data/`: Direktori yang berisi hasil ekstraksi (misalnya file .csv, .json, atau .xlsx).
- `requirements.txt`: Daftar pustaka (libraries) Python yang diperlukan.

## 🚀 Fitur Utama

- **Automated Data Extraction**: Mengambil data secara otomatis dari target website.
- **Data Cleaning**: Membersihkan data mentah dari duplikasi atau nilai yang hilang (*missing values*).
- **Export Ready**: Menyimpan hasil akhir ke dalam format yang siap dianalisis lebih lanjut (CSV/JSON).

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun menggunakan bahasa pemrograman **Python** dengan pustaka pendukung:
- `BeautifulSoup4` atau `Selenium`: Untuk navigasi dan ekstraksi elemen HTML.
- `Requests`: Untuk menangani HTTP requests.
- `Pandas`: Untuk manipulasi data dan ekspor ke format tabel.
- `Matplotlib` / `Seaborn` (Opsional): Jika terdapat visualisasi data sederhana.

## ⚙️ Cara Instalasi & Penggunaan

1. **Clone Repositori**
   ```bash
   git clone https://github.com/keychainbalee/tugas_scraping_bigdata.git
   cd tugas_scraping_bigdata
Install Dependensi
Pastikan Anda telah menginstal Python, kemudian jalankan:

Bash
pip install -r requirements.txt
Jalankan Skrip

Bash
python scraping.py
📊 Hasil Data
Data yang berhasil dikumpulkan mencakup atribut-atribut seperti:

[Sebutkan kolom 1, misal: Nama Produk]

[Sebutkan kolom 2, misal: Harga]

[Sebutkan kolom 3, misal: Rating/Ulasan]

📝 Catatan Tambahan
Proyek ini dibuat untuk memenuhi tugas mata kuliah Big Data. Pastikan untuk mematuhi kebijakan robots.txt pada situs web target saat melakukan scraping.

Dikembangkan oleh Muhammad Iqbal Saputra.
