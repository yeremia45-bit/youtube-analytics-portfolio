# 🎬 YouTube Trending Video Analysis  
**By Yeremia**

## 📌 Overview  
This project explores the YouTube Trending Videos dataset to uncover what factors contribute to a video’s popularity. Using real data, I identify trends across categories, engagement metrics, and upload timing to answer the question:  
> “What makes a YouTube video go viral?”

---

## 🎯 Business Objective  
The goal of this project is to help content creators and marketers understand which elements — such as category, title style, and posting time — influence a video’s likelihood to trend.

---

## 📦 Dataset  
Dataset used: [YouTube Trending Videos Dataset on Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)

Files:
- `USvideos.csv` — Main dataset  
- `US_category_id.json` — Contains category names mapped to category IDs

---

## ⚙️ Tools Used  
- **RStudio / R** — Data cleaning, transformation, visualization  
- **ggplot2 / dplyr** — Data wrangling and visualization  
- **Tableau** — Interactive dashboard  
- **GitHub** — Project documentation  
- **Kaggle** — Notebook development and dataset exploration  

---

## 🧮 Process  
1. **Data Cleaning**  
   - Removed duplicates and missing values  
   - Parsed publish dates and times  
   - Joined category names using JSON file  

2. **Exploratory Data Analysis (EDA)**  
   - Most popular categories by average views  
   - Upload day vs. performance heatmaps  
   - Engagement ratios (likes/views, comments/views)  

3. **Feature Engineering**  
   - `like_ratio = likes / views`  
   - `comment_ratio = comments / views`  
   - `title_length = nchar(title)`  

4. **Visualization**  
   - Charts created with ggplot2  
   - Tableau dashboard summarizing findings  

---

## 📊 Key Insights  
- Music and Entertainment categories dominate trending videos  
- Shorter titles (under 50 chars) perform slightly better  
- Thursdays and Fridays see the highest average engagement  
- Videos with emojis in titles have higher like-to-view ratios  

---

## 🖥️ Dashboard Preview  
![Dashboard Screenshot](tableau_dashboard.png)

View the interactive dashboard on Tableau Public: *[Add your link here]*

---

## 🧠 Learnings  
This project taught me how to clean and merge multi-format data (CSV + JSON), perform exploratory analysis, and communicate insights visually for stakeholders.

---

## 📚 References  
- [YouTube Trending Dataset on Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)  
- Google Data Analytics Professional Certificate — Case Study Framework  
