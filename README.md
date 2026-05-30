# Bike Sales Dashboard

![Dashboard Overview](images/Preview 1.png)

## Deskripsi Projek
Projek ini merupakan eksplorasi analitika data menggunakan Microsoft Excel untuk mentransformasi data mentah transaksi penjualan sepeda (*Bike Sales Dataset*) menjadi sebuah dashboard interaktif yang siap pakai untuk level manajemen (*Executive Dashboard*). Projek ini berfokus pada pemahaman fundamen analisis data, manajemen *spreadsheet*, manipulasi formula, dan prinsip visualisasi data yang *user-friendly*.

---

## Data Cleaning & Quality Log
* **Volume Data:** Terdapat total **112.036 data** transaksi di dalam dataset awal.
* **Data Duplikat:** Ditemukan sebanyak **1.000 data duplikat** (sekitar 8% dari keseluruhan data). Proses *delete duplicate* telah dilakukan dan karena jumlahnya yang sedikit, penghapusan ini **tidak berpengaruh secara signifikan** terhadap hasil analisis data akhir.
* **Validitas & Konsistensi Data:** Setelah diaudit, **tidak ditemukan *missing data*** (data kosong), tidak ada *value* data yang tidak konsisten, serta tidak ditemukan *value* yang tidak masuk akal (semua data berada dalam rentang batas logis).

---

## Pertanyaan Bisnis yang Ingin Dijawab
Projek ini dirancang untuk menjawab dua kebutuhan analisis utama:
1. **Analisis Performa & Produk:** Bagaimana tren performa penjualan produk antar tahun berdasarkan *revenue* dan *profit*? Serta kategori produk apa yang paling mendominasi *profit* di tiap-tiap negara?
2. **Analisis Demografi Pelanggan:** Bagaimana profil demografi pelanggan (*Gender* & Usia) berkontribusi terhadap *profit* di negara (*country*) tertentu?

---

##  Dashboard Preview
![Dashboard Overview](images/Preview_2.png)

---

## Business Insights
* **Tren Performa Tahunan:** 
* **Profil Pelanggan Berdasarkan Negara:**

---

## 📂 Struktur Repositori
* `data/` : Berisi file data mentah (*raw data*).
* `dashboard/` : File utama Microsoft Excel (`.xlsx`) yang memuat tabel data, pivot, data log, dan dashboard interaktif.
* `images/` : Dokumentasi visual atau gambar dashboard untuk keperluan operasional.
