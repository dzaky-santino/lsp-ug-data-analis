# LSP-UG-DATA-ANALIS

Repositori ini berisi kode Jupyter Notebook (`.ipynb`) yang menjelaskan teknik **web scraping** dan **data cleaning**. Ini adalah tugas LSP data analis di Universitas Gunadarma.

## Konten

1. **Web Scraping**
   - Menunjukkan cara mengambil data dari situs web menggunakan pustaka seperti `BeautifulSoup`, `requests`, dan `Selenium`.
   - Membahas topik seperti menangani konten dinamis, pagination, dan memastikan kepatuhan dengan ketentuan layanan situs web.

2. **Data Cleaning**
   - Panduan untuk menangani data yang hilang, data duplikat, dan outliers.
   - Teknik untuk transformasi dan normalisasi data menggunakan `pandas` dan `numpy`.
   - Contoh bagaimana cara merapikan dataset untuk keperluan machine learning atau analisis statistik.

## Ringkasan Notebook

### 1. `scraping_data.ipynb`
   - **Tujuan:** Mengambil data dari situs web publik.
   - **Teknik yang Digunakan:**
     - Requests untuk mengakses halaman web.
     - BeautifulSoup untuk parsing konten HTML.
     - Menangani pagination dan mengambil data dari beberapa halaman.

### 2. `cleaning_data.ipynb`
   - **Tujuan:** Membersihkan data mentah agar siap untuk dianalisis.
   - **Teknik yang Digunakan:**
     - Menghapus data yang hilang.
     - Menangani duplikasi dan data yang tidak relevan.
     - Normalisasi dan standarisasi data.

## Cara Menggunakan di Google Colab

Jika kamu ingin menjalankan notebook ini di Google Colab, ikuti langkah-langkah berikut:

1. **Buka Google Colab:**
   - Kunjungi [Google Colab](https://colab.research.google.com/).
   
2. **Muat Notebook dari GitHub:**
   - Klik `File` > `Open Notebook`.
   - Pilih tab `GitHub`.
   - Masukkan URL repositori GitHub ini: 
     ``` 
     https://github.com/dzaky-santino/lsp-ug-data-analis 
     ```
   - Pilih notebook yang ingin dijalankan (`scraping_data.ipynb` atau `cleaning_data.ipynb`).

3. **Instalasi Pustaka yang Dibutuhkan:**
   Di dalam notebook, kamu dapat menambahkan sel berikut untuk menginstal pustaka yang diperlukan:
   ```python
   !pip install beautifulsoup4 requests pandas numpy selenium
