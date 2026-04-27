# customer-segmentation-kmeans-pca-clustering

# Customer Segmentation using Clustering & Dimensionality Reduction

##  Overview
This project focuses on customer segmentation using unsupervised machine learning techniques. It applies clustering algorithms and dimensionality reduction methods to identify distinct customer groups based on their behavior and demographic features.

The dataset includes:
- Age
- Annual Income
- Spending Score

##  Features
- Data preprocessing and feature scaling
- Optimal cluster selection using the Elbow Method
- Customer segmentation using K-Means Clustering
- Dimensionality reduction using PCA
- Visualization of customer clusters

##  Concepts Used
- K-Means Clustering
- Elbow Method
- Principal Component Analysis (PCA)
- Feature Scaling (Standardization)

##  Workflow
1. Load dataset
2. Select relevant features
3. Scale the data using StandardScaler
4. Determine optimal number of clusters using Elbow Method
5. Apply K-Means clustering
6. Reduce dimensions using PCA
7. Visualize clusters in 2D space

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

##  Project Structure
├── Mall_Customers.csv
├── clustering.py
├── README.md

##  Results
- Customers are segmented into distinct clusters based on purchasing behavior.
- PCA helps visualize high-dimensional data in a 2D space.
- Clear separation of customer groups enables better analysis and insights.

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation-kmeans-pca-clustering.git

Navigate to the project folder:

cd customer-segmentation-kmeans-pca-clustering

Install dependencies:

pip install pandas matplotlib scikit-learn

Run the script:

python clustering.py
