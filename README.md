# 🌏 Geospatial Distribution of Seismic Activity in Indonesia (2008-2023)
Visualizing Indonesia Earthquake Frequency Based on Magnitude Categories 2008-2023

📌 **Project Overview**
This analysis aims to map earthquake patterns in Indonesia over the past 15 years (2008-2023) using Python for data processing and clustering, and Tableau for storytelling.

### 📊 Interactive Dashboard
[![Tableau Dashboard](DAFTAR_GAMBAR_KAMU.png)](https://public.tableau.com/app/profile/johannes.wuisan/viz/UnveilingIndonesiasSeismicRisksGeospatialClusteringInsights/SeismicInsightAGeospatialandMachineLearningStudyofIndonesiasEarthquakeRisks?publish=yes)
*Click the image above to view the interactive dashboard.

---

### 🚀 Key Features
* **Machine Learning:** K-Means Clustering to identify risk zones based on location, magnitude, and depth.
* **Interactive Map:** Spatial visualisation using Folium.
* **Data Storytelling:** Comprehensive insights via Tableau.

### 🛠️ Resources & Tech Stack
* [![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-blue?style=flat-square&logo=kaggle)](https://www.kaggle.com/datasets/kekavigi/earthquakes-in-indonesia)
* **Python** (Pandas, Folium, Scikit-Learn)
* **Tableau** (Data Storytelling)
* **Jupyter Notebook**

---

### 💡 Initial Hypothesis & Result
> "Despite low linear correlation, geographic location has a stronger categorical influence on magnitude than depth."

**Result: [ACCEPTED]**
* **Statistical Gap:** The linear correlation between coordinates and magnitude is low ($R^2 \approx 0$), meaning raw numbers can't predict strength.
* **Spatial Influence:** However, visual clusters show that $M > 6.0$ events are "locked" at specific tectonic boundaries (Sunda Arc & Molucca Sea). This proves geography is a stronger **categorical** predictor than depth alone.

### 📍 Clustering Visualization (Python Folium)
![Clustering Result](FOLDER_KAMU/NAMA_GAMBAR_MAP.png)
*Visualisasi hasil K-Means Clustering menggunakan Folium.*
