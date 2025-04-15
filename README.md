
# 🛍️ Mall Customer Clustering Project

This project explores customer segmentation using unsupervised learning techniques like **K-Means** and **Hierarchical Clustering** on a mall customer dataset.

---

## 📁 Dataset

**Source**: [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

**Features**:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1–100)`

---

## 🔍 Project Highlights

### ✅ Data Exploration & Preprocessing
- Handled missing values (none found)
- Encoded categorical data (`Gender`)
- Standardized features using `StandardScaler`
- Selected relevant features for clustering

### ⚙️ Clustering Algorithms
- **K-Means Clustering**
  - Used Elbow Method & Silhouette Scores to find optimal `k`
  - Best results with **k=5**
- **Hierarchical Clustering**
  - Used Ward linkage & dendrogram visualization
  - Supported 5-cluster structure

### 📊 Evaluation & Results
- Visualized clusters in 2D space
- Calculated silhouette scores
- Interpreted and profiled clusters with business insights

---

## 📦 Files Included

- `clustering_homework.ipynb`: Main Jupyter notebook
- `Mall_Customer_Clustering_Report.docx`: Summary report
- `Mall_Customers.csv`: Dataset (not included here, add manually or download from Kaggle)

---

## 💡 Business Applications

- Identify target groups for marketing strategies
- Improve product recommendations
- Personalize loyalty programs based on customer behavior

---

## 📜 License

This project is for academic use under the MSA 8150 - Machine Learning for Analytics course.

---

## ✍️ Author

Harshal Kamble
