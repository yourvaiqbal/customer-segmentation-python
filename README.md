# Customer Segmentation Analysis with Python

## Project Overview

This project analyzes mall customer behavior using Exploratory Data Analysis (EDA) and KMeans Clustering techniques.

The objective of this project is to identify customer segments based on annual income and spending behavior, helping businesses better understand customer characteristics and improve marketing strategies.

### Business Value

This project demonstrates how customer segmentation can help businesses:
- Improve targeted marketing campaigns
- Identify high-value customers
- Optimize promotional strategies
- Increase customer retention through behavioral analysis

---

## Business Problem

Businesses often struggle to understand different customer behaviors and spending patterns.

Without customer segmentation:
- Marketing campaigns become less targeted
- Customer retention strategies become inefficient
- High-value customers may not be properly identified

This project helps identify distinct customer groups for better business decision-making.

---

## Project Objectives

- Perform Exploratory Data Analysis (EDA)
- Analyze customer income and spending behavior
- Apply KMeans Clustering for customer segmentation
- Identify high-value customer groups
- Generate business insights from clustering results

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code
- GitHub

---

## Dataset Information

Dataset contains mall customer information including:
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## Project Workflow

1. Data Loading
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis
5. Customer Segmentation
6. KMeans Clustering
7. Data Visualization
8. Business Insight Generation

---

## Key Insights

Advanced behavioral personas extracted via unsupervised KMeans Clustering (Optimized into 5 distinct customer segments based on Silhouette and Elbow method analysis):

* **Cluster 1 — Premium Affluent (High Income, High Spend):** The ultimate high-value segment. These customers possess substantial purchasing power combined with an aggressive spending score, serving as the core engine for high-margin luxury growth.
* **Cluster 2 — Under-Tapped Affluent (High Income, Low Spend):** High-earning individuals exhibiting conservative spending behavior. This signals a critical "Value-Gap"—meaning they have the capital, but our current product offerings or engagement strategies fail to capture their share-of-wallet.
* **Cluster 3 — Balanced Middle Market (Mid Income, Mid Spend):** The highest density cohort representing the average consumer base. They exhibit predictable, moderate spending patterns and provide foundational revenue stability for the business.
* **Cluster 4 — High-Yield Budget (Low Income, High Spend):** Lower-income tier users with disproportionately high spending scores. They are highly impulse-driven and responsive to lifestyle trends, but possess high price sensitivity.
* **Cluster 5 — Conservative Value (Low Income, Low Spend):** Highly frugal consumers optimizing strictly for necessity. This segment represents the lowest commercial priority for premium marketing campaigns.

---

## Strategic Recommendations

Actionable, data-backed playbooks designed for the Marketing and Product Strategy teams to optimize Customer Lifetime Value (LTV):

* **VIP Experiences for Premium Affluent:** Maximize retention within this elite cohort by deploying high-tier loyalty programs, personal concierge services, and early-access privileges to premium product rollouts.
* **Cross-Sell Intervention for Under-Tapped Affluent:** Launch personalized, value-driven campaigns showcasing premium quality, exclusive bundles, or high-end status rewards to incentivize these high-income savers to increase their checkout spend.
* **Flash Sales & BNPL for High-Yield Budget:** Capture this impulse-driven segment by leveraging highly visual social-commerce ads, trend-centric messaging, flash discounts, or flexible buy-now-pay-later (BNPL) payment methods.
* **Automated Engagement for Balanced Middle Market:** Implement automated email marketing cycles and steady baseline rewards to maintain their recurring transaction frequency without over-allocating heavy promotional discounts.

---

## Potential Business Impact

* **Algorithmic Persona Shift:** Transformed generic, flat demographic reporting into a dynamic, multi-dimensional machine learning clustering model—preventing ad-budget waste on blind target markets.
* **Optimized Customer Acquisition Cost (CAC):** Enabled the marketing department to transition away from broad "one-size-fits-all" ads and execute surgical, persona-based ad spend that matches verified spending behavior.

---

## Visualizations

### Elbow Method

![Elbow Method](output/elbow_method.png)

### Income vs Spending Score

![Income vs Spending](output/income_vs_spending.png)

### Customer Segments

![Customer Segments](output/customer_segments.png)

---

## Project Structure

```bash
customer-segmentation-python/
│
├── data/
│   ├── customer_data.csv
│
├── notebook/
│   └── customer_segmentation.ipynb
│
├── output/
│   ├── customer_segments.csv
│   ├── customer_segments.png
│   ├── elbow_method.png
│   └── income_vs_spending.png
│
└── README.md
```

---

## Final Conclusion

KMeans clustering successfully identified five distinct customer groups based on annual income and spending score.

This analysis can help businesses:
- Improve targeted marketing campaigns
- Increase customer retention
- Identify premium customer segments
- Optimize business strategies using customer behavior analysis

---

## Future Improvements

Possible future enhancements for this project:
- Add interactive dashboard using Power BI or Tableau
- Deploy clustering visualization using Streamlit
- Apply additional clustering techniques such as DBSCAN or Hierarchical Clustering
- Perform customer behavior prediction using Machine Learning

## Author

Ahmad Iqbal Maulana -  Data Analyst
