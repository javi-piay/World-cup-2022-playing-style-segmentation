⚽ World Cup 2022 – Playing Style Segmentation

Unsupervised machine learning project to identify and segment national team playing styles during the FIFA World Cup 2022 using event-based data.

📌 Project Overview

This project applies unsupervised learning techniques to uncover distinct tactical identities among national teams competing in the 2022 World Cup.

Rather than simply applying a clustering algorithm, the objective was to:

Engineer meaningful performance indicators from raw event data

Reduce dimensionality while preserving interpretability

Identify natural groupings of teams

Translate statistical outputs into tactical insights

🎯 Objective

To build a data-driven framework capable of profiling team playing styles based on aggregated event metrics and identifying structural similarities between teams.

📊 Dataset

StatsBomb Open Data

Match-level aggregated event features

Offensive, defensive, possession and progression metrics

⚙️ Methodology

Feature engineering from event data

Standardization of variables

Dimensionality reduction using PCA

Clustering using K-Means

Internal validation metrics:

Silhouette Score

Davies-Bouldin Index

Calinski-Harabasz Score

📈 Results

Optimal number of clusters: k = X

Clear differentiation between playing identities such as:

High-possession structured teams

Direct transition-oriented teams

Compact defensive teams

High-pressing aggressive teams

(Insert visualizations here)

🧠 Tactical Interpretation

One of the key added values of this project lies in bridging quantitative clustering results with qualitative football interpretation.

Clusters were analyzed not only statistically but also through a tactical lens, identifying structural patterns in build-up, pressing intensity, and progression behavior.

🚀 Future Improvements

Incorporating player-level metrics

Testing hierarchical clustering approaches

Applying the framework to club competitions

Integrating tracking data
