# 🎓 Clustering School Quality Across Indonesian Provinces

<div align="center">
  <p>
    <b>Uncovering patterns in educational quality using K-Means and K-Medoids algorithms.</b>
  </p>
  
  <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white">
  <img src="https://img.shields.io/badge/Algorithm-K--Means_%26_K--Medoids-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
  <img src="https://img.shields.io/badge/Type-Unsupervised_Learning-4479A1?style=for-the-badge">
</div>

---

## 📌 Project Overview
Inequality in educational quality is a critical issue in Indonesia. This research project explores patterns of educational quality across various provinces using **Unsupervised Learning** techniques. 

By applying clustering algorithms, we aim to uncover meaningful groupings of provinces with similar educational characteristics. This analysis serves as a valuable step in data-driven educational policy-making, helping to identify regions that require specific interventions.

---

## ⚙️ Methodology
We compared two distinct partitioning methods to ensure the robustness of our clusters:

### 1. K-Means Clustering
* **Approach:** Partitions data into $k$ clusters in which each observation belongs to the cluster with the nearest mean.
* **Usage:** Used as the baseline model for identifying general groupings of school quality.

### 2. K-Medoids (PAM)
* **Approach:** Similar to K-Means but uses actual data points (medoids) as centers.
* **Why we used it:** To handle potential outliers in provincial data more robustly than K-Means.

---

## 📊 Key Findings & Insights
*(Di bagian ini, nanti Anda bisa masukkan screenshot plot/grafik hasil cluster, atau deskripsi singkat hasil temuan Anda. Contoh isian sementara:)*

Our analysis resulted in distinct clusters representing different tiers of educational performance:
* **Cluster 1 (High Performance):** Provinces with high accreditation scores and infrastructure availability.
* **Cluster 2 (Developing):** Provinces showing potential but lacking in specific facilities.
* **Cluster 3 (Needs Improvement):** Regions requiring prioritized government intervention.

> **Note:** Detailed visualizations and the list of provinces per cluster can be found in the [Results Folder](./clustering-kmeans) or the presentation deck.

---

## 🛠️ Tech Stack
* **Language:** R
* **Libraries:** `factoextra`, `cluster`, `tidyverse`, `fpc`
* **Data Source:** *Kementerian Pendidikan dan Kebudayaan*

---

## 🤝 Contributors
This project was a collaborative research effort involving:

* **Nabila Syukri** (Me)
* **Yani Prihantini Hiola**
* **Mega Ramatika**

*Special thanks to our supervising lecturer for the guidance and support throughout this journey.*

---

## 📞 Connect
If you're working on similar topics or passionate about educational data analytics, I’d love to connect and exchange ideas!
* [LinkedIn](https://www.linkedin.com/in/nabilasyukrii)
