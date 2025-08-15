# Customer Segmentation Using K-Means Clustering

## Overview
This project applies K-Means clustering to segment mall customers based on their annual income and spending score. Customer segmentation enables businesses to understand their customer base, personalize marketing strategies, and improve overall business performance.
![Workflow](https://github.com/Peter-Opapa/k-means-clustering-project/blob/main/workflow.png)

## Objective
- Identify distinct customer groups in the mall dataset.
- Provide actionable insights for targeted marketing and business decisions.

## Dataset
- **Source:** [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)
- **Columns:**
  - `CustomerID`: Unique identifier for each customer
  - `Gender`: Male/Female
  - `Age`: Age of the customer
  - `Annual Income (k$)`: Annual income in thousands of dollars
  - `Spending Score (1-100)`: Score assigned by the mall based on customer behavior

## Methodology
1. **Data Exploration:**  
	- Summary statistics and visualizations to understand feature distributions.
2. **Preprocessing:**  
	- Selection of relevant features (`Annual Income`, `Spending Score`).
3. **Clustering:**  
	- Elbow method to determine optimal number of clusters.
	- K-Means clustering to segment customers.
4. **Analysis:**  
	- Visualization of clusters and centroids.
	- Summary statistics for each cluster.
	- Business insights and recommendations.

## Results
- Customers are grouped into distinct segments based on income and spending patterns.
- Insights help identify high-value customers, potential targets for promotions, and strategies for customer retention.

## How to Run
1. Clone the repository.
2. Ensure you have Python 3.x and the required libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
3. Open and run the notebook `customer_segmentation_using_k-means.ipynb` step by step.

## Business Impact
- Enables targeted marketing campaigns.
- Improves customer satisfaction and loyalty.
- Supports data-driven decision making.

## References
- [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/clustering.html#k-means)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Kaggle Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)
