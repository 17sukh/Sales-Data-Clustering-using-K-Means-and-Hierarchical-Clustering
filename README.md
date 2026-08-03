# Sales Data Clustering using K-Means and Hierarchical Clustering

## 📌 Project Overview

This project applies **K-Means Clustering** and **Hierarchical Clustering** techniques to group customers or sales records based on similar characteristics from the **sales_data_sample.csv** dataset.

The **Elbow Method** is used to determine the optimal number of clusters before applying the clustering algorithms. The project also visualizes the resulting clusters to understand patterns within the sales data.

---

## 🎯 Objectives

- Load and preprocess the sales dataset
- Select relevant numerical features
- Normalize the data (if required)
- Determine the optimal number of clusters using the Elbow Method
- Implement K-Means Clustering
- Implement Hierarchical Clustering
- Visualize and analyze the resulting clusters

---

## 📂 Dataset

**Dataset:** Sample Sales Data

https://www.kaggle.com/datasets/kyanyoga/sample-sales-data

The dataset contains sales-related information such as:

- ORDERNUMBER
- QUANTITYORDERED
- PRICEEACH
- SALES
- ORDERDATE
- STATUS
- PRODUCTLINE
- CUSTOMERNAME
- COUNTRY
- DEALSIZE
- YEAR_ID
- MONTH_ID
- TERRITORY

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## 📁 Project Structure

```
Sales-Data-Clustering/
│
├── 6.ipynb
├── README.md
└──sales_data_sample.csv
```

---

## ⚙️ Project Workflow

### 1. Data Preprocessing

- Loaded the dataset
- Checked dataset information
- Removed missing values (if any)
- Selected relevant numerical features
- Encoded categorical variables (if required)
- Prepared the data for clustering

---

### 2. Feature Scaling

- Applied **StandardScaler** to normalize the numerical features
- Improved clustering performance by ensuring equal feature importance

---

### 3. Determine Optimal Number of Clusters

Used the **Elbow Method** to calculate the Within-Cluster Sum of Squares (WCSS) for different values of **K**.

The optimal number of clusters is selected at the "elbow point," where adding more clusters provides diminishing improvements.

---

### 4. K-Means Clustering

Implemented the **K-Means** algorithm to group similar sales records into clusters based on feature similarity.

---

### 5. Hierarchical Clustering

Applied **Agglomerative Hierarchical Clustering** to create a hierarchy of clusters.

A **Dendrogram** was generated to visualize the clustering hierarchy and determine suitable cluster groups.

---

## 📊 Model Evaluation

The clustering results were evaluated through:

- Elbow Method (WCSS)
- Cluster Visualization
- Dendrogram Analysis
- Cluster Distribution

---

## 📈 Results

| Clustering Technique | Purpose |
|----------------------|---------|
| Elbow Method | Determines the optimal number of clusters |
| K-Means Clustering | Groups similar sales records efficiently |
| Hierarchical Clustering | Reveals hierarchical relationships between clusters |

The Elbow Method helps identify the appropriate number of clusters, while K-Means and Hierarchical Clustering provide different perspectives on grouping the sales data.

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/Sales-Data-Clustering.git
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
6.ipynb
```

Run all cells sequentially.

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
scipy
jupyter
```

---

## 📚 Machine Learning Pipeline

```
Dataset
    │
    ▼
Data Preprocessing
    │
    ▼
Feature Selection
    │
    ▼
Feature Scaling
    │
    ▼
Elbow Method
    │
    ▼
Optimal Number of Clusters
    │
    ├──────────────┐
    ▼              ▼
K-Means      Hierarchical
Clustering    Clustering
    │              │
    └──────┬───────┘
           ▼
Cluster Visualization
```

---

## 📌 Learning Outcomes

- Unsupervised Learning
- Data Preprocessing
- Feature Scaling
- K-Means Clustering
- Hierarchical Clustering
- Agglomerative Clustering
- Elbow Method
- Dendrogram Analysis
- Cluster Visualization
- Customer and Sales Segmentation

---

## 👩‍💻 Author

**Sukhada Tamboli**

Interested in:

- Data Science
- Machine Learning
- Deep Learning
- Artificial Intelligence
- Python Development

---
