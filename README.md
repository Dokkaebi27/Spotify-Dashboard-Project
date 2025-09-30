# 🎧Spotify-Dashboard-Project

🌐 Languages: [English](#english-version) | [Bahasa Indonesia](#versi-bahasa-indonesia)

---

## English Version

Welcome to the **Spotify Analysis Project** repository 🚀 

This project presents an in-depth analysis of music popularity trends, artist performance, and song characteristics using Spotify data, visualized through an interactive dashboard. This dashboard serves as a case study in Data Analysis and Business Intelligence (BI).

**Project Type**: End-to-End Data Analytics & Business Intelligence.

**Tools Used**: Microsoft Excel (for Data Source & Cleaning), and Data Visualization Tool Power BI for reporting.

---
## 🔍 Project Overview

This project demonstrates a streamlined Business Intelligence (BI) workflow, transforming raw music data into actionable market insights:
1. **Data Source (Excel)** → Spotify Top Hits dataset containing track, artist, and popularity metrics, initially processed and cleaned in Excel.
2. **Data Transformation** → Data imported directly from the Excel file into the visualization tool.
3. **KPI Calculation (DAX/Calculated Fields)** → Aggregation and Key Performance Indicator (KPI) calculations, such as Total Popularity and Average Position, are performed within the visualization tool's modeling layer.
4. **Dashboard (Visualization Tool)** → Interactive reports and visual insights into music trends.

---
## 📌 Problem Statement
Currently, Spotify’s raw “Top 50” dataset is limited to lists and rankings, making it difficult for stakeholders to see patterns and take insights quickly.

From the screens, the key problems solved are:

- **No clear KPI monitoring** → Dashboard provides quick summary of total songs, artists, popularity, duration, etc.
- **Lack of explicit vs non-explicit analysis** → Users can compare how explicit songs perform vs non-explicit.
- **Difficulty in tracking song/album distribution** → Visuals show breakdown by album type and release year.
- **Trend visibility missing** → Popularity and distinct songs trends are shown over time (monthly & yearly).
- **Artist vs Song level insights not connected** → Drill-down pages for Artists and Songs connect overview insights to detailed records.
- **Decision-making gaps** → Marketing and curation teams can now identify which artists/songs to promote, trends to follow, and which content resonates with audiences.

---
## 🎯  Business Requirement
Spotify stakeholders (music analysts, playlist managers, and marketing teams) need a **consolidated dashboard** to monitor song and artist performance across different dimensions.

Based on the screens provided, the business requires:

🏠 Overview Page
- Track KPIs like **Total Songs, Distinct Artists, Average Popularity, Avg Duration.**
- Compare **Explicit vs Non-Explicit Songs** and see their share.
- Analyze **Songs by Album Type** (single, album, compilation).
- View **Distinct Songs and Avg Popularity by Year.**
- Trend analysis of **Avg Popularity & Distinct Songs by Month.**
- Highlight **Top Songs & Top Artists by Popularity.**

👤  Artist Page
- Show **Top Artists by Popularity.**
- Compare **Tracks per Album and Songs by Artist.**
- Provide drill-down to artist-level data **artist name, distinct song, position 1 hits per artist ,avg popularity per artist, avg position, avg duration per year.**
- Support identifying artists with consistent hits and #1 positions.

🎶 Songs Page
- Rank **Top Songs by Popularity.**
- Show Tracks per Song (Album/Single distribution).
- Compare **Songs by Song Count.**
- Provide detailed table with **song name, release date, avg popularity, position, avg duration per minutes.**

---
## 📂 Repository Structure
```
spotify-dashboard-project/ 
│ 
├── datasets/                             # Raw music data and cleaned tables
│   └── spotify-top-50-world.csv          # The primary data source (csv)
│ 
├── powerbi/                              # Dashboard file
│   └── Spotify_Dashboard.pbix            # Interactive dashboard
│ 
├── docs/                                 # Documentation & reports 
│   └── Spotify_Dashboard.pdf             # Visual export of the dashboard 
│ 
└── README.md                             # Project description and portfolio details
```

---
## 🛠️ Tools & Skills Demonstrated

**Excel**:
- Data entry, cleaning, and preprocessing.
- Ensuring data quality and consistency before visualization.

**Data Visualization Tool (Power BI)**:
- Dashboard design, DAX (or equivalent) for KPI calculation.
- Visual storytelling through bar charts, tables, and time series.

**Data Analytics & BI**:
- Trend Analysis: Interpreting monthly and yearly release patterns.
- Ranking & Segmentation: Identifying top performers and segmenting songs by album type.
- Turning raw popularity scores into meaningful industry insights.
  
---
## 🙍 About Me  

Hi, I'm **Ahmad Zaki Amani** 👋  

✨ I'm passionate about **Data Analytics** and **Business Intelligence**, focusing on building dashboards, creating data visualizations, and turning raw data into actionable insights.  

💡 This project is part of my portfolio, where I showcase skills in:  
- Data visualization & storytelling  
- Dashboard design (Power BI, Tableau)  
- Data transformation & analysis  
- Business Intelligence solutions  

📫 Let’s connect and collaborate!  

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmadzaki27.az@gmail.com) 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-zaki-amani-ab091635b/) 

---

## Versi Bahasa Indonesia

Selamat datang di repositori **Spotify Analysis Project** 🚀

Proyek ini menyajikan analisis mendalam mengenai tren popularitas musik, performa artis, serta karakteristik lagu menggunakan data Spotify, yang divisualisasikan melalui dashboard interaktif. Dashboard ini menjadi studi kasus dalam **Data Analytics** dan **Business Intelligence (BI)**.

**Jenis Proyek**: End-to-End Data Analytics & Business Intelligence

**Alat yang Digunakan**: Microsoft Excel (untuk sumber & pembersihan data) dan Power BI sebagai alat visualisasi.

---

## 🔍 Gambaran Umum Proyek

Proyek ini menunjukkan alur kerja Business Intelligence (BI) yang terintegrasi, mengubah data mentah Spotify menjadi wawasan bisnis yang dapat ditindaklanjuti:

1. **Sumber Data (Excel)** → Dataset *Spotify Top Hits* yang berisi lagu, artis, dan metrik popularitas, diproses dan dibersihkan terlebih dahulu di Excel.
2. **Transformasi Data** → Data diimpor langsung dari file Excel ke dalam alat visualisasi.
3. **Perhitungan KPI (DAX/Calculated Fields)** → Perhitungan indikator kinerja utama seperti Total Popularitas dan Rata-rata Posisi dilakukan dalam layer pemodelan di Power BI.
4. **Dashboard (Visualisasi)** → Laporan interaktif dan wawasan visual mengenai tren musik.

---

## 📌 Permasalahan
Dataset Spotify “Top 50” masih terbatas berupa daftar dan ranking, sehingga sulit bagi stakeholder untuk langsung melihat pola dan mengambil insight.

Dashboard ini menyelesaikan permasalahan berikut:

* **Tidak ada monitoring KPI yang jelas** → Dashboard menyediakan ringkasan cepat: total lagu, artis, popularitas, durasi, dsb.
* **Analisis eksplisit vs non-eksplisit tidak tersedia** → Pengguna dapat membandingkan performa lagu eksplisit vs non-eksplisit.
* **Sulit melacak distribusi lagu/album** → Visualisasi menunjukkan pembagian berdasarkan tipe album dan tahun rilis.
* **Minim visibilitas tren** → Tren popularitas dan jumlah lagu ditampilkan per bulan & tahun.
* **Insight artis vs lagu tidak terhubung** → Halaman detail artis dan lagu menghubungkan overview dengan data detail.
* **Kesenjangan pengambilan keputusan** → Tim marketing & kurasi dapat mengidentifikasi artis/lagu yang harus dipromosikan, tren musik, serta konten yang sesuai dengan audiens.

---

## 🎯 Kebutuhan Bisnis
Stakeholder Spotify (analis musik, manajer playlist, dan tim marketing) memerlukan **dashboard terpusat** untuk memantau performa artis & lagu dari berbagai dimensi.

Dari dashboard, kebutuhan bisnis mencakup:

🏠 Halaman Overview
* Monitor KPI seperti **Total Lagu, Total Artis, Rata-rata Popularitas, Rata-rata Durasi**.
* Perbandingan **Lagu Eksplisit vs Non-Eksplisit**.
* Analisis **Lagu berdasarkan Tipe Album** (single, album, kompilasi).
* Tren **Jumlah Lagu Unik & Popularitas Rata-rata per Tahun**.
* Tren bulanan untuk **Popularitas & Jumlah Lagu Unik**.
* Highlight **Top Lagu & Top Artis berdasarkan Popularitas**.

👤 Halaman Artis
* Menampilkan **Top Artis berdasarkan Popularitas**.
* Membandingkan **Jumlah Lagu per Album & Lagu per Artis**.
* Drill-down hingga ke level artis: **nama artis, jumlah lagu unik, jumlah #1 hits, rata-rata popularitas, rata-rata posisi, rata-rata durasi per tahun**.
* Identifikasi artis yang konsisten dengan hits dan posisi #1.

🎶 Halaman Lagu
* Ranking **Top Lagu berdasarkan Popularitas**.
* Distribusi lagu per tipe album.
* Analisis **Jumlah Lagu per Song**.
* Detail tabel: **nama lagu, tanggal rilis, rata-rata popularitas, posisi, rata-rata durasi (menit)**.

---
## 📂 Struktur Repositori
```
spotify-dashboard-project/
│
├── datasets/                             # Data mentah & tabel hasil pembersihan
│   └── spotify-top-50-world.csv          # Sumber data utama (csv)
│
├── powerbi/                              # File dashboard
│   └── Spotify\_Dashboard.pbix           # Dashboard interaktif
│
├── docs/                                 # Dokumentasi & laporan
│   └── Spotify\_Dashboard.pdf            # Ekspor visualisasi dashboard
│
└── README.md                             # Deskripsi proyek & portfolio
```

---
## 🛠️ **Alat & Skill yang Digunakan**

**Excel**:

* Input, pembersihan, dan preprocessing data.
* Menjamin kualitas & konsistensi data sebelum visualisasi.

**Power BI**:

* Desain dashboard, pembuatan KPI dengan DAX.
* Visual storytelling menggunakan grafik batang, tabel, dan time series.

**Data Analytics & BI**:

* Analisis Tren: pola rilis bulanan & tahunan.
* Ranking & Segmentasi: identifikasi artis teratas & segmentasi lagu per tipe album.
* Mengubah skor popularitas mentah menjadi insight industri yang berarti.

---
## 🙍 Tentang Saya

Halo, saya **Ahmad Zaki Amani** 👋

✨ Saya memiliki passion di bidang **Data Analytics** dan **Business Intelligence**, khususnya dalam membangun dashboard, membuat visualisasi data, serta mengubah data mentah menjadi insight yang berguna.

💡 Proyek ini adalah bagian dari portfolio saya, yang menampilkan keahlian dalam:

* Visualisasi data & storytelling
* Desain dashboard (Power BI, Tableau)
* Transformasi & analisis data
* Solusi Business Intelligence

📫 Yuk, terhubung & kolaborasi!

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:ahmadzaki27.az@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/ahmad-zaki-amani-ab091635b/)

---

