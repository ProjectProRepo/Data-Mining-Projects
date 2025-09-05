# Customer Segmentation Project  

This project demonstrates how to perform **Customer Segmentation** using data mining and clustering techniques. The goal is to group customers based on demographic and spending behavior so businesses can target them more effectively. By applying **unsupervised learning** methods, hidden patterns in customer data are uncovered, leading to actionable marketing insights.  

---

## Project Objectives  
- Explore and analyze customer demographics and spending patterns.  
- Perform data preprocessing (encoding categorical data, scaling numerical features).  
- Visualize relationships between age, income, and spending score.  
- Apply clustering algorithms:  
  - **K-Means Clustering**  
  - (Optional) **Hierarchical Clustering** or **DBSCAN**  
- Evaluate clusters using metrics like Silhouette Score.  
- Profile clusters to derive business insights.  

---

## Dataset  
- **Source:** [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/datasets/shwetabh123/mall-customers)  
- **Alternative Repo Source:** [Mall_Customers.csv](https://raw.githubusercontent.com/ProjectProRepo/Data-Mining-Projects/main/datasets/Mall_Customers.csv)  
- **Columns include:**  
  - `CustomerID` → Unique ID for each customer  
  - `Gender` → Male/Female  
  - `Age` → Age of customer  
  - `Annual Income (k$)` → Annual income in thousand dollars  
  - `Spending Score (1-100)` → Spending score assigned by the mall  

---

## Tech Stack  
- **Programming Language:** Python 3.x  
- **Libraries:**  
  - `pandas`, `numpy` → Data manipulation  
  - `matplotlib`, `seaborn` → Data visualization  
  - `scikit-learn` → Clustering models and evaluation metrics  

---

## Data Mining  
- Age distribution and customer demographics  
- Relationship between income and spending score  
- Gender-based spending patterns  
- Correlation analysis of customer attributes  
- Cluster formation and interpretation  

---

## Clustering Approaches  
1. **K-Means Clustering**  
   - Use the Elbow Method to determine the optimal number of clusters.  
   - Segment customers into distinct groups based on income and spending behavior.  

2. **Hierarchical Clustering (Optional)**  
   - Visualize customer relationships with dendrograms.  

---

## Expected Outcomes  
- Distinct customer groups such as:  
  - **Premium Shoppers** (High income, high spending)  
  - **Budget-Conscious Customers** (Low income, moderate spending)  
  - **High Income but Low Spending** customers  
- Visual insights through 2D and 3D scatter plots of clusters.  
- Actionable strategies for targeted marketing campaigns.  
- Hands-on experience applying clustering for real-world business analysis.  

---

## Resources  
- [Kaggle: Mall Customers Dataset](https://www.kaggle.com/datasets/shwetabh123/mall-customers)  

---
