**Customer Segmentation using K-Means Clustering**

This project uses K-Means Clustering to segment retail customers based on their purchasing behavior. It enables businesses to better understand their customer base and develop targeted marketing strategies.

**Dataset**

**Source:** Kaggle - Customer Segmentation Tutorial

**File:** Mall_Customers.csv

**Attributes**:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1-100)

**How It Works**

**Data Preprocessing:**

Load and clean dataset

Select relevant features (Annual Income, Spending Score)

Normalize/scale features (optional)

**Apply K-Means Clustering:**

Determine optimal number of clusters using Elbow Method

Train K-Means model

Predict customer groups

**Visualization:**

Scatter plot of customer clusters

**Evaluation**

**Elbow Method:** Used to select optimal k.

**Silhouette Score (optional):** For cluster quality.

**References**

 **Kaggle:** https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
 
 **Scikit-learn** https://scikit-learn.org/stable/modules/clustering.html#k-means
