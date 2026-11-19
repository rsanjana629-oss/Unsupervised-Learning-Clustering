# Unsupervised-Learning-Clustering
Customer segmentation using K-Means clustering on the Mall Customer Segmentation dataset
# Customer Segmentation Using K-Means Clustering

## Week 3 Task – Unsupervised Learning and Clustering Analysis

## Project Overview
This project focuses on customer segmentation using the K-Means clustering algorithm. The Mall Customer Segmentation dataset is used to group customers based on their age, annual income, and spending score.

The goal is to identify different customer groups and understand their purchasing behaviour to help businesses make better marketing and business decisions.

## Objective
- Perform exploratory data analysis (EDA).
- Clean and preprocess the dataset.
- Apply feature scaling.
- Implement K-Means clustering.
- Determine the optimal number of clusters using the Elbow Method.
- Visualize customer clusters.
- Analyze customer segments and derive business insights.

## Dataset
**Dataset:** Mall Customer Segmentation Dataset

**Source:** Kaggle

**Number of Records:** 200 customers

**Features:**
- CustomerID – Unique customer identifier
- Gender – Customer gender
- Age – Customer age
- Annual Income (k$) – Annual income in thousands of dollars
- Spending Score (1-100) – Score assigned based on spending behaviour

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Data acquisition
2. Data loading
3. Exploratory Data Analysis
4. Data cleaning
5. Feature selection
6. Feature scaling using StandardScaler
7. Finding optimal clusters using the Elbow Method
8. Applying K-Means clustering
9. Cluster visualization
10. Cluster analysis
11. Model evaluation

## Algorithm
### K-Means Clustering
K-Means is an unsupervised machine learning algorithm that groups data points into clusters based on similarity.

The algorithm assigns customers to clusters according to the distance between data points and cluster centroids.

**Number of clusters selected:** 5

**Parameters:**
- `n_clusters = 5`
- `init = k-means++`
- `random_state = 42`
- `n_init = 10`

## Results
Five customer segments were identified:

| Cluster | Customer Segment | Characteristics |
|---|---|---|
| 0 | Low Income – Low Spending | Customers with low income and low spending |
| 1 | Young High-Spending Customers | Young customers with moderate income and high spending |
| 2 | High-Income – High-Spending | Customers with high income and high spending |
| 3 | High-Income – Low-Spending | Customers with high income but low spending |
| 4 | Older Moderate-Spending Customers | Older customers with moderate income and spending |

## Model Evaluation
- **Silhouette Score:** 0.4166
- **WCSS:** 168.25
- **Davies-Bouldin Score:** 0.8746

The evaluation indicates reasonably formed clusters with moderate separation between customer groups.

## Business Applications
Customer segmentation can help businesses:
- Create targeted marketing campaigns.
- Offer personalized discounts.
- Identify high-value customers.
- Improve customer retention.
- Develop loyalty programs.
- Understand customer purchasing behaviour.

## Project Files
- `Week_3_Unsupervised_Learning_and_Clustering_Analysis.pdf` – Project report
- `Week_3_Unsupervised_Learning_and_Clustering_Analysis.docx` – Editable report
- `Week_3_Unsupervised_Learning_Clustering.ipynb` – Python notebook
- `Customer_Segmentation_Results.csv` – Customer data with cluster labels
- `Cluster_Analysis_Summary.csv` – Cluster-wise summary

## Conclusion
This project successfully applied K-Means clustering to segment customers based on age, annual income, and spending score. The analysis identified five distinct customer groups and provided useful insights into customer behaviour. These segments can help businesses make informed decisions regarding marketing strategies, customer engagement, and personalized services.

## Author
**Sanjana Rathod**

Artificial Intelligence and Machine Learning Student
