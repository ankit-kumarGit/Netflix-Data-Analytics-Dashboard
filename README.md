# 🎬 Netflix Data Analytics Project

This project is a comprehensive **data analysis of the Netflix content dataset** using Python, Pandas, and visualization libraries. The goal is to uncover patterns, trends, and insights about the type of content available on Netflix, helping understand its global distribution, popular genres, top countries, and more.

---

## 📁 Dataset Used

- **Source:** [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Format:** CSV
- **Attributes:** `title`, `type`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## 📊 Objectives

- Clean and preprocess the raw Netflix dataset
- Perform **exploratory data analysis (EDA)** on key attributes
- Visualize content distribution over time and geography
- Identify top genres, countries, and trends for content creators and viewers

---

## 🔧 Tech Stack

| Tool/Library     | Purpose                                      |
|------------------|----------------------------------------------|
| Python           | Core programming language                    |
| Pandas           | Data cleaning and manipulation               |
| Matplotlib       | Basic visualizations                         |
| Seaborn          | Advanced visual plots                        |
| Jupyter Notebook | Interactive development & documentation      |

---

## 📈 Key Insights

- 📅 Netflix added the **most content in 2019**, followed by 2020 and 2021.
- 🌍 **United States** leads in content production, followed by **India**, **United Kingdom**, and **Canada**.
- 🎬 Movies dominate the platform (~70%) compared to TV Shows.
- 🎭 Most common genres include **Dramas**, **Comedies**, and **Documentaries**.
- 👥 Cast frequency and director appearances were analyzed using string-based parsing.

---

## 📌 Project Highlights

- ✅ Cleaned missing values and removed duplicates
- ✅ Converted date columns into `datetime` format
- ✅ Extracted year-wise data trends using grouping and aggregation
- ✅ Built **bar plots**, **pie charts**, and **heatmaps** to interpret data
- ✅ Used **string operations** to analyze genre and cast data fields

---

## 🖼️ Sample Visualizations

- 📊 Movies vs TV Shows Pie Chart  
- 📍 Top 10 Countries with Most Netflix Titles (Bar Plot)  
- 📆 Year-wise Netflix Content Trend (Line Plot)  
- 🎭 Most Frequent Genres (Bar Chart)


---

## 🧠 Conclusion

The project offers actionable insights about Netflix’s content expansion over the years. It highlights regional preferences, type-based trends, and popular categories — making it valuable for researchers, content strategists, or data science beginners.

---

## 📎 How to Run

1. Clone the repo or download the `.ipynb` file
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
