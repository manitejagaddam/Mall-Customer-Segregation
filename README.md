# Mall Customer Segmentation Application

This project demonstrates customer segmentation using the **K-Means clustering algorithm**. The dataset contains information about customers' demographics and spending habits, and the application categorizes customers into distinct segments. The analysis includes data visualization, feature scaling, and clustering.

---

## Features

- Data pre-processing and encoding of categorical variables.
- Visualization of customer demographics and spending patterns using Matplotlib, Seaborn, and Plotly.
- Clustering customers into 5 and 6 segments using the K-Means algorithm.
- Interactive 3D visualizations for understanding customer segmentation.

---

## Dataset Details

The dataset consists of the following columns:
- **Gender**: Male or Female.
- **Age**: Customer's age.
- **Annual Income (k$)**: Customer's annual income in thousands of dollars.
- **Spending Score (1-100)**: A score assigned based on customer spending behavior.

---

## Data Processing Steps

- Dropped unnecessary columns such as `CustomerID`.
- Converted the `Gender` column into numeric format using one-hot encoding.
- Visualized the dataset using scatter plots and pie charts for an overview of customer demographics and spending habits.
- Standardized the data to ensure clustering accuracy using `StandardScaler`.

---

## Clustering

- **Algorithm**: K-Means Clustering
- **Metrics**:
  - WCSS (Within-Cluster Sum of Squares) calculated for optimal cluster determination.
- **Clusters**:
  - Segmented customers into 5 and 6 groups for analysis.

---

## Visualization

- **Matplotlib & Seaborn**:
  - Scatter plots for annual income vs. spending score.
  - Pair plots to observe relationships between features.

---

## Results

- **Optimal Clusters**: Using the elbow method, 6 clusters were identified as optimal for segmentation.
- **Segmentation Visualized**:
  - Grouped customers into clusters based on their demographic and spending data.
 

---
## Installation and Usage

 1. Clone the Repository

```bash
git clone https://github.com/manitejagaddam/mall-customer-segmentation.git
cd mall-customer-segmentation
```

 2. Install Dependencies

```bash
pip install -r requirements.txt
```




