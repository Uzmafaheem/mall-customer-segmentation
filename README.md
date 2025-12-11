# 🛍️ Customer Segmentation with Clustering
## Project Overview

This project applies unsupervised machine learning to segment mall customers into distinct groups based on their demographics and spending habits. By identifying patterns in income, spending score, and engineered features, this analysis helps marketing teams design targeted campaigns, improve customer engagement, and optimize business strategies.

## Project Objective

Segment customers using clustering techniques (K-Means).

Understand spending behavior across gender, age, and income.

Identify actionable customer groups for marketing and business decisions.

## Dataset

The dataset used is Mall_Customers.csv, which contains the following attributes:

- CustomerID – Unique ID for each customer

- Gender – Male/Female

- Age – Age of the customer

- Annual Income (k$) – Annual income in thousands

- Spending Score (1–100) – Customer spending score

## Key Steps
- Performed an in-depth Exploratory Data Analysis (EDA):
Used 2D and 3D visualizations to explore the relationships between gender, income, age, spending score, and engineered features. These visual insights helped frame how customers differ across various dimensions.

- Built multiple segmentation models:

     - Income-based segmentation

     - Age-based segmentation

     - Engineered feature segmentation using spending efficiency
This showed that customer segmentation is not a one-size-fits-all process—each perspective reveals different patterns and actionable insights.

- Determined optimal clusters using the Elbow Method:
Used distortion/inertia plots to select the most suitable value of k for each model in a systematic, data-driven way.

- Applied Hierarchical Clustering:
Constructed a dendrogram to visualize natural grouping tendencies in the data and validate the chosen number of clusters.

- Created quantitative customer personas:
Each cluster was transformed into a meaningful, data-backed profile—helping marketing teams design precise, targeted campaigns.

## Cluster Visualization

3D Cluster Plot
| Cluster | Income Level | Spending Score | Customer Profile             | Business Interpretation                                                    |
| ------- | ------------ | -------------- | ---------------------------- | -------------------------------------------------------------------------- |
| **0**   | High         | High           | Premium Shoppers             | High-value segment; target for luxury products and exclusive offers.       |
| **1**   | High         | Low            | High-Income Minimal Shoppers | Under-engaged; target for personalized outreach.                           |
| **2**   | Low          | High           | Enthusiastic Budget Shoppers | Spend more despite lower income; ideal for discounts and loyalty programs. |
| **3**   | Low          | Low            | Low-Engagement Customers     | Limited spending; focus on broad promotions.                               |
| **4**   | Medium       | Medium         | Average Shoppers             | Moderate engagement; responsive to seasonal campaigns.                     |

Insight: Clusters are clearly separated based on spending and income patterns, confirming that segmentation is effective.

## Insights

- Gender alone is not a strong determinant of spending behavior.

- Spending efficiency is a valuable feature for identifying high-potential customers.

- K-Means clustering effectively segments customers into actionable groups.

- Marketing strategies can be tailored to each cluster to improve engagement and revenue.

## Technologies Used

Python 3

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (K-Means clustering)

## Future Improvements

- Incorporate additional features like purchase frequency, product categories, or visit history.

- Test advanced clustering algorithms DBSCAN.

## Project Impact

This project provides business-ready insights to:

- Identify high-value customers.

- Personalize marketing campaigns.

- Optimize promotional strategies.

- Increase customer retention and lifetime value.

## 🛠 How to Run the Project
- Download
- Open on google colab or Jupyter Notebook
- Run all

## 👤 Author
Faheemunnisa Syeda Machine Learning & Applied Math Specialist

- 📧 syedafaheem7@gmail.com
- 🔗 GitHub: [https://github.com/syedafaheem7/]
- 🔗 linkedln: [https://www.linkedin.com/in/faheem-unnisa-s-6270888b/]
