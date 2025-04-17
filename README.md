# 📱 Google Play Store App Analytics

This project provides a comprehensive analysis of the Android app market using a dataset of Google Play Store apps and user reviews. The goal is to uncover insights about app categories, ratings, pricing strategies, popularity, and more through exploratory data analysis and visualization.

## 📊 Dataset

**Source:**  
The data was scraped from the Google Play Store by Lavanya Gupta (2018) and is available on [Kaggle](https://www.kaggle.com/lava18/google-play-store-apps).

**Files used:**
- `googleplaystore.csv`
- `user_reviews.csv`

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- WordCloud
- Jupyter Notebook

## 📌 Project Highlights

- Data Cleaning & Preprocessing
- Handling missing and duplicate values
- Exploratory Data Analysis (EDA):
  - App category distribution
  - Price distribution of apps (Free vs Paid)
  - Rating trends by category
  - Content ratings & install counts
  - Sentiment analysis of user reviews using word clouds
- Visualizations to identify trends and outliers
- Interactive plots using Plotly

## 📷 Sample Visualizations

- Pie charts of app categories
- Histograms of ratings and installs
- Boxplots of price distributions
- WordClouds for review sentiment (positive/negative)

## 🚀 How to Run

1. Clone the repository.
2. Ensure you have the required libraries installed (`pip install -r requirements.txt`).
3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Google_Play_Store_App_Analytics.ipynb
