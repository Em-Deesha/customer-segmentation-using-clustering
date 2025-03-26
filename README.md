# Customer Segmentation using Clustering

## 📌 Project Overview
This project applies **K-Means** and **Hierarchical Clustering** to segment customers based on **Age, Income, and Spending Score**. The goal is to help businesses better understand customer groups.

## 📂 Dataset Information
The dataset includes:
- **Customer ID**: Unique identifier for each customer (Not used in clustering)
- **Gender**: Male or Female
- **Age**: Customer's age
- **Annual Income**: Customer's yearly income (in thousands)
- **Spending Score**: Customer's spending behavior (1-100)

## ⚙️ Steps in the Project
1. **Exploratory Data Analysis (EDA)** 
   - Visualized Age, Income, and Spending Score distributions.
2. **Data Preprocessing** 
   - Removed unnecessary columns (Customer ID).
   - Encoded Gender.
   - Scaled data for better clustering performance.
3. **Clustering Methods**
   - Applied **K-Means Clustering** to find optimal customer segments.
   - Applied **Hierarchical Clustering** and compared results.
4. **Visualization & Insights**
   - Created scatter plots to visualize clusters.
   - Interpreted customer behavior based on spending patterns.

## 📊 Results & Insights
- Customers were successfully segmented into **five distinct groups**.
- High-income, high-spending customers formed a unique segment.
- Low-income, low-spending customers formed another segment.
- Age also influenced spending patterns, as younger customers had higher spending scores.

## 🚀 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (K-Means, Hierarchical Clustering)

## 🛠 How to Run
1. Install dependencies
2. Run the model
