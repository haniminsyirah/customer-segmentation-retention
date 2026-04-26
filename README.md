# Customer Segmentation and Retention Analysis

## 📌 Project Overview
This project focuses on analyzing customer purchase data from an online retail store to understand behavior, segment customers into meaningful groups, and evaluate retention patterns. Using Python in Google Colab, I applied descriptive statistics, cohort analysis, and machine learning (K-Means Clustering) to drive data-driven marketing insights.

## 🚀 Main Objectives
* **Data Cleaning:** Prepared large transaction datasets by handling missing values and removing cancellations.
* **Cohort Analysis:** Measured customer retention by tracking acquisition groups over time.
* **RFM Segmentation:** Scored customers based on **Recency, Frequency, and Monetary** values.
* **K-Means Clustering:** Grouped customers into segments such as "Champions," "Loyal," and "At Risk."
* **CLV Prediction:** Modeled future value using BG/NBD and Gamma-Gamma probabilistic models.

## 🛠️ Tech Stack
- **Language:** Python
- **Environment:** Google Colab
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Lifetimes

## 📊 Key Methodologies
### 1. Cohort Analysis
I created monthly cohorts to visualize how many customers return month-over-month. This helps identify when customers typically "drop off."

### 2. RFM Analysis
Customers were assigned scores (1-4) based on:
- **Recency:** Days since last purchase.
- **Frequency:** Total number of transactions.
- **Monetary:** Total spend.

### 3. Machine Learning (K-Means)
Normalized the RFM data and used the **Elbow Method** to determine that 4 clusters provided the most actionable segmentation.



## 🎯 Key Outcomes & Findings
### 1. Retention Trends (Cohort Analysis)
* **Discovery:** Identified that customer retention typically peaks during the holiday season (November/December) but sees a significant drop-off in the following quarter.
* **Actionable Insight:** The business should implement a "New Year Re-engagement" campaign in January to retain customers acquired during the December peak.


### 2. Strategic Segmentation (RFM & K-Means)
* **Discovery:** The population was successfully divided into **4 distinct clusters** using the Elbow Method and Silhouette Analysis.
* **Top Segment (Champions):** This group accounts for the highest percentage of total revenue despite being a smaller portion of the total customer base.
* **At-Risk Segment:** Identified a group of "formerly loyal" customers who haven't purchased in 6+ months, allowing for targeted win-back email strategies.

### 3. Predictive Forecasting (CLV)
* **Discovery:** Using **BG/NBD** and **Gamma-Gamma** models, the project successfully predicted which customers are most likely to be "alive" (active) in the next 6 months.
* **Outcome:** We can now prioritize marketing spend on customers with the highest **Predicted Customer Lifetime Value**, optimizing the return on ad spend (ROAS).

## 📂 How to Run
1. Open the `.ipynb` file in Google Colab.
2. Upload the `Online Retail.xlsx` dataset to the session storage.
3. Run all cells to see the visualizations and model outputs.
