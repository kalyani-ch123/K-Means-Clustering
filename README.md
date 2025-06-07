# 🧠 K-Means Clustering on Mall Customer Data

This project applies **K-Means clustering**, an unsupervised machine learning technique, to segment customers based on their demographics and spending behavior. 
Using the **Mall Customer Segmentation dataset**, we explore patterns and groupings that are not visible through traditional analysis. 
PCA is used to visually decode clusters in 2D space, and metrics like the Elbow Method and Silhouette Score help identify the optimal number of clusters.

## 🔍 Objective

- Cluster customers into distinct groups using K-Means.
- Visualize clusters using PCA.
- Determine the optimal number of clusters using the Elbow Method.
- Evaluate clustering quality with Silhouette Score.


## 🛠️ Tools Used

- **Python**  
- **Pandas, NumPy** – Data handling  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn** – Clustering & Evaluation  
- **PCA** – Dimensionality reduction for 2D plotting


## 📊 Steps Followed

1. **Data Loading & Cleaning**: Removed irrelevant columns, encoded categorical values.
2. **Feature Scaling**: Standardized features for better K-Means performance.
3. **PCA Visualization**: Converted data to 2D for intuitive visual clustering.
4. **K-Means Clustering**: Clustered data into `K` groups (optimal `K=5` found).
5. **Elbow Method**: Plotted WCSS to find optimal number of clusters.
6. **Silhouette Score**: Evaluated how well-separated the clusters are.
7. **Cluster Plotting**: Color-coded visualization using PCA components.


## 📁 Files in This Repo

- `kmeans_customer_segmentation.ipynb` or `.py`: Main code file
- `Mall_Customers.csv`: Dataset used (if allowed)
- `README.md`: This file
- `output_images/`: (Optional) Contains plots like Elbow curve and cluster scatterplots


## 📌 Learnings

- Hands-on experience with **unsupervised learning**.
- Use of **PCA** for visual simplification.
- Techniques to **validate cluster quality** without ground truth.
- Real-world application of customer segmentation for marketing.


## 🔗 Dataset Source

[Customer Segmentation Dataset – Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
