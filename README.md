# ⚽ World Cup 2022 – Playing Style Segmentation

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

Unsupervised machine learning project to identify and segment national team playing styles during the FIFA World Cup 2022 using event-based data.

---

## 📌 Project Overview

This project applies **unsupervised learning techniques** to uncover distinct tactical identities among national teams competing in the 2022 World Cup.

Rather than simply applying a clustering algorithm, the objective was to:

- Engineer meaningful performance indicators from raw event data  
- Reduce dimensionality while preserving interpretability  
- Identify natural groupings of teams  
- Translate statistical outputs into tactical insights  

---

## 🎯 Objective

To build a **data-driven framework** capable of profiling team playing styles based on aggregated event metrics and identifying structural similarities between teams.

---

## 📊 Dataset

- **StatsBomb Open Data**
- Match-level aggregated event features  
- Offensive, defensive, possession and progression metrics  

---

## ⚙️ Methodology

1. Feature engineering from event data  
2. Standardization of variables  
3. Dimensionality reduction using **PCA**  
4. Clustering using **K-Means**  
5. Internal validation metrics:
   - Silhouette Score  
   - Davies-Bouldin Index  
   - Calinski-Harabasz Score  

---

## 📈 Results

- **Optimal number of clusters:** k = 4  
- Clear differentiation between playing identities such as:
  - High-possession structured teams  
  - Direct transition-oriented teams  
  - Compact defensive teams  
  - High-pressing aggressive teams  

<img width="989" height="690" alt="image" src="https://github.com/user-attachments/assets/265b11cd-051a-4342-8287-70af162a9868" />


---

## 🧠 Tactical Interpretation

One of the key added values of this project lies in bridging quantitative clustering results with qualitative football interpretation.

Clusters were analyzed not only statistically but also through a tactical lens, identifying structural patterns in:

- Build-up behavior  
- Pressing intensity  
- Progression speed  
- Defensive compactness  

---

## 🚀 Future Improvements

- Incorporating player-level metrics  
- Testing hierarchical clustering approaches  
- Applying the framework to club competitions  
- Integrating tracking data  

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 👤 Author

Javier Piay  
Industrial Engineer | Big Data & AI | UEFA C Coach  
AI applied to Football Performance  

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/javier4piay)
