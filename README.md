# 📊 ChatGPT User Reviews Analysis

## 📌 Project Overview

With the rapid adoption of ChatGPT, users have shared thousands of reviews expressing their experiences, opinions, and suggestions. This project analyzes ChatGPT user reviews to understand customer sentiment, identify common issues, and examine how user feedback changes over time.

The analysis is performed using Python and popular data analysis libraries in Google Colab.

---

## 🎯 Problem Statement

People have shared a wide range of feedback about ChatGPT through ratings and written reviews.

The objective of this project is to:

- Identify **positive, negative, and neutral** user sentiments.
- Detect **common issues** driving negative reviews.
- Analyze **sentiment trends over time**.
- Generate actionable insights to understand user satisfaction and areas for improvement.

---

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Dataset Information

The dataset contains user reviews collected from ChatGPT users and includes the following information:

- Review ID
- Review Text
- Rating (1–5)
- Review Date

---

## 📋 Project Workflow

### 1. Data Cleaning

- Loaded the dataset
- Checked dataset structure and data types
- Converted review dates to datetime format
- Handled missing values
- Removed duplicate records

---

### 2. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand the dataset by analyzing:

- Rating distribution
- Review length distribution
- Monthly review trends
- Day-wise review distribution

---

### 3. Sentiment Analysis

Since ratings were available, sentiment categories were created using the following mapping:

| Rating | Sentiment |
|---------|-----------|
| 4–5 | Positive |
| 3 | Neutral |
| 1–2 | Negative |

The distribution of each sentiment category was then analyzed using visualizations.

---

### 4. Issue Identification

To identify common customer complaints:

- Filtered only negative reviews
- Cleaned review text
- Removed punctuation and common stop words
- Calculated word frequencies
- Visualized the most frequent words using bar charts

A deeper analysis was also performed for **July**, the month with the highest number of negative reviews, to identify the primary issues reported during that period.

---

### 5. Time-Series Analysis

Analyzed how user sentiment changed over time by examining:

- Monthly review distribution
- Monthly negative sentiment trends
- Identification of months with unusually high negative feedback

---

## 📊 Key Insights

- Most users gave **positive ratings**, indicating an overall positive perception of ChatGPT.
- Review lengths are **right-skewed**, showing that most users leave concise feedback.
- **July recorded the highest number of negative reviews**, suggesting a period of increased user dissatisfaction.
- Frequent words in negative reviews highlighted common issues related to performance, errors, login, and subscription experiences.
- Longer reviews generally provided more detailed feedback and helped identify recurring user concerns.

---

## 📈 Visualizations

The project includes multiple visualizations, including:

- Rating Distribution
- Review Length Distribution
- Monthly Review Trends
- Sentiment Distribution
- Negative Sentiment by Month
- Top Frequent Words in Negative Reviews
- Top Frequent Words in July Negative Reviews

---

## 📁 Repository Structure

```
ChatGPT-Reviews-Analysis/
│
├── ChatGPT_reviews_Project.ipynb
├── README.md
└── dataset.csv
```

---

## 🚀 Future Improvements

- Perform NLP-based sentiment analysis using review text.
- Build interactive dashboards using Power BI or Tableau.
- Analyze bigrams and trigrams to identify common user complaints more accurately.
- Create predictive models for sentiment classification.

---

## 📌 Conclusion

This project demonstrates a complete data analysis workflow, starting from data cleaning and exploratory analysis to sentiment analysis and issue identification.

The findings provide valuable insights into user satisfaction and highlight recurring issues that can help improve the ChatGPT user experience.

---

## 👨‍💻 Author

**Abhisek Pattanayak**

Data Analytics Enthusiast

- Python
- SQL
- Excel
- Pandas
- NumPy
- Matplotlib
- Seaborn
