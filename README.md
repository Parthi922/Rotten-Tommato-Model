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

---

## 🧪 Tech Stack

| Tool          | Use                        |
|---------------|-----------------------------|
| `pandas`      | Data handling & exploration |
| `matplotlib`  | Base plotting               |
| `seaborn`     | Statistical visualizations  |
| `Jupyter` / `Colab` | Notebook environment  |

---

## 📝 Changelog

### 🔧 [v1.0.1] – Column Reference Fix
- **Issue**: Incorrect column `audience_score` used.
- **Fix**: Replaced with correct column `audience_rating`.
- ✅ All analysis and visualizations now run without errors.

---

## 📁 File Structure

```bash
.
├── Rotten-Tommato-Model.ipynb     # Main Colab notebook
├── rotten_tommato_model.py        # Converted Python script
├── rotten_tomatoes_movies.csv     # Input dataset (not included)
├── README.md                      # Project overview
└── screenshots/                   # Optional image outputs


