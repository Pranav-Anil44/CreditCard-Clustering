# 🧠 Credit Card Customer Segmentation using KMeans Clustering

This project performs **unsupervised clustering** on a credit card customer dataset using **KMeans** and **PCA**, with the goal of segmenting customers based on behavioral patterns. It is intended for educational and portfolio demonstration purposes.

## 📌 Objective

To identify distinct customer segments based on spending patterns and card usage behavior, using clustering techniques. This helps businesses better understand customer profiles and tailor strategies accordingly.

## 📂 Dataset

The dataset (`Credit_card_data.xlsx`) includes anonymized customer information with features like:

- Credit limit
- Monthly spend
- Cash advance behavior
- Purchase types and frequencies
- Tenure and balance
- ...and more

---

## 🧪 Techniques Used

- 📊 **Exploratory Data Analysis**
- 🧹 **Data Preprocessing**
  - Null value handling
  - Outlier detection
  - Feature scaling (`StandardScaler`)
- 📉 **Dimensionality Reduction**
  - Applied **PCA** (Principal Component Analysis) for 2D visualization
- 🔍 **Clustering**
  - Used **KMeans** clustering
  - Optimal number of clusters found using:
    - **Elbow Method**
    - **Silhouette Score** (best score ~0.596)
   
    - 
## 📸 Visualizations

- Elbow Curve to determine optimal `k`
- Cluster scatter plots (after PCA)
- Visual cluster comparison with original scaled features



## 📁 Files Included

| File | Description |
|------|-------------|
| `Credit_card_clustering.ipynb` | Complete Jupyter Notebook |
| `Credit_card_data.xlsx` | Dataset |
| `Clustering1.png`, `clustering.png` | Visualizations of clusters |
| `.ipynb_checkpoints/` | Jupyter autosave checkpoints |


## 🚀 How to Run

1. Clone this repository:git clone https://github.com/Pranav-Anil44/CreditCard-Clustering.git
2. Install requirements (mostly standard libraries):

pip install pandas matplotlib seaborn scikit-learn openpyxl
jupyter notebook Credit_card_clustering.ipynb

This project showcases practical application of unsupervised learning on real-world-like data. It demonstrates:

Feature engineering
Choosing the right number of clusters
Visualizing high-dimensional clustering in 2D
Using silhouette score to evaluate clustering performance

📚 Acknowledgement
Dataset adapted from public sources for learning purposes.

📧 Contact
Pranav A Kumar
Aspiring Data Scientist
🔗 https://www.linkedin.com/in/pranav-a-kumar-2a39b4358/
📂 https://github.com/Pranav-Anil44
