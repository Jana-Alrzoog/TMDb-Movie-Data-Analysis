# 🎬 TMDb Movie Data Analysis

<p align="center">
  <img src="https://github.com/user-attachments/assets/e80fc584-8894-451e-989d-30f7a31ef42d" alt="banner" width="30%">
  

</p>
--
This project explores and analyzes a dataset of over 10,000 movies from The Movie Database (TMDb). It was completed as part of Udacity's Data Analyst Nanodegree program. The goal is to answer key questions related to movie trends, genres, and revenue using Python, pandas, and data visualization tools.
---

## 📌 Project Objectives

- Investigate trends in movie production by genre over time.
- Identify the factors most associated with high movie revenue.
- Practice data wrangling, feature engineering, and EDA techniques.
- Present findings using clear visualizations and summary statistics.

---
## 🧪 Technologies Used

- Python 3
- pandas
- NumPy
- matplotlib
- seaborn
- Jupyter Notebook

---

## 🔍 Key Findings

1. **Popular Genres Over Time**  
   - *Drama*, *Comedy*, and *Action* were the most frequently produced genres.
   - Drama consistently led from the 1990s to 2010s.
  
2. **Revenue-Related Factors**  
   - Strong correlation between **Budget** and **Revenue** (r = 0.71).
   - **Popularity** also positively linked to revenue (r = 0.60).
   - Other factors like *vote average*, *runtime*, and *number of genres* showed weak or no correlation.

---

## 📊 Visuals

The project includes:
- Line plots of genre trends over time
- Scatter plots between revenue and key variables
- Correlation heatmaps

---

## ⚠️ Limitations

- Missing and zero values in key columns (e.g., `budget`, `revenue`) may reduce accuracy.
- The analysis is based on correlation and does **not imply causation**.
- Genre data required special handling due to nested JSON-like format.

---

