# 📊 Zara Sales Data Analysis Dashboard

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-yellow)
![Looker Studio](https://img.shields.io/badge/Google-Looker%20Studio-orange)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00)
![License](https://img.shields.io/badge/License-MIT-green)

Analisis data penjualan Zara menggunakan **Python** untuk melakukan **Exploratory Data Analysis (EDA)** dan membangun dashboard interaktif menggunakan **Google Looker Studio**. Proyek ini bertujuan untuk memperoleh insight mengenai performa penjualan produk berdasarkan kategori, promosi, posisi produk, koleksi musiman, serta kontribusi pendapatan (Revenue).

---

# 📌 Project Overview

Industri fashion sangat bergantung pada analisis data untuk memahami perilaku penjualan, mengevaluasi efektivitas strategi pemasaran, dan mengoptimalkan penempatan produk di toko. Melalui proyek ini dilakukan analisis terhadap dataset penjualan Zara guna memperoleh insight mengenai performa produk berdasarkan berbagai aspek, seperti kategori produk, promosi, posisi produk, harga, dan koleksi musiman.

Selain melakukan Exploratory Data Analysis (EDA), hasil analisis divisualisasikan dalam bentuk dashboard interaktif menggunakan **Google Looker Studio**, sehingga informasi bisnis dapat dipahami dengan lebih mudah dan mendukung proses pengambilan keputusan.

---

# 🎯 Objectives

Proyek ini bertujuan untuk:

- Memahami karakteristik dataset penjualan Zara.
- Menganalisis performa penjualan berdasarkan kategori produk.
- Mengevaluasi pengaruh promosi terhadap penjualan.
- Menganalisis kontribusi posisi produk terhadap penjualan.
- Mengidentifikasi produk dengan volume penjualan tertinggi.
- Mengidentifikasi produk dengan revenue tertinggi.
- Menyediakan dashboard interaktif untuk visualisasi data.

---

# 📥 Dataset Source

Dataset diperoleh dari Kaggle.

**Dataset**
> Zara Sales Dataset

**Source**
https://www.kaggle.com/datasets/xontoloyo/data-penjualan-zara

**Author**
> xontoloyo

Dataset berisi informasi mengenai:

- Product ID
- Product Name
- Product Position
- Product Category
- Promotion
- Seasonal Product
- Sales Volume
- Product Price
- Section
- Revenue
- dan atribut lainnya.

---

# 🛠️ Tech Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- OpenPyXL

### Tools

- Google Colab
- Google Looker Studio
- Git
- GitHub

---

# 📂 Project Structure

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
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🔍 Exploratory Data Analysis

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

# 📊 Dashboard

Dashboard dibuat menggunakan **Google Looker Studio** untuk memvisualisasikan hasil analisis secara interaktif.

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

# 🖥️ Dashboard Preview

> Simpan screenshot dashboard berikut pada folder **images** dengan nama **dashboard.png**

<p align="center">
    <img src="images/dashboard.png" width="1000">
</p>

---

# 📈 Key Insights

Beberapa insight yang diperoleh dari analisis data:

- Produk pada posisi **Aisle** menghasilkan total volume penjualan dan revenue tertinggi dibandingkan posisi lainnya.
- Produk pada posisi **Front of Store** memiliki rata-rata volume penjualan per produk tertinggi.
- Kategori **Jackets** mendominasi produk dengan revenue tertinggi.
- Revenue dipengaruhi oleh kombinasi antara harga produk dan volume penjualan.
- Produk dengan promosi memiliki performa penjualan yang kompetitif dibandingkan produk tanpa promosi.
- Section **MAN** memberikan kontribusi revenue terbesar pada dataset.

---

# 📁 Output

Project menghasilkan beberapa output:

- Exploratory Data Analysis Notebook
- Dataset yang telah dibersihkan
- Dashboard Google Looker Studio
- Insight bisnis berdasarkan hasil analisis

---

# 🚀 Installation

Clone repository

```bash
git clone https://github.com/putnab42/Zara-Sales-Analysis.git
```

Masuk ke folder project

```bash
cd Zara-Sales-Analysis
```

Install dependency

```bash
pip install -r requirements.txt
```

Jalankan notebook menggunakan Jupyter Notebook

```bash
jupyter notebook
```

atau buka notebook menggunakan **Google Colab**.

---

# 📷 Visualizations

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

# 📌 Future Improvements

Pengembangan yang dapat dilakukan pada proyek ini:

- Menambahkan analisis tren penjualan berdasarkan waktu.
- Membangun dashboard menggunakan Power BI atau Tableau.
- Melakukan prediksi penjualan menggunakan Machine Learning.
- Menambahkan analisis customer segmentation apabila tersedia data pelanggan.

---

# 🙏 Acknowledgements

Terima kasih kepada **Kaggle** dan pembuat dataset yang telah menyediakan dataset sehingga proyek ini dapat digunakan sebagai media pembelajaran dalam analisis data.

Dataset:
https://www.kaggle.com/datasets/xontoloyo/data-penjualan-zara

---

# 👩‍💻 Author

**Putri Nabila**

Undergraduate Student | Informatics Engineering

📧 Email : putnab42@gmail.com

💼 LinkedIn : *(Tambahkan URL LinkedIn Anda di sini)*

🐙 GitHub : https://github.com/putnab42

---

⭐ Jika repository ini bermanfaat, jangan lupa berikan **Star** pada repository ini.
