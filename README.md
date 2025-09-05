# 🛒 Capstone Project: Supermarket Sales Data Insights

## 📌 Project Overview

Supermarket memiliki ribuan transaksi harian yang kompleks. Dengan menganalisis dataset **Supermarket Sales Sample Data**, kita dapat menemukan tren penjualan, mengidentifikasi faktor utama penyumbang revenue, serta menghasilkan rekomendasi strategi berbasis data.

### 🎯 Objective

1. Menganalisis tren penjualan supermarket berdasarkan data transaksi.
2. Mengklasifikasikan transaksi menjadi kategori *High Value* dan *Low Value*.
3. Menggunakan **AI (IBM Granite Model via Replicate API)** untuk memperkaya insight dengan klasifikasi, ringkasan, dan rekomendasi strategis.
4. Menghasilkan rekomendasi actionable untuk meningkatkan efisiensi dan pendapatan.

---

## 📊 Dataset

Dataset yang digunakan: **Supermarket Sales Sample Data**

| Variable        | Deskripsi                                    |
|-----------------|----------------------------------------------|
| Order No.       | Nomor transaksi                              |
| Order Date      | Tanggal order                                |
| Customer Name   | Nama pelanggan                               |
| Ship Date       | Tanggal pengiriman                           |
| Retail Price    | Harga retail product                         |
| Order Quantity  | Jumlah barang yang diorder                   |
| Tax             | Besaran pajak transaksi                      |
| Total           | Nilai total transaksi                        |

👉 [Download Dataset](./resources/data/supermarket_sales.xlsx)

---

## ⚙️ Analysis Process

1. **Data Preparation**
   - Import dataset Excel.
   - Cek missing values, pastikan dataset siap dipakai.

2. **Exploratory Data Analysis (EDA)**
   - Hitung total transaksi, rata-rata order, dan distribusi order.
   - Buat visualisasi tren penjualan bulanan.

3. **AI Support (IBM Granite Model via Replicate API)**
   - **Classification**: Transaksi *High Value* (>300) atau *Low Value* (≤300).
   - **Summarization**: Merangkum insight dataset.
   - **Recommendation**: Strategi bisnis berbasis data.

---

## 🔍 Insight & Findings

Beberapa temuan dari dataset:

- **80% revenue berasal dari transaksi besar (Pareto Principle).**  
- **Seasonality effect**: terdapat bulan dengan kenaikan signifikan order quantity.  
- Produk dengan **retail price tinggi memberikan margin lebih besar** meskipun volumenya lebih rendah.  

---

## ✅ Conclusion & Recommendations

1. Fokuskan promosi pada produk bernilai tinggi untuk meningkatkan margin.
2. Luncurkan strategi diskon pada periode sepi untuk menjaga stabilitas pendapatan.
3. Optimalkan proses pengiriman karena terdapat gap antara order date dan ship date.

---

## 🤖 AI Support Explanation

- **LLM Granite-3.0-8b-instruct** via **Replicate API** digunakan untuk:
  - Melakukan **klasifikasi transaksi** (High vs Low Value).
  - Merangkum hasil analisis (*summarization*).
  - Memberikan rekomendasi berbasis data (*insight generation*).

Contoh Prompt yang digunakan:

- *"Classify the following transactions as 'High Value' or 'Low Value'"*
- *"Summarize key insights from dataset analysis"*
- *"Recommend 3 actionable strategies to improve revenue and efficiency"*

---
