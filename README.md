# Music Genres Clustering using K-Means

## 📌 Project Overview
This project applies **K-Means Clustering** to group songs into different **music genres** based on their audio features. Using a dataset containing various song characteristics (e.g., tempo, loudness, danceability), the goal is to uncover hidden patterns in musical styles without predefined genre labels.

## 🚀 Technologies Used
- **Python** 🐍
- **Pandas, NumPy** (Data Processing)
- **Scikit-learn** (K-Means Clustering)
- **Matplotlib, Seaborn** (Data Visualization)

## 📂 Dataset
- The dataset contains numerical audio features of songs such as:
  - Liveness
  - Loudness
  - Danceability
  - Energy
  - Acousticness
- Ensure the dataset is in **CSV format**.

## 🔹 Implementation Steps
1. **Load and Preprocess Data**
   - Handle missing values, normalize numerical features.
2. **Feature Selection**
   - Select relevant audio features for clustering.
3. **Apply K-Means Algorithm**
   - Determine the optimal number of clusters using the **Elbow Method**.
   - Train the model on selected features.
4. **Cluster Analysis & Visualization**
   - Visualize the clustered songs using **scatter plots**.

## 🎯 Expected Outcomes
- Group songs with similar audio features into **clusters**.
- Identify distinct patterns between different genres.
- Use cluster insights for **music recommendations** or playlist creation.

## 📊 Visualization Examples
- **Scatter Plots**: Genre clusters using Plotly.

## ▶️ Running the Project
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
2. Run the script:
   ```bash
   python music_clustering.py
   ```
3. View clustering results in **graphs and console outputs**.

---
📌 **Author**: Saloni Trivedi  
📅 **Date**: 13 march 2025

