# CustomerSegmentationinE-commerce_202401100300269
# 🛒 Customer Segmentation in E-commerce

This project applies machine learning techniques to identify distinct customer segments based on purchasing and browsing behavior. It uses **K-Means Clustering** and **PCA (Principal Component Analysis)** to reveal hidden patterns in customer data and visualize them clearly.

---

## 📁 File Upload (Google Colab)
This notebook is built to run in **Google Colab** and uses `files.upload()` to allow CSV file input directly from your local system.

---

## 🧠 Problem Statement

E-commerce businesses often struggle to understand diverse customer behavior. By clustering customers based on their activity, we can:
- Optimize marketing strategies
- Personalize recommendations
- Improve customer retention

---

## 🔬 Methodology

1. **Upload Data:** Users upload a `.csv` file containing customer-related information.
2. **Preprocessing:** Handle missing values, filter numeric data, and apply scaling.
3. **Elbow Method:** Determine the optimal number of clusters using WCSS.
4. **Clustering:** Apply KMeans clustering on the scaled dataset.
5. **PCA:** Reduce feature dimensions for visualization.
6. **Visualization:** Use Seaborn to plot distinct clusters in 2D space.

---

## 🧾 Dependencies

- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`
- `google.colab`

Install using pip (if running locally):
```bash
pip install pandas matplotlib seaborn scikit-learn
