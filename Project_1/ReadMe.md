# Mall Customer Segmentation Using K-Means Clustering

## Project Description

This project demonstrates the use of K-Means clustering to perform customer segmentation on a mall customer dataset. The dataset is synthetic and sourced from Kaggle, containing 200 samples with the following features:

- `CustomerID`: Unique identifier for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

The project includes implementations of the K-Means clustering algorithm from scratch and using the scikit-learn library. Additionally, the K-Means++ initialization method was utilized for better clustering results. The optimal number of clusters was determined using the elbow method and the silhouette score.

## Installation

### Prerequisites

- Python 3.6 or later
- Apache Spark 3.0 or later
- Java 8 or later
- scikit-learn
- matplotlib
- seaborn

### Installation Steps

1. **Install PySpark**: You can install PySpark using pip.

    ```sh
    pip install pyspark
    ```

2. **Install scikit-learn, matplotlib, and seaborn**:

    ```sh
    pip install scikit-learn matplotlib seaborn
    ```

3. **Verify Installation**: Ensure that PySpark is installed correctly by starting a Python session and importing PySpark.

    ```python
    import pyspark
    print(pyspark.__version__)
    ```

## Usage

### Initialize a Spark Session

To use PySpark, you need to initialize a Spark session. Here is how you can do it:

```python
from pyspark.sql import SparkSession

# Initialize Spark session
spark = SparkSession.builder \
    .appName("MallCustomerSegmentation") \
    .getOrCreate()

# Print Spark session details
print(spark)

