# Task-12-KMeans-Customer-Segmentation
# KMeans Customer Segmentation – Task 12

## Overview
This project is part of the AI & ML Internship Task 12 and focuses on customer segmentation using the KMeans clustering algorithm. The objective is to group customers based on their purchasing behavior using unsupervised learning techniques.

## Dataset
Wholesale Customers Dataset

The dataset contains annual spending data of customers across different product categories:
- Fresh
- Milk
- Grocery
- Frozen
- Detergents_Paper
- Delicassen

The columns Channel and Region were removed as they do not contribute effectively to distance-based clustering.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Methodology
1. Loaded and explored the dataset
2. Removed non-useful categorical columns
3. Applied StandardScaler for feature scaling
4. Used the Elbow Method to determine the optimal number of clusters
5. Trained the KMeans clustering model
6. Assigned cluster labels to customers
7. Visualized clusters using scatter plots
8. Interpreted customer segments

## Results
- Optimal number of clusters identified using the Elbow Method
- Customers grouped into meaningful segments based on spending patterns

### Customer Segments
- Retail Customers: High spending on grocery and milk products
- Medium Businesses: Balanced spending across categories
- Small Buyers: Low overall purchase volume

## Deliverables
- Elbow method plot
- Cluster visualization
- Segmented dataset CSV file

## How to Run
1. Clone the repository
   git clone <repository-link>

2. Install dependencies
   pip install pandas numpy scikit-learn matplotlib seaborn

3. Run the Python script or Jupyter Notebook

## Final Outcome
This project demonstrates the application of KMeans clustering for business-oriented customer segmentation and unsupervised learning.


