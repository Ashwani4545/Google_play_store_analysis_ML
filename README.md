# 📊 Google Play Store Data Analysis — EDA & Insights
## 📌 Project Overview

This project performs an exploratory data analysis (EDA) of Google Play Store applications to uncover trends, patterns, and actionable insights about the Android app ecosystem.
It analyzes more than 10,000+ apps across categories, ratings, installs, pricing models, genres, and user engagement.

Using Python, Pandas, and Plotly, the notebook provides:

Category-level breakdown of apps

Popularity and rating insights

Distribution of reviews and installs

Free vs Paid comparison

Genre analysis

Data cleaning & preprocessing

This project is ideal for data analysis, visualization practice, and understanding app-store market behavior.

## 📁 Repository Structure
Google_play_store_analysis_ML/
│
├── data/
│   └── googleplaystore.csv      # Raw dataset (uploaded)
│
├── notebooks/
│   └── Google_Play_Analysis.ipynb   # EDA notebook
│
├── README.md
└── requirements.txt

## 📊 Dataset Description

The dataset used contains the following key features:

Column	Description
App	App name
Category	App category (GAME, FAMILY, TOOLS, etc.)
Rating	User rating (1–5)
Reviews	Number of user reviews
Size	App size
Installs	Number of installs
Type	Free or Paid
Price	App price
Content Rating	Age-group suitability
Genres	App genres
Last Updated	Update timestamp
Current Ver	Current version
Android Ver	Required Android version

## 🔍 Key Analysis Performed
### ✔ Data Cleaning

Removed duplicates

Cleaned installs and price columns

Converted categories and ratings

Formatted dates

### ✔ Visual Explorations

Number of apps per category

Most competitive app categories

Distribution of ratings

Distribution of installs

Free vs Paid app comparisons

Top-grossing app categories

### ✔ Insights Extracted (Examples)

Categories like FAMILY, GAME, TOOLS dominate the Play Store.

Most apps are free → monetization occurs via ads + in-app purchases.

Highly-rated apps typically occupy categories like EDUCATION or HEALTH & FITNESS.

Paid apps have fewer installs but slightly higher average ratings.

📈 Technologies Used

Python

Pandas — data manipulation

Plotly — interactive visualizations

Matplotlib/Seaborn — optional plots

Jupyter Notebook

Install dependencies:

pip install -r requirements.txt

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/Ashwani4545/Google_play_store_analysis_ML.git
cd Google_play_store_analysis_ML


Install required libraries:

pip install -r requirements.txt


Open the notebook:

jupyter notebook


Run the EDA notebook step-by-step to explore insights.

📌 Future Enhancements

Build a predictive model to estimate:

App rating

App success probability

Install count category

Dashboard using Streamlit or Power BI

Sentiment analysis of app reviews (if review dataset added)

Feature engineering for ML

Category recommendation system for new developers

📜 License

This project is open-source under the MIT License.

👨‍💻 Author

Ashwani Pandey
Machine Learning & Data Science Developer
