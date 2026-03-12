# E-Commerce Public Data Analysis Dashboard

## Deskripsi Proyek
Proyek ini merupakan submission untuk kelas **Belajar Analisis Data dengan Python** di Dicoding. Dashboard ini dibuat menggunakan **Streamlit** untuk memvisualisasikan hasil eksplorasi dan analisis data dari *E-Commerce Public Dataset*.

Dashboard ini terdiri dari 5 bagian utama yang menjawab berbagai pertanyaan bisnis:
1. **Daily Orders:** Menampilkan tren metrik jumlah pesanan harian dan total pendapatan (*revenue*).
2. **Customer Demographics:** Menampilkan persebaran pelanggan berdasarkan Negara Bagian (*State*) dan Kota (*City*) khusus untuk pesanan yang berhasil terkirim.
3. **Delivery Time Analysis:** Menganalisis rata-rata waktu pengiriman pesanan dan distribusi keterlambatan pengiriman.
4. **Best Performing Product Categories:** Mengidentifikasi kategori produk paling laris berdasarkan volume penjualan (jumlah item) dan total pendapatan.
5. **RFM Analysis:** Menyajikan segmentasi pelanggan terbaik berdasarkan parameter *Recency* (Keterbaruan), *Frequency* (Frekuensi), dan *Monetary* (Nilai Uang).

## Struktur Direktori
- `/data`: Berisi dataset mentah berformat `.csv` yang digunakan dalam proyek ini.
- `/dashboard`: Berisi file utama `dashboard.py` dan dataset bersih `all_data.csv` yang digunakan untuk aplikasi Streamlit.
- `Proyek_Analisis_Data.ipynb`: File Jupyter Notebook yang berisi alur analisis data lengkap dari tahap *Data Wrangling* hingga *Explanatory Analysis*.
- `README.md`: Dokumentasi petunjuk informasi dan penggunaan proyek.
- `requirements.txt`: Daftar *library* Python yang dibutuhkan untuk menjalankan proyek ini.
- `url.txt`: Berisi tautan (URL) untuk mengakses dashboard interaktif yang sudah di-deploy ke Streamlit Cloud.

## Setup Environment
**Menggunakan Anaconda:**
```bash
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
D:
cd "D:\DOKUMEN & TUGAS KULIAH\DICODING\latihanDicoding\fundamental analisis data\submission_riadin\dashboard-project"
streamlit run dashboard.py
