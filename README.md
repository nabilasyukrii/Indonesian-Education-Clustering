# 🎓 Clustering School Quality Across Indonesian Provinces

<div align="center">
  <p>
    <b>Uncovering patterns in educational quality using K-Means and K-Medoids algorithms.</b>
  </p>
  
  <p>
    <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R Language">
    <img src="https://img.shields.io/badge/Algorithm-K--Medoids_%26_K--Means-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Algorithms">
    <img src="https://img.shields.io/badge/Domain-Education_Analytics-4CAF50?style=for-the-badge" alt="Domain">
  </p>
</div>

---

## 📌 Project Overview
Inequality in educational quality is a critical issue in Indonesia. This research project explores patterns of educational quality across various provinces using **Unsupervised Learning** techniques. 

By applying clustering algorithms, we aim to uncover meaningful groupings of provinces with similar educational characteristics. This analysis serves as a valuable step in data-driven educational policy-making, helping to identify regions that require specific interventions.

---

## ⚙️ Methodology
We compared two distinct partitioning methods to ensure the robustness of our clusters:

### 1. K-Means Clustering
* **Approach:** Partitions data into $k$ clusters where each observation belongs to the cluster with the nearest mean. Used as a baseline model for initial exploration.

### 2. K-Medoids (PAM - Partitioning Around Medoids)
* **Approach:** Similar to K-Means but uses actual data points (medoids) as centers instead of means.
* **Status:** **Selected as the final model** due to its superior robustness against outliers often present in provincial data.

---

## 📊 Key Findings & Insights

The K-Medoids analysis successfully identified 4 distinct clusters, revealing a clear spatial pattern in educational quality across Indonesia.

### **Visualisasi Hasil Klasterisasi:**

<div align="center">
  <img src="https://github.com/nabilasyukrii/Indonesian-Education-Clustering/blob/main/Cuplikan%20layar%202025-12-29%20154259.png" alt="Peta Klasterisasi Provinsi di Indonesia" width="85%">
  <p><i>Figure 1: Map of Indonesian Provinces Clustered by Educational Quality (K-Medoid Results)</i></p>
</div>

### **Interpretasi Cluster (Berdasarkan Peta & Legenda):**

The map above visually represents the clustering results, categorized into four rankings:

* 🔵 **Cluster 2 (Sangat Tinggi - Very High):** Provinces with the highest educational quality metrics, depicted in **dark blue** (e.g., DKI Jakarta, DI Yogyakarta).
* 🔵 **Cluster 3 (Tinggi - High):** Provinces with good educational quality, depicted in **light blue** (e.g., Jawa Barat, Jawa Tengah, Bali).
* 🟢 **Cluster 1 (Sedang - Medium):** Provinces with moderate educational quality, depicted in **green** (e.g., Sumatera Utara, sebagian Kalimantan).
* 🟡 **Cluster 4 (Rendah - Low):** Provinces requiring significant improvement, depicted in **yellow** (e.g., Nusa Tenggara Timur, Maluku, Papua, Papua Barat).

> **Strategic Insight:** The analysis highlights a significant **spatial disparity**, with provinces in Java and Bali generally performing better than those in Eastern Indonesia. **Policy interventions should be prioritized for regions in Cluster 4 (Yellow)** to bridge this educational gap.

---

## 🛠️ Tech Stack
* **Language:** R (RStudio)
* **Libraries:**
    * `factoextra`: For elegant visualization of clustering results.
    * `cluster`: For computing clustering algorithms (PAM).
    * `tidyverse` (`dplyr`, `ggplot2`): For data manipulation and base plotting.
    * `fpc`: For cluster validation statistics.
* **Data Source:** *(Kemendikbud & Badan Pusat Statistik (BPS), Tahun 202X)*

---

## 🤝 Contributors
This project was a collaborative research effort involving:

* **Nabila Syukri** (Me)
* **Yani Prihantini Hiola**
* **Mega Ramatika**

*Special thanks to our supervising lecturer for the invaluable guidance and support throughout this research journey.*

---

## 📞 Connect
I am highly interested in educational data analytics and policy research. If you're working on similar topics, I’d love to connect!
* [LinkedIn](https://www.linkedin.com/in/nabilasyukrii)
