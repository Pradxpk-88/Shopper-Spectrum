# 🛒 Shopper Spectrum: Customer Segmentation and Product Recommendation System

## 📌 Overview

Shopper Spectrum is a Machine Learning and Retail Analytics project designed to analyze customer purchasing behavior using online retail transaction data. The project combines customer segmentation and personalized product recommendations to help businesses better understand their customers and improve marketing effectiveness.

Using RFM (Recency, Frequency, Monetary) analysis, K-Means clustering, and collaborative filtering techniques, the system identifies valuable customer segments and recommends relevant products based on purchasing patterns.

---

## 🎯 Objectives

* Analyze customer purchasing behavior from retail transaction data
* Segment customers based on RFM metrics
* Identify high-value, regular, occasional, and at-risk customers
* Build a personalized product recommendation system
* Generate actionable business insights for customer retention and marketing
* Develop an interactive Streamlit application for real-time predictions

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries & Frameworks

* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Streamlit

### Machine Learning Techniques

* RFM Analysis
* K-Means Clustering
* Collaborative Filtering
* Cosine Similarity

---

## 📂 Project Structure

```text
Shopper-Spectrum/
│
├── docs/
│   └── Project Documentation
│
├── models/
│   └── Trained ML Models
│
├── app.py
├── requirements.txt
├── customer_segmentation.ipynb
├── recommendation_system.ipynb
└── README.md
```

---

## 🔍 Project Workflow

### 1. Data Collection & Understanding

* Explored online retail transaction data
* Examined data structure and quality
* Identified missing values and inconsistencies

### 2. Data Preprocessing

* Removed records with missing Customer IDs
* Excluded cancelled transactions
* Eliminated invalid quantities and prices
* Prepared clean data for analysis

### 3. Exploratory Data Analysis (EDA)

* Transaction volume analysis
* Top-selling product analysis
* Customer spending patterns
* Country-wise sales distribution
* Purchase trend visualization

### 4. Customer Segmentation

#### RFM Analysis

* **Recency** – How recently a customer purchased
* **Frequency** – How often a customer purchases
* **Monetary** – How much a customer spends

#### K-Means Clustering

Customers are grouped into meaningful segments such as:

* High-Value Customers
* Regular Customers
* Occasional Customers
* At-Risk Customers

### 5. Product Recommendation System

Implemented an Item-Based Collaborative Filtering approach using cosine similarity to recommend products based on customer purchase behavior.

The system generates personalized recommendations by identifying products with similar purchasing patterns.

---

## 📊 Key Features

### 🎯 Customer Segmentation Module

Users can enter:

* Recency
* Frequency
* Monetary Value

The system predicts the customer segment and provides behavioral insights.

### 🎯 Product Recommendation Module

Users can enter a product name and receive:

* Top 5 similar product recommendations
* Similarity-based product suggestions
* Personalized recommendation outputs

---

## 📈 Business Value

This project helps businesses:

* Improve customer retention
* Personalize shopping experiences
* Increase customer engagement
* Support targeted marketing campaigns
* Identify valuable customer groups
* Optimize inventory planning

---

## 🚀 Future Enhancements

* Deep Learning-based Recommendation Models
* Real-Time Customer Analytics Dashboard
* Hybrid Recommendation System
* Advanced Customer Lifetime Value Prediction
* Cloud Deployment with AWS or Azure

---

## 🎓 Skills Demonstrated

* Data Cleaning & Preprocessing
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Customer Analytics
* Machine Learning
* Unsupervised Learning
* K-Means Clustering
* Recommendation Systems
* Collaborative Filtering
* Streamlit Deployment
* Business Intelligence

---

## 👨‍💻 Author

**Prathep Kumar R**

B.Tech Artificial Intelligence & Data Science

Aspiring Data Scientist | Machine Learning Enthusiast | Data Analyst

* GitHub: https://github.com/Pradxpk-88
* LinkedIn: https://linkedin.com/in/prathep-kumar-465734292

---

⭐ If you found this project useful, consider giving it a star.
