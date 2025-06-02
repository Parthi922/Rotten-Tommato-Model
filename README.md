**Zoho Assignment_
 rotten_tomatoes_movies3.ipynb_**

 

# 🎬 Rotten Tomatoes Movie Ratings Analysis

This project explores and visualizes a dataset of movies from **Rotten Tomatoes** to identify patterns and insights related to:
- 🎯 Audience and critic ratings
- 🎭 Genres
- 📅 Release trends
- 🧮 Review counts

Built using **Python, pandas, seaborn, and matplotlib**.

---

## 📦 Dataset

- **Source**: `rotten_tomatoes_movies.csv`
- **Encoding**: `latin-1`
- **Rows**: 17,712
- **Columns**: 22

### 📊 Key Features
- `tomatometer_rating`: Critic score (0–100)
- `audience_rating`: Audience score (0–100)
- `runtime`: Movie duration in minutes
- `genres`: Comma-separated genre labels
- `original_release_date`: Official release date
- `tomatometer_count` / `audience_count`: Number of reviews

---

## 🚀 Features & Analysis

### 1. **Data Exploration**
- Shape, types, missing values
- Descriptive stats for numeric columns
- Frequency counts for categorical columns

### 2. **Visualizations**
- Histograms for:
  - `tomatometer_rating`
  - `audience_rating`
  - `runtime`
- Scatter plots:
  - Rating correlations
  - Review count vs. rating
- Bar plot of genre frequency
- Line plot of ratings over release years

### 3. **Correlation Insights**
- ✅ Positive correlation between critic and audience ratings (~0.65)
- ⚠️ Weak correlation between number of reviews and rating
- 🎬 Genre-wise movie distribution analysis
- 📈 Year-wise average rating trends

---

## 📈 Sample Visuals

<img src="screenshots/rating_distribution.png" width="400"/>  
<img src="screenshots/ratings_over_time.png" width="400"/>

## 📦 Dataset

- **Source**: [Rotten Tomatoes Movies & Reviews (Kaggle)](https://www.rottentomatoes.com/m/0814255)
- **Encoding**: `latin-1`
- **File Name**: `rotten_tomatoes_movies.csv`
- **Rows**: 17,712
- **Columns**: 22


