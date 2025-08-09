# PRODIGY_ML_03  
**Customer Segmentation using K-Means Clustering**

## 📌 Overview  
This project implements **K-Means Clustering** to segment customers of a retail store based on:  
- **Annual Income**  
- **Spending Score**  

By grouping customers with similar purchasing behaviors, businesses can design targeted marketing strategies and improve customer satisfaction.

---

## 🎯 Objective  
The primary goal is to identify distinct customer groups and understand their purchasing patterns. This enables:  
- Better product recommendations  
- Personalized marketing campaigns  
- Improved business decision-making

---

## 📂 Dataset  
The dataset used is the **Mall Customers Dataset**, containing the following key features:  
- **CustomerID** – Unique customer identifier  
- **Gender** – Male / Female  
- **Age** – Customer age in years  
- **Annual Income (k$)** – Income of the customer in thousand dollars  
- **Spending Score (1-100)** – Score assigned based on customer behavior and spending nature  

📎 [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

## 🛠️ Technologies Used  
- **Python 3.8+**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning model implementation

---

## 📊 Methodology  
1. **Data Exploration & Cleaning**  
   - Checked for missing values  
   - Basic statistical analysis  
2. **Data Visualization**  
   - Plotted distributions and relationships between variables  
3. **Feature Selection**  
   - Selected **Annual Income** and **Spending Score** as clustering features  
4. **K-Means Clustering**  
   - Used the **Elbow Method** to determine the optimal number of clusters  
   - Implemented K-Means algorithm to group customers  
5. **Result Visualization**  
   - Plotted customer clusters in 2D space

---

## 📷 Visualizations  
- **Elbow Method Graph** – Helps determine the optimal `k` value  
- **Customer Cluster Plot** – Displays distinct groups of customers based on chosen features  

---

## 🚀 Installation & Usage  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/SRIHARI18V/PRODIGY_ML_03.git
cd PRODIGY_ML_03
