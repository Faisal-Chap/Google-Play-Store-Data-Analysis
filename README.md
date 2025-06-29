# 📱 Google Play Store Data Analysis & Visualization with Plotly

Welcome to an end-to-end exploratory data analysis (EDA) project on Android app data from the Google Play Store. This project dives deep into **app performance**, **user behavior**, **pricing strategies**, and **market competition** using the power of **Pandas** and **interactive Plotly charts**.

---

## 📊 Project Overview

**Dataset Source:**  
[Google Play Store Apps Dataset on Kaggle](https://www.kaggle.com/lava18/google-play-store-apps)  
Scraped and compiled by Lavanya Gupta (2018)

**Project Goals:**
- Clean and preprocess real-world app data
- Explore app popularity, ratings, installs, and pricing
- Visualize trends and insights using **Plotly Express**

---

## 🚀 What I Did

### 🧹 Data Cleaning
- Removed unnecessary columns
- Dropped rows with missing `Rating`
- Removed duplicate app entries (e.g., multiple "Instagram")
- Converted size, price, and install data into numeric format

### 📈 Exploratory Data Analysis
- Most downloaded apps
- Highest rated apps (with caution)
- Most expensive apps
- Apps with most reviews
- Revenue estimates for paid apps

### 📊 Data Visualization with Plotly
- **Pie/Donut Charts** for Content Ratings
- **Bar Charts** for:
  - Most competitive categories (by number of apps)
  - Most popular categories (by installs)
- **Scatter Plots** showing:
  - Downloads vs. competition in each category
- **Box Plots** for:
  - Free vs. Paid app installs
  - Revenue by category
  - Paid app pricing strategies
- **Grouped Bar Charts** comparing Free vs. Paid app counts

---

## 💡 Key Insights

- Free apps dominate in downloads, especially in gaming and communication.
- A few paid apps (mostly games/tools) generate significant revenue.
- Tools, Productivity, and Medical apps tend to have higher paid price points.
- Most app categories are saturated — pricing smartly is critical.

---

## 🛠️ Tools Used

- Python 🐍
- Pandas for data cleaning
- Plotly Express for visualization
- Jupyter Notebook for analysis

---

## 📁 Folder Structure

project/
│
├── apps.csv # Raw dataset
├── playstore-analysis.ipynb # Jupyter Notebook (Main Analysis)
├── README.md # This file
└── figures/ # (Optional) Saved visualizations

yaml
Copy
Edit

---

## ✍️ Author

**Faisal Zia**  
Data Science Learner | Pythonista | AI Explorer  
Connect on [LinkedIn](https://www.linkedin.com/in/faisal-zia-dev/) | Follow on [X/Twitter](https://x.com/faisalziachap)

---

## 📌 Future Work

- Incorporate user reviews sentiment analysis
- Predict app success based on category, size, and type
- Build a dashboard using Dash or Streamlit

---

## 📜 License

This project is licensed under the MIT License.
