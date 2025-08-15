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
- `BA_reviews.csv` – Collected reviews data.
- `1.scraping.py` – Script for scraping reviews.
- `2.cleaning.py` – Script for cleaning the dataset.
- `3.review_analysis.py` – Script for exploratory data analysis.
- `requirements.txt` – List of Python packages required to run the project.
- `README.md` – Project information and instructions.
---

## 🛠 Requirements
Install the dependencies before running the code:

```bash
pip install -r requirements.txt
