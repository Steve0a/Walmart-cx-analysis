# 🛒 Walmart Customer Experience Analysis
### Turning Customer Reviews into Actionable Insights

![Walmart Store](images/Image_of_Walmart_Store_2.webp)

---

> **Disclaimer:** This project is a conceptual and educational representation created for business analysis and portfolio purposes. It does not represent the official or proprietary process of Walmart. The model is based on publicly available information, logical workflow structuring, and standard analytical practices.

---

## 📌 Project Overview

This project analyzes customer reviews from **Walmart Store #4553 (Kansas City, MO)** to understand how customers feel about their shopping experience.

Using Python and text analytics, I transformed unstructured review data into clear insights that help improve operations, staff performance, and customer satisfaction.

![Walmart Store Workflow](images/Walmart_Super_Store_Customer_Workflow.png)

---

## 🎯 Key Questions Answered

- What do customers generally think about their experience?
- Which store areas receive the most feedback?
- Are customers more positive or negative in specific areas?
- Which staff members are mentioned and why?
- How has customer sentiment changed over time?

---

## 🧠 Approach

1. Data Collection (SerpAPI)
2. Data Cleaning (NLP preprocessing)
3. Word Frequency Analysis
4. Named Entity Recognition (spaCy)
5. Sentiment Analysis (VADER)
6. Aspect-Based Sentiment Analysis
7. Trend Analysis
8. Staff-Level Insights

---

## 📊 Key Visualizations

### Overall Customer Sentiment
![Sentiment Distribution](images/3_Sentiment_Chart.png)

### Sentiment by Star Rating
![Sentiment by Rating](images/3_Sentiment_Rating_Chart.png)

### Top 20 Named Entities (Type Distribution)
![Entity Type Distribution](images/1_Entity_Chart_Top_20.png)

### Top 20 Most Mentioned Named Entities
![Top Named Entities](images/2_Entity_Chart_Top_20.png)

### What Customers Think About Store Departments
![Store Units Sentiment](images/4_Sentiment_Store_Units_Chart.png)

### What Customers Think About Staff
![Staff Sentiment](images/4_Sentiment_Staff_Chart.png)

### Store Experience Aspect Sentiment
![Store Experience Aspects](images/5_Store_Experience_Aspect_chart.png)

### 2025 Trend – Positive Checkout Feedback
![Positive Checkout Trend](images/6_Positive_Checkout_Review_Trend_Chart.png)

### 5-Year Trend – Negative Checkout Feedback
![Negative Review Trend](images/6_Negative_Review_Trend_Chart.png)

### 2025 Trend – Negative Staff Feedback
![Negative Staff Trend](images/6_Negative_Staff_Review_Trend_Chart.png)

---

## 📊 Key Insights

- Customers are **generally positive (52%)**, but issues are concentrated
- **Checkout and Auto Care** show the most negative feedback
- **Staff interactions** strongly influence customer satisfaction
- Feedback clearly highlights operational problem areas

---

## 💡 Real-World Impact

- Identify operational issues quickly
- Improve checkout efficiency
- Recognize high-performing staff
- Monitor trends over time

---

## ⚠️ Limitations

- Limited dataset (Google reviews only)
- VADER may miss sarcasm
- Keyword-based aspect classification
- Single store focus

---

## 🛠️ Tools & Technologies

- **Python** (pandas, NumPy)
- **NLP:** NLTK, spaCy
- **Sentiment Analysis:** VADER
- **Visualization:** Matplotlib, Seaborn, Altair
- **API:** SerpAPI

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```

---

## 📁 Project Structure

```
Walmart-cx-analysis/
├── README.md
├── requirements.txt
├── notebook.ipynb
├── data/
│   ├── reviews.csv
│   ├── reviews_with_sentiment.csv
│   └── name_entities.csv
├── images/
│   └── (all chart images)
└── docs/
    └── project_summary.md
```

---

## 👤 Author

**Steve O** | [@Steve0a](https://github.com/Steve0a)  
Data Analyst | Business Intelligence | NLP Enthusiast  
📍 Kansas City, MO
