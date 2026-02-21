# Customer Segmentation Using Unsupervised Learning

An unsupervised machine learning project that segments retail customers based on income and spending behavior.  
Multiple clustering algorithms were implemented and compared to identify meaningful customer groups and detect anomalies.

---

## Project Overview

Customer segmentation helps businesses understand purchasing behavior and design targeted marketing strategies.

In this project:

- Performed clustering on 200 retail customers
- Analyzed income and spending score features
- Compared multiple unsupervised learning algorithms
- Identified actionable customer segments
- Detected anomalous customer profiles

The goal was not only clustering, but translating results into practical business insights.

---

## Dataset

- Total Customers: 200
- Key Features Used:
  - Annual Income
  - Spending Score

These features were selected to represent customer purchasing power and behavior patterns.

---

## Exploratory Data Analysis (EDA)

- Analyzed income and spending distributions  
- Visualized customer density and patterns  
- Identified potential natural groupings  
- Observed behavioral trends across income levels  

EDA helped guide cluster selection and interpretation.

---

## Clustering Algorithms Implemented

### K-Means Clustering
- Optimal number of clusters: **k = 5**
- Selected using **Silhouette Score**
- Produced well-separated customer segments

### DBSCAN
- Density-based clustering
- Identified **8 anomalous customers (outliers)**
- Effective for detecting irregular customer behavior

### Hierarchical Clustering
- Used dendrogram analysis
- Compared cluster consistency with K-Means

---

## Evaluation Metric

- **Silhouette Score** was used to evaluate cluster quality and separation.

---

## Key Results

- Identified **5 distinct customer segments**, including:
  - High Income – High Spending (Premium Customers)
  - High Income – Low Spending
  - Low Income – High Spending
  - Budget Customers
  - Moderate/Regular Customers

- DBSCAN detected **8 anomalous customers**, representing unusual purchasing behavior.

- Clustering results were translated into actionable business segments:
  - **Premium**
  - **Regular**
  - **Budget**

---

## Business Insights

- Premium customers can be targeted with exclusive offers.
- Budget customers respond better to discounts and promotions.
- Anomalous customers may indicate unusual buying patterns or special cases.
- Segmentation enables personalized marketing and improved retention strategies.

---

## Project Structure
```
customer-segmentation/
│
├── customer_segmentation.ipynb
├── requirements.txt
└── README.md

```

---

## Installation & Usage

### Clone Repository
git clone https://github.com/psawner/segmentation-analysis

### Install Dependencies
pip install -r requirements.txt

### Run Notebook

Open: 
- customer_segmentation.ipynb



and execute all cells.

---

## Requirements

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## Key Concepts Demonstrated

- Unsupervised learning  
- Cluster evaluation using Silhouette Score  
- Density-based anomaly detection  
- Business-driven interpretation of clustering results  
- Translating ML output into strategic insights  

---

