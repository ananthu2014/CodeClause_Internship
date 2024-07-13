# Mall Customer Segmentation Using K-Means Clustering

## Project Description

This project demonstrates the use of K-Means clustering to perform customer segmentation on a mall customer dataset. The dataset is synthetic and sourced from Kaggle, containing 200 samples with the following features:

- `CustomerID`: Unique identifier for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

The project includes implementations of the K-Means clustering algorithm from scratch and using the scikit-learn library.  
Additionally, the K-Means++ initialization method was utilized for better clustering results.  
The optimal number of clusters was determined using the elbow method and the silhouette score was found to be approximately 0.4 for k = 4.  
Exploratory data analysis(EDA) was performed on the dataset and insights after clustering are also given.  

## Installation

### Prerequisites

- Python
- scikit-learn
- matplotlib
- seaborn
- Pandas
- Numpy

## References:

1. https://medium.com/@robertb909/k-means-clustering-a64f859a1074
2. https://medium.com/data-and-beyond/customer-segmentation-using-k-means-clustering-with-pyspark-unveiling-insights-for-business-8c729f110fab
3. Kaggle(dataset)  





