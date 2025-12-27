# Spark-Ecommerce-RFM-Analysis
E-commerce Behavioral Analytics: A Big Data Framework
Leveraging Apache Spark and CRISP-DM for Consumer Insights
This repository contains an end-to-end Big Data Analytics project designed to transform raw e-commerce transaction data into actionable business intelligence. Utilizing Apache Spark (PySpark), the project addresses complex challenges in customer segmentation, product association, and geographical revenue distribution.

🚀 Project Overview
In a highly competitive e-commerce landscape, understanding customer behavior is critical for retention and growth. This project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology to solve three primary business questions:

Customer Segmentation: How can we categorize our base into distinct behavioral personas (VIP, At-Risk, etc.)?

Market Basket Analysis: Which products are frequently purchased together to drive cross-selling?

Geographic Strategy: Where is our revenue concentrated, and how can we optimize regional marketing spend?

🛠️ Tech Stack & Methodology
Engine: Apache Spark 3.x (PySpark)

Environment: Jupyter Notebook / VS Code

Libraries: MLlib (K-Means, FP-Growth), Matplotlib, Seaborn, Pandas

Key Algorithms: * K-Means Clustering: For RFM (Recency, Frequency, Monetary) segmentation.

FP-Growth: For association rule mining and frequent itemset discovery.

Pareto Analysis: For geographic revenue concentration.

📊 Key Analytical Findings
1. Behavioral Customer Segmentation
Using K-Means clustering, we identified 4 distinct segments. The model was validated using the Elbow Method and Silhouette Scores to ensure mathematical separation.

Finding: 5% of our customers (Platinum Segment) generate nearly 40% of total revenue.

Visual Proof:

2. Market Basket Insights
We identified strong psychological associations between products, notably within specific home decor and kitchenware lines.

Finding: Customers purchasing 'Green Regency Teacups' have a >70% likelihood of purchasing the 'Pink' variant, indicating collection-completion behavior.

3. Revenue Concentration (Pareto 80/20)
Finding: Revenue is highly centralized, with the UK, EIRE, and Netherlands accounting for over 82% of the total business income.

💡 Business Recommendations
Automated Cross-Selling: Deploy recommendation engines on product pages based on our discovered association rules (Lift > 10).

Retention Campaigns: Target the "At-Risk" cluster with personalized re-engagement discounts before they churn.

Tiered Marketing Spend: Allocate 80% of the ad budget to Tier-1 markets (UK/EIRE/NL) while exploring high-AOV growth in France and Germany.
