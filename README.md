
# 🛍️ RFM Customer Segmentation using KMeans Clustering

## 📌Project Description

This project performs customer segmentation using RFM analysis (Recency, Frequency, Monetary) on retail transaction data and applies KMeans clustering to group customers based on their purchasing behavior. The results are visualized in 2D and 3D plots.

## ✅Features

✔️ Upload Excel retail data directly in Google Colab 
✔️ Clean and preprocess data (remove invalid rows, handle missing values) 
✔️ Compute Total Price, and extract RFM metrics
✔️ Normalize the data for clustering 
✔️ Find the optimal number of clusters using the Elbow Method 
✔️ Segment customers using KMeans Clustering 
✔️ Visualize clusters in:

2D Plot: Recency vs Monetary

3D Plot: Recency, Frequency, and Monetary 
✔️ Display sample clustered customer data

# Package and its Purpose

1.pandas	Data manipulation and analysis
2.numpy	Numerical operations
3.matplotlib	Plotting and data visualization
4.seaborn	Statistical data visualization
scikit-learn	Clustering using KMeans, data scaling
5.openpyxl	Reading Excel files (.xlsx)
6.mpl_toolkits.mplot3d	3D plotting for clustering visualization
7.google.colab.files	Uploading files in Google Colab

# 📊 Analysis Workflow

1. Data Cleaning

Strip column names, remove missing values

Filter rows where Quantity and Price > 0

2. Feature Engineering

Compute TotalPrice = Quantity × Price

Convert InvoiceDate to datetime

3. RFM Metrics

Recency: Days since last purchase

Frequency: Number of unique invoices

Monetary: Total amount spent

4. Normalization

Scale RFM features using StandardScaler

5. KMeans Clustering

Use Elbow Method to find optimal clusters (k)

Apply KMeans with selected k (e.g., 4)
6. Visualization

2D plot: Recency vs Monetary

3D plot: Recency, Frequency, Monetary with cluster coloring

## Screenshots

![customer segmentation](https://github.com/user-attachments/assets/e057611b-dffb-49a7-a0c2-8167472ab88b)

![customer segmentation (2)](https://github.com/user-attachments/assets/5d41f358-afb7-45b4-b443-62745d55013b)

![customer segmentation (3)](https://github.com/user-attachments/assets/91867567-2430-475d-8d6d-e16e54344374)

## Demo

https://github.com/user-attachments/assets/558b802c-ce90-41cd-b162-fc45534f1c05

