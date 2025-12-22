# Project overview
Goal: Create a K-Means clustering model to group retail store customers based on their purchase history.

Motivation: Understand customer segments to support targeted marketing, personalized offers, and better business decisions.
​

# Dataset
clustered_customers.csv: Output file containing customer IDs with their assigned cluster labels.
​
task2.ipynb: Jupyter notebook containing data preprocessing, clustering, and analysis.
​
Any raw customer data file used as input (e.g., customers.csv, transactions.csv) depending on your task.
​

# Project structure
task2.ipynb: Main notebook with preprocessing, K-Means clustering, and visualization.
​
clustered_customers.csv: Final customer segments with cluster labels.
​
Additional data files used for clustering (update names here to match your repo).
​

# Approach
Load the customer data into a pandas DataFrame.

Explore the data (shape, summary statistics, missing values, distributions).
​
Select or engineer features from purchase history, such as total spending, purchase frequency, and recency (if available).
​
Preprocess: handle missing values, treat outliers, and scale numerical features using StandardScaler or MinMaxScaler.
​
Choose the number of clusters using the Elbow method and optionally Silhouette score.
​
Train a K-Means model with scikit-learn using the selected number of clusters.
​
Assign each customer to a cluster and analyze segments (e.g., high-value loyal customers, infrequent low spenders)​

Save the final clustered dataset with labels to clustered_customers.csv.
​

# How to run
Clone the repository:

bash
git clone https://github.com/shikha-03/SCT_ML_02.git
cd SCT_ML_02
Install dependencies (example):
​
bash
pip install -r requirements.txt
Or manually:
​
bash
pip install numpy pandas scikit-learn matplotlib seaborn
Open task2.ipynb in Jupyter/Colab and run all cells to reproduce preprocessing, clustering, and analysis.
​

# Technologies used
Python.
​
NumPy, pandas for data manipulation.
​
Matplotlib, Seaborn for visualization.
​
Scikit-learn for K-Means clustering and evaluation metrics.
​

# Results
Grouped customers into meaningful segments using K-Means clustering based on purchase history.
​
Exported a labeled dataset (clustered_customers.csv) that can be used for marketing and business strategy.
​

# Future improvements
Experiment with other clustering algorithms (Hierarchical Clustering, DBSCAN) for comparison.
​

Add more behavioral features (e.g., product categories, average basket size).
​

Connect this segmentation with a dashboard or recommendation system for the retail store.
