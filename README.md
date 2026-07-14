# 🤖 AI Customer Feedback Analyzer

An AI-powered customer feedback analysis project that uses **Natural Language Processing (NLP)** to classify Amazon customer reviews into **Positive, Neutral, and Negative** sentiments. The project also includes an interactive **Power BI dashboard** to visualize customer feedback and generate business insights.

---

## 📌 Project Overview

Customer reviews provide valuable insights into customer satisfaction. This project analyzes Amazon Fine Food Reviews using Python and VADER Sentiment Analysis to automatically classify review sentiment and visualize the results through an interactive Power BI dashboard.

---

## 🚀 Features

- 📊 Data Cleaning and Preprocessing
- 📈 Exploratory Data Analysis (EDA)
- 🤖 AI-Based Sentiment Analysis using NLTK VADER
- 📉 Rating Distribution Analysis
- 📅 Monthly Review Trend Analysis
- 📊 Interactive Power BI Dashboard
- 💡 AI Insights with Top Positive and Negative Words

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK (VADER)
- Matplotlib
- Power BI

---

## 📂 Dataset

**Dataset:** Amazon Fine Food Reviews

- Original Dataset: **568,454 customer reviews**
- Working Dataset: **5,000 randomly sampled reviews**

Dataset Columns:
- Score
- Summary
- Text
- Time
- AI_Sentiment
- AI_Sentiment_Score

---

## 📊 Dashboard Features

### Dashboard Page

- Total Reviews
- Average Rating
- Positive Reviews
- Negative Reviews
- Neutral Reviews
- Customer Rating Distribution
- Customer Sentiment Distribution
- Monthly Review Trend
- Interactive Filters

### AI Insights Page

- Top 10 Positive Words
- Top 10 Negative Words
- Sample Positive Reviews
- Sample Negative Reviews

---

## 📷 Dashboard Preview

### Dashboard

> Add your screenshot here after uploading.

![Dashboard](screenshots/dashboardpage1.png)

### AI Insights

> Add your screenshot here after uploading.

![AI Insights](screenshots/dashboardpage2.png)

---

## 📁 Project Structure

```text
AI-Customer-Feedback-Analyzer/
│
├── data/
│   ├── Reviews_5000.csv
│   ├── final_reviews.csv
│   ├── top_positive_words.csv
│   └── top_negative_words.csv
│
├── notebook/
│   └── AI_Customer_Feedback_Analyzer.ipynb
│
├── dashboard/
│   └── AI_Customer_Feedback_Analyzer.pbix
│
├── screenshots/
│   ├── dashboard_page1.png
│   └── dashboard_page2.png
│
├── README.md
└── requirements.txt
```

---

## 📈 Business Insights

- Most customer reviews are positive.
- Average customer rating is above 4/5.
- Positive reviews highlight product quality and taste.
- Negative reviews commonly mention packaging and product quality issues.
- The dashboard enables quick analysis of customer feedback and sentiment trends.

---

## ▶️ How to Run

1. Clone this repository.
2. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebook.
5. Open the Power BI (`.pbix`) file to explore the dashboard.

---

## 👩‍💻 Author

**Menakha Sripriya C**

