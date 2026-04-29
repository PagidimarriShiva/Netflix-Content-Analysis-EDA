# 📊 Netflix Data Analysis (EDA)

## 🧩 Problem Statement
Analyze Netflix’s content dataset to understand distribution, trends, and patterns in movies and TV shows, and derive actionable insights.

---

## 📁 Dataset Description
- **Source:** Kaggle (Netflix Movies and TV Shows)
- **Size:** ~8,800 records, 12 columns  
- **Features:**
  - type (Movie / TV Show)
  - title, director, cast
  - country
  - date_added, release_year
  - rating, duration
  - listed_in (genre), description

---

## 🎯 Objective of Analysis
- Understand content distribution on Netflix  
- Identify trends over time  
- Analyze country-wise production  
- Explore ratings and duration patterns  

---

## ❓ Key Questions Explored
- What is the proportion of Movies vs TV Shows?  
- How has content addition changed over time?  
- Which countries produce the most content?  
- What are the most common genres?  
- What is the typical duration of movies?  
- What type of content dominates different ratings?  

---

## 🧹 Data Cleaning
- Handled missing values in:
  - director, cast, country → filled with "Unknown"  
- Converted `date_added` to datetime format  
- Extracted:
  - `year_added`, `month_added`  
- Removed duplicates  
- Cleaned duration column for numeric analysis  

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis
- Distribution of Movies vs TV Shows  
- Content release year distribution  
- Ratings distribution  

### 🔹 Bivariate / Multivariate Analysis
- Content growth over years  
- Country vs content type analysis  
- Correlation between features  

---

## 📈 Visualizations
- Bar charts (content distribution, countries, genres)  
- Line plot (content growth over time)  
- Pie chart (Movies vs TV Shows)  
- Histogram (movie duration distribution)  
- Heatmap (feature correlation)  

---

## 💡 Key Insights
- Movies dominate Netflix content (~70%)  
- Peak content addition occurred around 2018–2019  
- United States and India are top content producers  
- Drama and Comedy are the most common genres  
- Most movies are between 90–120 minutes  

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📌 Conclusion
The analysis highlights Netflix’s strong focus on movies, increasing content growth in recent years, and dominance of specific countries and genres.

---

## 🚀 Future Improvements / Suggestions
- Perform genre-based recommendation analysis  
- Build a dashboard using Power BI or Tableau  
- Apply machine learning for content prediction  
