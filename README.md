Customer Segmentation and Retention Analysis

This project involves performing customer segmentation and retention analysis on an online retail dataset using Python in Google Colab. The analysis includes data cleaning, cohort analysis, RFM segmentation, clustering, and customer lifetime value (CLV) modeling.

Introduction

Understanding customer behavior is key to designing targeted marketing strategies, improving customer retention, and increasing revenue. This project applies statistical and machine learning techniques to analyze purchase data, segment customers, and predict future value.

Dataset

The dataset used is an online retail transactions dataset with the following fields:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

You can download the dataset from [source link] and upload it directly to Google Colab.

Objectives

- Clean and preprocess retail transaction data
- Conduct cohort analysis to study customer retention over time
- Segment customers using RFM analysis
- Cluster customers through K-Means for more granular segmentation
- Visualize customer segments with scatter plots and snake plots
- Build models to estimate Customer Lifetime Value (CLV)

Methodology

The analysis proceeds through these key steps:

1. Data Loading & Cleaning
Upload the Online Retail.xlsx file to your Google Colab environment and load it using pandas.

2. Exploratory Data Analysis
Visualize transaction trends, identify top products, and analyse customer purchase patterns.

3. Cohort Analysis
Assign customers to cohorts based on their first purchase month and measure retention.

4. RFM Segmentation
Calculate Recency, Frequency, and Monetary metrics, score customers, and define segments.

5. Clustering
Normalize RFM features, determine optimal clusters using elbow method, and analyze segments visually.

6. Customer Lifetime Value Prediction
Use probabilistic models to forecast future customer value (CLV).

Environment & Setup

This project is optimized to run entirely in Google Colab. No local setup is necessary.

To get started:

1. Open the Google Colab Notebook link.
2. Upload the Online Retail.xlsx file directly into the Colab environment:
3. Run the notebook cells sequentially. The code is pre-configured to work with the uploaded dataset.


Results & Insights

Great question! When you include a section like "Results & Insights", you can highlight specific, tangible findings from your analysis that showcase the value of your work. Here are some example findings you might include based on the insights typically obtained from such a customer segmentation and retention project:

Results & Insights

- Customer Segments Identified:
The clustering analysis revealed distinct customer groups such as Big Spenders, Loyal Customers, Occasional Shoppers, and Lost Customers, each with unique purchasing behaviors.

- High-Value Customer Profile:
Customers in the 'Big Spenders' segment tend to have high recency and monetary scores, indicating recent high-value purchases. These customers should be targeted for loyalty programs.

- At-Risk Customers Detected:
Segments with low recency, low frequency, and low monetary value — often labeled as 'Lost' or 'Almost Lost' — highlight customers at risk of churn. Tailored re-engagement campaigns could be designed for these groups.

- Retention Patterns Observed:
The cohort analysis showed that retention drops sharply after the initial months, especially around the holiday season, emphasizing the need for targeted post-purchase engagement.

- Seasonality Effects:
Monthly gross sales indicate a peak in December followed by a sharp decline, which aligns with holiday shopping trends. This insight can inform inventory planning and marketing strategies.

- Customer Lifetime Value (CLV) Estimations:
The probabilistic models predict that top-tier customers (e.g., in the 'Best Customers' segment) are likely to generate significant future revenue, emphasizing the importance of personalized marketing for these groups.

- Attribute Importance for Segments:
Heatmaps and snake plots indicate that Recency and Monetary spend are the most distinguishing features for high-value segments, guiding targeted promotional efforts.

- Optimal Number of Clusters:
The elbow method and silhouette scores suggest that four clusters provide the best balance between segmentation granularity and interpretability.

