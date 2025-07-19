# Customer-Segmentation-RFM

## Project Overview
This project aimed to help an e-commerce seller on Spotify establish a value-based customer segmentation system to assist them in managing customers more efficiently and increasing repurchase rates.

We began with several million rows of raw order records and performed data cleaning and preprocessing using Python. 

For each customer, we calculated their **RFM (Recency, Frequency, Monetary)** scores:
- **Recency**: time since last purchase – indicates activity level
- **Frequency**: number of purchases in a given period – measures stickiness
- **Monetary**: total amount spent – reflects spending power

Using these RFM features, we applied the **K-Means clustering algorithm** to segment users into six distinct groups, such as **VIP**, **high potential**, and **inactive** users. The optimal number of clusters was determined using the elbow method and validated with silhouette scores.

Based on the clustering results, we designed **personalized marketing strategies** for each segment, including targeted discounts for VIPs and customized follow-up for high-potential users. 

After deploying the segmentation-based strategy, we tracked behavior over 30 days. The results showed:
- **Repeat purchase rate increased by 11 percentage points**
- **Average order value (AOV) rose by 25%**

Statistical validation via **two-sample t-tests** confirmed that both improvements were **significantly different** from the baseline, indicating strong business value of the segmentation framework.
