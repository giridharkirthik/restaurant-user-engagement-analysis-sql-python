# 🍽️ Restaurant User Engagement & Success Analysis – Yelp Dataset

Analyzing how **user engagement** (reviews, tips, check-ins, sentiment) relates to restaurant success metrics (review count, ratings) using **SQL, Python, and Power BI**.

---

## 📌 Table of Contents
- [Overview](#-overview)  
- [Business Problem](#-business-problem)  
- [Dataset](#-dataset)  
- [Tools & Technologies](#-tools--technologies)  
- [Project Structure](#-project-structure)  
- [Data Cleaning & Preparation](#-data-cleaning--preparation)  
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)  
- [Research Questions & Key Findings](#-research-questions--key-findings)  
- [Dashboard](#-dashboard)  
- [How to Run This Project](#-how-to-run-this-project)  
- [Final Recommendations](#-final-recommendations)  
- [Author & Contact](#-author--contact)  

---

## 📖 Overview
In a competitive market like the restaurant industry, understanding the factors that influence business success is crucial for stakeholders.

This project investigates the relationship between **user engagement** (reviews, tips, check-ins) and **business success metrics** (review count, ratings) for restaurants using the **Yelp dataset**.

---

## 🎯 Business Problem
Restaurants need to understand:  
- How user engagement affects ratings and review counts.  
- Whether positive sentiment in reviews and tips contributes to business success.  
- If consistent engagement over time predicts long-term success better than sporadic activity.  

---

## 📂 Dataset
- Subset of Yelp covering 8 metropolitan areas in the USA and Canada.  
- Original data provided as JSON files: `business`, `review`, `user`, `tip`, `checkin`.  
- JSON files stored in a database for easy retrieval.  

**Key Stats:**  
- 150K businesses total  
- 35K are open restaurants  

---

## 🛠️ Tools & Technologies
- **SQL** → Data ingestion and queries  
- **Python** → Pandas, Matplotlib, Seaborn, SciPy  

---

## 🧹 Data Cleaning & Preparation
- Data stored in a database for structured queries  
- Removed closed businesses and non-restaurant entries  
- Handled missing or inconsistent data in review, check-in, and tip files  

---

## 📊 Exploratory Data Analysis (EDA)

### Business Success Metrics
- Higher ratings do not guarantee higher review counts, or vice versa.  
- Review count reflects engagement but not necessarily satisfaction or overall performance.  

### Engagement Trends
- Engagement (reviews, tips, check-ins) generally increases from 1 → 4 stars.  
- Restaurants rated 4 stars show the highest engagement; slight drop at 5 stars.  

### User Engagement Correlations
- Reviews, tips, and check-ins are positively interlinked.  
- Boosting one type of engagement often increases others.  

### Time Patterns
- High-rated restaurants (≥3.5 stars) maintain consistent or increasing engagement over time.  

### Geographic Trends
- Philadelphia tops the success score chart.  
- Tampa, Indianapolis, and Tucson also rank highly.  

### Sentiment Analysis
- Counts of “useful,” “funny,” and “cool” reviews correlate with higher engagement and satisfaction.  

### Elite Users
- Elite users are fewer but contribute a large proportion of total reviews.  
- Positive engagement with elite users drives loyalty and repeat visits.  

### Busiest Hours
- Peak engagement between 4 PM – 1 AM  
- Evening/night demand likely driven by work schedules, social gatherings, and leisure activities  

---

## ❓ Research Questions & Key Findings
- **Do restaurants with higher engagement tend to have higher ratings?**  
  - 4-star restaurants show peak engagement; 5-star slightly lower.  

- **Is there a difference in engagement between high-rated and low-rated businesses?**  
  - Higher ratings show increased engagement across reviews, tips, and check-ins.  

- **Correlation between reviews, tips, and check-ins**  
  - Engagement across these is strongly interlinked.  

- **Time-based engagement patterns**  
  - Consistent engagement over time correlates with higher success.  

- **Geographic variation**  
  - Philadelphia, Tampa, Indianapolis, Tucson show highest success scores.  

- **Sentiment impact**  
  - Useful, funny, and cool reviews enhance engagement metrics.  

- **Elite vs Non-Elite Users**  
  - Elite users contribute disproportionately to review count.  

- **Busiest Hours**  
  - Peak engagement occurs 4 PM – 1 AM  

---

## 📊 Dashboard
Power BI Dashboard provides insights on:  
- Ratings vs Engagement Metrics  
- Sentiment Analysis  
- Elite User Contributions  
- Geographic Performance  
- Peak Hours  

---

## ⚡ How to Run This Project
'''bash
# 1️⃣ Clone repository
git clone https://github.com/your-username/restaurant-user-engagement-analysis.git

cd restaurant-user-engagement-analysis


# 3️⃣ Run ingestion script to populate database
scripts/ingestion_db.py

---

## ✅ Final Recommendations
- Collaborate with elite users to boost engagement and loyalty.  
- Optimize operating hours and staffing to match peak engagement.  
- Focus on consistent engagement strategies.  
- Respond actively to feedback (“useful,” “funny,” “cool”).  
- Target high-success cities for expansion: Philadelphia, Tampa, Indianapolis, Tucson.  

---

## 👤 Author & Contact
**Giridhar Kirthik H**  
📧 [giridharkirthikh2001@gmail.com](mailto:giridharkirthikh2001@gmail.com)
