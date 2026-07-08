<h1 align="center">ZARA Sales Data Analysis Dashboard</h1>

<p align="center">
![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-yellow)
![Looker Studio](https://img.shields.io/badge/Google-Data%20Studio-orange)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00)
</p>
---

# Dashboard Preview

<p align="center">
    <img src="images/dashboard zara.jpg" width="1000">
</p>

## Live Dashboard

🔗 **View Interactive Dashboard:**  
[https://lookerstudio.google.com/...](https://datastudio.google.com/reporting/e77ffbee-3848-4ce1-9573-7fe47da3f07b)

---

# Project Overview

Industri fashion sangat bergantung pada analisis data untuk memahami perilaku penjualan, mengevaluasi efektivitas strategi pemasaran, dan mengoptimalkan penempatan produk di toko. Proyek ini dilakukan analisis terhadap dataset penjualan ZARA guna memperoleh insight mengenai performa produk berdasarkan berbagai aspek, seperti kategori produk, promosi, posisi produk, harga, koleksi musiman serta kontribusi pendapatan (Revenue).

Selain melakukan Exploratory Data Analysis (EDA), hasil analisis divisualisasikan dalam bentuk dashboard interaktif menggunakan **Google Data Studio**, sehingga informasi bisnis dapat dipahami dengan lebih mudah dan mendukung proses pengambilan keputusan.

---

# Objectives

Proyek ini bertujuan untuk:

- Memahami karakteristik dataset penjualan Zara.
- Menganalisis performa penjualan berdasarkan kategori produk.
- Mengevaluasi pengaruh promosi terhadap penjualan.
- Menganalisis kontribusi posisi produk terhadap penjualan.
- Mengidentifikasi produk dengan volume penjualan tertinggi.
- Mengidentifikasi produk dengan revenue tertinggi.
- Menyediakan dashboard interaktif untuk visualisasi data.

---

# Dataset Source

Dataset diperoleh dari Kaggle.

**Dataset**
> Zara Sales Dataset

**Source**
https://www.kaggle.com/datasets/xontoloyo/data-penjualan-zara

**Author**
> xontoloyo

Dataset berisi informasi mengenai:

- Product ID: Unique identifier for each product.
- Product Position: The position of the product in the catalog or store layout.
- Promotion: Indicator of whether the product is currently on promotion or not.
- Product Category: The category of the product, such as clothing, accessories, shoes, etc.
- Seasonal: Indicator of whether the product is part of a specific seasonal collection.
- Sales Volume: The quantity of products sold.
- Brand: Brand of the product.
- URL: Product URL (e.g., if the product is sold online).
- SKU: Stock Keeping Unit, a unique code used to identify items available for sale.
- Name: Name of the product.
- Description: Description of the product.
- Price: Price of the product.
- Currency: Currency of the product price.
- Scraped_at: The time when the data was scraped (e.g., in web scraping process).
- Terms: Terms or conditions of the product.
- Section: Section or category where the product is sold in the store (e.g., women's clothing, men's clothing, children's clothing, etc.).

---

# 🛠️ Tech Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

### Tools

- Google Colab
- Google Data Studio
- Git
- GitHub

---

# Project Structure

```
Zara-Sales-Analysis
│
├── dataset
│   └── zara.csv
│
├── notebook
│   └── Data_penjualan_ZARA.ipynb
│
├── dashboard
│   └── Zara_Sales_Dashboard.pdf
│
├── images
│   └── dashboard.png
│
├── Data_penjualan_ZARA.ipynb
├── README.md
├── requirements.txt
```
---

# Exploratory Data Analysis

Tahapan analisis yang dilakukan meliputi:

### Data Understanding

- Melihat struktur dataset
- Mengecek tipe data
- Missing values
- Duplicate values

### Data Preparation

- Membersihkan nama kolom
- Mengubah format tanggal
- Membuat fitur Revenue
- Membuat kategori harga

### Exploratory Data Analysis

Analisis dilakukan berdasarkan:

- Revenue by Section
- Revenue by Product Type
- Sales by Promotion
- Revenue by Seasonal Product
- Sales by Product Position
- Revenue by Price Category
- Top Product by Sales Volume
- Top Product by Revenue
- Correlation Analysis

---

# Dashboard

Dashboard dibuat menggunakan **Google Data Studio** untuk memvisualisasikan hasil analisis secara interaktif.

Dashboard menyediakan beberapa filter sehingga pengguna dapat mengeksplorasi data berdasarkan kebutuhan.

## Dashboard Features

### KPI

- Total Product
- Total Sales Volume
- Total Revenue
- Average Product Price
- Average Sales Volume

### Charts

- Revenue by Section
- Revenue by Product Type
- Sales by Promotion
- Revenue by Seasonal Product
- Sales by Product Position
- Top Products by Revenue

### Interactive Filters

- Section
- Product Type
- Promotion
- Seasonal
- Product Position

---

# Key Insights

Beberapa insight yang diperoleh dari analisis data:

- Produk pada posisi **Aisle** menghasilkan total volume penjualan dan revenue tertinggi dibandingkan posisi lainnya.
- Produk pada posisi **Front of Store** memiliki rata-rata volume penjualan per produk tertinggi.
- Kategori **Jackets** mendominasi produk dengan revenue tertinggi.
- Revenue dipengaruhi oleh kombinasi antara harga produk dan volume penjualan.
- Produk dengan promosi memiliki performa penjualan yang kompetitif dibandingkan produk tanpa promosi.
- Section **MAN** memberikan kontribusi revenue terbesar pada dataset.

---

# Output

Project menghasilkan beberapa output:

- Exploratory Data Analysis Notebook
- Dataset yang telah dibersihkan
- Dashboard Google Data Studio
- Insight bisnis berdasarkan hasil analisis

---

# Visualizations

Visualisasi yang dibuat pada notebook antara lain:

- Revenue by Section
- Revenue by Product Type
- Sales by Promotion
- Revenue by Seasonal Product
- Sales by Product Position
- Revenue by Price Category
- Top 10 Products by Sales Volume
- Top 10 Products by Revenue
- Scatter Plot
- Correlation Heatmap

---

# Future Improvements

Pengembangan yang dapat dilakukan pada proyek ini:

- Menambahkan analisis tren penjualan berdasarkan waktu.
- Membangun dashboard menggunakan Power BI atau Tableau.
- Melakukan prediksi penjualan menggunakan Machine Learning.
- Menambahkan analisis customer segmentation apabila tersedia data pelanggan.

---
