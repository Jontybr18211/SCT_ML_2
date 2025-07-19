# 🧠 Customer Segmentation using K-Means Clustering

This project implements **K-Means clustering** to group retail customers based on their **age**, **annual income**, and **spending score**, aiming to identify meaningful customer segments for targeted marketing.

---

## 📌 Problem Statement

Build an unsupervised machine learning model using **K-Means Clustering** to segment customers of a retail store based on their purchase history and demographics.

---

## 📊 Dataset

- Source: [Kaggle - Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python?select=Mall_Customers.csv)
- Features:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🛠️ Technologies & Libraries Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Plotly (for 3D visualizations)

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for null values and data consistency
- Dropped unnecessary features like `CustomerID`
- Visualized data using 3D scatter plots (Age vs Income vs Spending Score) with gender coloring

---

## 📈 Clustering Process

1. **Feature Selection**: Selected `Age`, `Annual Income`, and `Spending Score` for clustering.
2. **Elbow Method**: Used WCSS (Within-Cluster Sum of Squares) to find the optimal number of clusters.
3. **K-Means Clustering**: Applied clustering and visualized the customer segments in 2D and 3D.
4. **Visualization**: Used Plotly for interactive 3D scatter plots to distinguish clusters effectively.

---

## 📌 Results

- Customers were grouped into distinct clusters based on their purchasing behavior.
- 3D interactive plots helped visualize the segmentation clearly by gender and income-spending-age dimensions.

---

## 📁 Project Structure

```
Customer_Segmentation.ipynb   # Jupyter Notebook with full analysis and implementation
README.md                     # Project overview and documentation
```

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
   cd customer-segmentation
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Customer_Segmentation.ipynb
   ```

---

## ✅ Future Improvements

- Add demographic and behavioral features like region, frequency of purchases
- Try other clustering algorithms (DBSCAN, Hierarchical)
- Deploy clustering results via a simple web dashboard

---

## 📬 Contact

For feedback or collaboration, feel free to reach out at: **your.email@example.com**
