# <p align = 'center'>Product-Analytics-and-Recommendation-System-for-Online-Retail</p>

## 🧠 Project Overview

This project focuses on two essential pillars of marketing analytics:
- **Product Analytics**: Understanding customer behavior and product performance over time.
- **Product Recommendations**: Leveraging collaborative filtering to recommend relevant products to users.

The dataset used for this analysis is the **Online Retail** dataset available on [Kaggle](https://www.kaggle.com/). It covers transactions from a UK-based online retailer from **December 2010 to November 2011**.

---

## 🗂️ Table of Contents

1. [Introduction](#introduction)
2. [Dataset & Setup](#dataset--setup)
3. [Product Analytics](#product-analytics)
   - 3.1 [Number of Orders Over Time](#31-number-of-orders-over-time)
   - 3.2 [Revenue Over Time](#32-revenue-over-time)
   - 3.3 [Repeat Customers Over Time](#33-repeat-customers-over-time)
   - 3.4 [Repeat Customer Revenue Over Time](#34-repeat-customer-revenue-over-time)
   - 3.5 [Popular Items Over Time](#35-popular-items-over-time)
4. [Product Recommendations](#product-recommendations)
   - 4.1 [Collaborative Filtering](#41-collaborative-filtering)
     - 4.1.1 [User-based Collaborative Filtering](#411-user-based-collaborative-filtering)
     - 4.1.2 [Item-based Collaborative Filtering](#412-item-based-collaborative-filtering)
5. [Conclusion](#conclusion)

---

## 📌 Introduction

This project began with a focus on conversion rate analysis, leading into more advanced aspects of marketing analytics—specifically, **product performance** and **recommendation systems**. 

The project is structured to analyze one full year of retail transaction data and draw insights into:
- Purchase behaviors
- Revenue trends
- Customer loyalty
- Personalized product recommendations

---

## 📥 Dataset & Setup

The dataset used is from **Kaggle’s Online Retail** repository. It contains transactional records including:
- Invoice numbers
- Product details
- Quantity purchased
- Unit price
- Customer ID
- Invoice dates

The data is filtered to cover the period from **December 1, 2010 to November 30, 2011** to allow for a comprehensive annual analysis.

---

## 📈 Product Analytics

### 3.1 Number of Orders Over Time

Visualized the trend in monthly order counts, highlighting seasonal spikes and troughs in customer activity.

### 3.2 Revenue Over Time

Calculated monthly revenue by multiplying `Quantity` and `UnitPrice`. The resulting sales figures were analyzed to identify periods of high and low performance.

### 3.3 Repeat Customers Over Time

- Extracted unique purchase orders.
- Tracked customers with multiple purchases per month.
- Compared repeat customers with total customers to derive repeat percentages.

### 3.4 Repeat Customer Revenue Over Time

- Calculated revenue contributions from repeat customers.
- Assessed the percentage of total monthly revenue attributable to returning customers.

### 3.5 Popular Items Over Time

- Identified top-selling products in the final month (Nov 2011).
- Tracked the purchase trend of these items over time to understand long-term popularity.

---

## 🤖 Product Recommendations

### 4.1 Collaborative Filtering

A recommendation system was developed using two approaches:

#### 4.1.1 User-based Collaborative Filtering

- Compared users based on their purchase histories.
- Recommended products favored by similar users.

#### 4.1.2 Item-based Collaborative Filtering

- Compared products based on co-occurrence in transactions.
- Recommended items that are frequently bought together.

---

## ✅ Conclusion

This project provided insights into:
- Seasonal customer behaviors
- Repeat customer contributions
- Top-selling product trends
- Personalized recommendations through collaborative filtering

Such analytics are essential for businesses aiming to increase revenue, improve retention, and deliver a more personalized shopping experience.

---

## 📌 Future Enhancements

- Implement content-based recommendation models.
- Integrate customer demographics for deeper segmentation.
- Use deep learning models (e.g., autoencoders) for improved recommendation accuracy.

---

## 📁 Resources

- 📂 Dataset: [Kaggle - Online Retail](https://www.kaggle.com/)
- 📘 Libraries used: pandas, numpy, matplotlib, scikit-learn


