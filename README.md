# 🍽️ Restaurant Ratings Data Visualization Project

This project is part of **Level 3 - Task 3** of the **Cognifyz Data Science Internship**, focusing on **Data Visualization** to explore restaurant ratings, cuisines, cities, and related features using Python.

---

## 📌 Task Objective

- **Visualize** the distribution of restaurant ratings.
- **Compare** average ratings across different **cuisines** and **cities**.
- **Analyze relationships** between features and the target variable (`Aggregate rating`) to draw insights.

---

## 🧰 Tools & Libraries Used

- Python 🐍
- Pandas
- Matplotlib
- Seaborn

---

## 📊 Visualizations Created

1. **Distribution of Ratings**  
   - Histogram with KDE  
   - Bar chart of rating frequency  

2. **Comparative Analysis**
   - Average ratings by **Top 10 Cities**
   - Average ratings by **Top 10 Cuisines**

3. **Feature Relationships**
   - 📦 Price Range vs Rating (Box Plot)
   - 🪑 Table Booking vs Rating (Bar Chart)
   - 📈 Votes vs Rating (Scatter Plot)

---

## 📁 Files

- `Dataset.csv` – Raw dataset used for analysis.
- `notebook.ipynb` – Jupyter/Colab notebook with all code and visualizations.
- `README.md` – This file.
- `visuals/` – (Optional) Folder with saved plots (if exporting).

---

## 🧠 Insights Discovered

- Many restaurants had a **rating of 0.0**, likely indicating no customer reviews.
- Most rated restaurants fell between **3.0 and 4.5**, reflecting generally good service.
- Some cuisines (like Japanese and Italian) received consistently high ratings.
- Cities with more restaurants didn’t always mean better ratings.

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/restaurant-rating-visualization.git
   cd restaurant-rating-visualization
