# 🎵 Spotify Power BI Dashboard

### 🎧 Music Analytics • Artist Insights • Audio Features • Popularity Trends

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&weight=600&size=24&duration=3500&pause=1000&color=1DB954&center=true&vCenter=true&width=850&lines=Spotify+Music+Analytics+Dashboard;Interactive+Power+BI+Dashboard;Data+Visualization+%7C+DAX+%7C+Power+Query;Explore+Songs+Artists+Albums+%26+Genres"/>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Spotify-Music%20Analytics-1DB954?style=for-the-badge&logo=spotify&logoColor=white"/>
  <img src="https://img.shields.io/badge/DAX-Measures-0057B8?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Excel-Data%20Preparation-217346?style=for-the-badge&logo=microsoftexcel"/>
</p>

### 🎼 Discover Music Trends with Interactive Power BI Visualizations

</div>

---

# 🌟 Project Overview

The **Spotify Power BI Dashboard** is an interactive Business Intelligence project that analyzes Spotify music data to uncover trends in **songs, artists, albums, genres, popularity, and audio features**.

The dashboard transforms raw Spotify streaming data into meaningful visual insights using **Power BI, Power Query, DAX, and Data Modeling**.

> 🎯 **Goal:** Explore global music trends, identify popular artists, analyze genres, and understand song popularity through interactive dashboards.

---

# 🎯 Objectives

* 🎵 Analyze Spotify song popularity.
* 🎤 Identify top-performing artists.
* 💿 Discover trending albums.
* 🎼 Explore genre distribution.
* 📈 Analyze popularity trends over time.
* 🎛️ Build an interactive dashboard with slicers and filters.

---

# 🛠️ Tech Stack

| Technology         | Purpose                        |
| ------------------ | ------------------------------ |
| 🎵 Power BI        | Interactive Dashboard          |
| ⚡ Power Query      | Data Cleaning & Transformation |
| 🧮 DAX             | KPI Measures & Calculations    |
| 📗 Microsoft Excel | Dataset Preparation            |
| 📊 Data Modeling   | Relationships & Analytics      |

---

# 📂 Dataset Information

<table>
<tr><td><strong>Dataset</strong></td><td>Spotify Top 50 World Songs</td></tr>
<tr><td><strong>Domain</strong></td><td>Music Streaming Analytics</td></tr>
<tr><td><strong>Format</strong></td><td>Excel / CSV</td></tr>
<tr><td><strong>Source</strong></td><td>Spotify Music Dataset</td></tr>
</table>

### 📋 Dataset Contains

* 🎵 Song Name
* 🎤 Artist Name
* 💿 Album
* 🎧 Genre
* ❤️ Popularity Score
* 📅 Release Year
* ⏱️ Duration
* 🔊 Danceability
* ⚡ Energy
* 🎼 Tempo
* 😊 Valence
* 🔈 Loudness

---

# 🎨 Dashboard Highlights

## 📊 Executive Music Dashboard

| KPI                   | Description               |
| --------------------- | ------------------------- |
| 🎵 Total Songs        | Number of songs analyzed  |
| 🎤 Total Artists      | Unique artists in dataset |
| 💿 Total Albums       | Album count               |
| ❤️ Average Popularity | Overall popularity score  |
| 🔥 Top Artist         | Most popular artist       |
| 🎧 Top Genre          | Highest-performing genre  |

---

# 🚀 Interactive Dashboard Features

| Feature                | Description                |
| ---------------------- | -------------------------- |
| 🎤 Top 10 Artists      | Highest popularity artists |
| 💿 Top Albums          | Best-performing albums     |
| 🎵 Song Popularity     | Popular songs ranking      |
| 🎧 Genre Analysis      | Genre-wise comparison      |
| 📈 Popularity Trends   | Trend visualization        |
| 🌍 Interactive Filters | Artist, Genre, Album, Year |
| 🎛️ Dynamic Slicers    | Drill-down exploration     |

---

# 📈 Dashboard Workflow

```text
Spotify Dataset
       │
       ▼
Power Query Cleaning
       │
       ▼
Data Modeling
       │
       ▼
DAX Measures
       │
       ▼
Interactive Power BI Dashboard
       │
       ▼
Music Insights & Trends
```

---

# ⚙️ Data Preparation

The dataset was cleaned and transformed before visualization.

### ✔️ Power Query Steps

* Removed duplicates.
* Fixed missing values.
* Converted numeric columns.
* Cleaned artist & album names.
* Standardized genres.
* Created calculated fields.

---

# 🧮 DAX Measures Used

```DAX
Total Songs =
COUNT(Spotify[Track Name])

Total Artists =
DISTINCTCOUNT(Spotify[Artist])

Average Popularity =
AVERAGE(Spotify[Popularity])

Top Popular Song =
MAX(Spotify[Popularity])
```

Additional measures include:

* Average Danceability
* Average Energy
* Genre Count
* Artist Ranking
* Album Ranking

---

# 📊 Dashboard Visualizations

### 🎵 Visuals Included

* 🎤 KPI Cards
* 📊 Top 10 Artists (Bar Chart)
* 💿 Top Albums (Column Chart)
* 🎧 Genre Distribution (Donut Chart)
* 📈 Popularity Trend (Line Chart)
* ❤️ Popularity by Artist
* 🎼 Audio Feature Analysis
* 🎛️ Interactive Filters & Slicers

---

# 🎯 Key Insights

### 🎤 Artist Insights

* Identify the most streamed artists.
* Compare artist popularity scores.
* Discover emerging artists.

### 💿 Album Performance

* Highest popularity albums.
* Album comparison by popularity.
* Album-wise song distribution.

### 🎧 Genre Analysis

* Most popular music genres.
* Genre contribution to total songs.
* Genre popularity comparison.

### 🎼 Audio Features

* Danceability vs Energy.
* Tempo distribution.
* Loudness comparison.
* Valence analysis.

---

# 📷 Dashboard Preview

## 🎵 Spotify Music Analytics Dashboard

> Replace this placeholder with your dashboard screenshot.

<p align="center">
<img width="950" src="images/spotify-dashboard-preview.png">
</p>

---

# 📁 Repository Structure

```bash
Spotify-PowerBI-Dashboard/
│
├── Spotify Dashboard.pbix
├── spotify-top-50-world.xlsx
├── README.md
├── dashboard-preview.png
└── Assets/
     ├── Icons
     ├── Images
     └── Backgrounds
```

---

# 🚀 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/vinaygunti-41/Spotify-PowerBI-Dashboard.git
```

## 2️⃣ Open Power BI File

```text
Spotify Dashboard.pbix
```

## 3️⃣ Connect Dataset

Load the provided **spotify-top-50-world.xlsx** dataset.

## 4️⃣ Explore Dashboard

Use interactive slicers to filter by:

* Artist
* Genre
* Album
* Popularity
* Year

---

# 💼 Business Impact

This dashboard helps:

* 🎵 Analyze global music trends.
* 🎤 Compare artist performance.
* 💿 Identify top-performing albums.
* 🎧 Understand genre popularity.
* 📊 Build interactive music analytics reports.

---

# 🌟 Future Improvements

* ✅ Spotify Streaming Trend Forecasting.
* ✅ Real-Time Spotify API Integration.
* ✅ Artist Recommendation Dashboard.
* ✅ Song Recommendation System using Python.
* ✅ Power BI + SQL Live Dashboard.

---

# 📚 Skills Demonstrated

* Power BI Dashboard Design
* Power Query Data Transformation
* DAX Measures & KPIs
* Music Analytics
* Interactive Data Visualization
* Data Modeling
* Business Intelligence Reporting

---

# 👨‍💻 Author

<div align="center">

## Gunti Vinay

### 💚 Aspiring Data Analyst | SQL • Python • Power BI • Tableau

<p align="center">
  <a href="https://github.com/vinaygunti-41">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/>
  </a>

  <a href="https://linkedin.com/in/vinaygunti-dataanalyst">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin"/>
  </a>

  <a href="https://devoted-jade-0of9azstaa.edgeone.app/">
    <img src="https://img.shields.io/badge/Portfolio-1DB954?style=for-the-badge&logo=google-chrome&logoColor=white"/>
  </a>
</p>

**🎧 Transforming Music Data into Visual Insights**

</div>

---

<div align="center">

## ⭐ If you like this project, give it a Star ⭐ on GitHub!

### 🎵 Built with Power BI • Spotify Analytics • Data Visualization

**Made with ❤️ by Gunti Vinay**

</div>
