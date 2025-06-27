# 🍽️ Zomato India – Restaurant Trends, Costs & Consumer Insights

## 📌 Project Overview

This project performs an in-depth **Exploratory Data Analysis (EDA)** on restaurant listings from Zomato across Indian cities. The goal is to extract valuable **business insights**, analyze **consumer behavior**, and identify patterns that could help a platform like Zomato **optimize services, target expansion**, and enhance customer engagement.

---

## 📂 Dataset

**Name**: Zomato Restaurants in India  
**Source**: [Kaggle – Zomato India Restaurants](https://www.kaggle.com/datasets/rabhar/zomato-restaurants-in-india)  
**Size**: ~9500 records | 21 columns  
**Features include**:
- Restaurant name, location, cuisines
- Average cost for two, rating, votes
- Online delivery and table booking flags
- City, locality, and cuisine details

---

## 🧠 Problem Statement

> “What insights can we uncover from Indian Zomato listings to understand city trends, popular cuisines, cost dynamics, and consumer preferences — to guide business expansion and strategy?”

---

## 🎯 Objectives

- Identify cities with the most Zomato-listed restaurants  
- Analyze cost patterns across cities and cuisines  
- Study the relation between ratings, cost, and delivery options  
- Explore popularity (votes) and high-rated restaurants  
- Provide data-driven business suggestions

---

## 🧩 Skills Applied

| Category          | Tools Used                   |
|-------------------|------------------------------|
| Data Wrangling    | `Pandas`, `NumPy`            |
| Visualization     | `Matplotlib`, `Seaborn`      |
| Data Cleaning     | Null handling, type parsing  |
| Business Analysis | Insight generation & summary |
| Version Control   | `Git`, `GitHub`              |

---

## 📊 Key Insights
 1. Chennai Has the Most Restaurants Listed
Chennai tops the list with 11,630 restaurants, ahead of Mumbai and Bangalore.
This shows strong Zomato adoption in southern India.

🧾 "Zomato’s highest coverage is in Chennai — a potential city for deeper food partner expansion."

🍛 2. North Indian and Chinese are India’s Go-To Cuisines
With over 85,000 listings, North Indian is the most common cuisine on Zomato.
Chinese and Fast Food follow closely.

🧾 "Traditional and casual cuisines dominate — ideal for promotions and combo offers."

💰 3. High Rating ≠ High Price
Scatterplot shows no strong link between cost and rating.
Affordable places often have 4.5+ ratings.

🧾 "Customers value quality and taste more than price — great food can be cheap."

🚚 4. Restaurants with Delivery Get More Votes
Feature	Avg Rating	Avg Votes
Delivery ✅	3.74	411
No Delivery ❌	3.22	362

Delivery availability improves visibility and customer interaction.

🧾 "Delivery-ready restaurants tend to be more popular — Zomato should help partners enable it."

💸 5. Some Restaurants Offer Exceptional Value
Name	City	Rating	Cost	Value Score
Sharma Ji Ki Chai	Lucknow	4.8	₹50	0.0960
Fateh Ki Kachori	Delhi	4.3	₹50	0.0860

These spots give premium ratings at low cost — perfect for student/office crowds.

🧾 "Zomato can highlight these ‘value heroes’ with a badge or featured section."


(--see visuals in notebook for more info--)

## 📁 Project Structure

```bash
Zomato-India-EDA/
│
├── Zomato_EDA.ipynb       # Final analysis notebook
└── README.md              # Project summary and documentation