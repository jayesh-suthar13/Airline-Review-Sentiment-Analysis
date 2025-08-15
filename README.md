# British Airways Reviews Project

This project collects British Airways customer reviews, processes the data, and performs analysis to understand sentiment patterns and common issues.

---

## 📌 Project Details
The project is divided into the following parts:

1. **Data Collection**
   - Scrapes customer reviews from a public website using `requests` and `BeautifulSoup`.
   - Saves the reviews to a CSV file for later use.

2. **Data Cleaning**
   - Removes extra spaces, special characters, and unnecessary text.
   - Handles missing values.
   - Prepares data for analysis.

3. **Data Analysis**
   - Calculates average ratings and sentiment scores.
   - Creates visualizations such as bar plots, word clouds, and sentiment trend charts.

---

## 📂 Files in This Repository
├── 1_web_scraping_BA.ipynb        # Notebook for scraping British Airways reviews
├── 2_data_cleaning_BA.ipynb       # Notebook for cleaning and preparing the dataset
├── 3_EDA_BA_Reviews.ipynb         # Notebook for EDA and visualizations
├── BA_reviews.csv                 # Raw scraped reviews data
├── cleaned-BA-reviews.csv         # Cleaned dataset after preprocessing
├── requirements.txt               # Python dependencies
└── README.md                      # Project documentation

---

## 🛠 Requirements
Install the dependencies before running the code:

```bash
pip install -r requirements.txt
