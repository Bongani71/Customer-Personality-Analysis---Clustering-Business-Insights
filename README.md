# Customer Personality Analysis — Clustering & Business Insights

## Project Overview

This project analyses customer data from a retail company.

The goal is to group customers into different segments based on:

- Personality
- Spending habits
- Income
- Household profile
- Shopping behaviour

I used a **KMeans** clustering model to find **4 customer groups**.

The final results give simple business insights that can help a company target the right customers with the right marketing campaigns.

## Dataset

- **Dataset used:** [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
- **Source:** Kaggle

## Tools Used

- Python
- pandas
- pandasql
- matplotlib
- seaborn
- scikit-learn

## What I Did

1. Loaded the dataset using pandas.
2. Explored the data using pandas and SQL queries.
3. Checked for missing values.
4. Filled missing income values using the median income.
5. Removed extreme outliers, such as income of $666,666.
6. Fixed the date column.
7. Removed columns that were not useful.
8. Created new features:
   - Age
   - TotalSpend
   - TotalChildren
   - TotalPurchases
9. Created charts to understand customer behaviour.
10. Scaled the data using `StandardScaler`.
11. Used the Elbow Method to choose the best number of clusters.
12. Selected **k = 4** clusters.
13. Built a KMeans clustering model.
14. Assigned each customer to a segment.
15. Used PCA to visualise the clusters in 2D.
16. Profiled each customer segment.
17. Gave each segment a business name.
18. Wrote business insights and recommendations.

## Customer Segments

| Segment | Customers | Average Income | Average Spend |
|---------|-------------|----------------|---------------|
| Elite Buyers | 554 | $77,204 | $1,429 |
| Affluent Regulars | 596 | $59,301 | $729 |
| Moderate Spenders | 659 | $30,872 | $111 |
| Budget Conscious | 427 | $41,469 | $129 |

## Key Finding

**Elite Buyers** are the most valuable customers.

They spend about **13 times more** than Budget Conscious customers.

Even though they are only about **25%** of the customer base, they bring very high value.

## Business Recommendation

The company should focus more marketing campaigns on **Elite Buyers**.

This group is more likely to respond to:

- Premium offers
- Loyalty rewards
- Exclusive deals
- Personalised campaigns
- High-value product promotions

## Project Files

```
├── README.md
├── Customer_Personality_Analysis.ipynb
├── Customer Personality Analysis Plan.png
└── data/
    └── marketing_campaign.csv
```

## Contact

**Bongani Mathew Miya**

- LinkedIn: [Bongani Mathew Miya](https://www.linkedin.com/in/bongani-mathew-miya-156580228/)
- Email: [miyabongani71@gmail.com](mailto:miyabongani71@gmail.com)
