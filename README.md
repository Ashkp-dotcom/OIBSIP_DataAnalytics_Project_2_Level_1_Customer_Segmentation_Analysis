# 🛍️ Customer Segmentation Using K-Means  

## 📌 Project Overview  
This project applies **K-Means clustering** to segment customers of a retail business into meaningful groups based on their purchasing behavior, demographics, and engagement patterns. The goal is to help businesses design targeted marketing strategies, improve personalization, and enhance customer retention.  

---

## 🔧 Steps Performed  
1. **Data Preprocessing**  
   - Handled missing values  
   - Removed/treated invalid entries (e.g., negative values)  
   - Feature engineering (e.g., Age, Customer_Days, MntTotal, etc.)  
   - Scaled numerical features for clustering  

2. **Clustering**  
   - Applied **K-Means clustering**  
   - Determined optimal `k` using **Elbow Method** and **Silhouette Score**  
   - Cluster centroids were analyzed to interpret group behaviors  

3. **Customer Segmentation Summary**  
   Based on the clustering, five customer segments were identified:  

   - **🟢 Cluster 0 – Loyal Premium Shoppers**  
     - High income, frequent purchases across categories  
     - Strong response to past campaigns  
     - Ideal for loyalty programs and premium offers  

   - **🟡 Cluster 1 – Budget-Conscious Families**  
     - Low income, small purchases mostly in essentials  
     - Rarely respond to campaigns  
     - Best reached through discounts & value-based promotions  

   - **🔵 Cluster 2 – Balanced Wine Enthusiasts**  
     - High income, heavy spenders on wine & meat products  
     - Moderate campaign response  
     - Perfect for premium wine/meat campaigns  

   - **🟣 Cluster 3 – Mature Moderate Spenders**  
     - Older age group, moderate purchases  
     - Limited campaign engagement  
     - Potential target for subscription or membership models  

   - **🔴 Cluster 4 – Elite Top Spenders**  
     - Highest income & spending across all categories  
     - Strong engagement with campaigns  
     - VIP customers: prioritize with exclusive offers & white-glove service  

---

## 📊 Key Insights  
- The **retail customer base is highly diverse**, ranging from budget-focused families to elite luxury shoppers.  
- **Targeted marketing** can significantly improve ROI compared to blanket campaigns.  
- **Cluster 4 (Elite Top Spenders)** and **Cluster 0 (Loyal Premium Shoppers)** should be prioritized for retention, while **Cluster 1 (Budget-Conscious Families)** could benefit from promotional offers.  

---

## 🛠️ Tech Stack  
- **Python** 🐍  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- Clustering Algorithm: **K-Means**  

---

## 👤 Author  
Ashish Kumar Paswan  
Oasis Infobyte Internship(Data Science Domain)


# Run the notebook
jupyter notebook Customer_Segmentation.ipynb  
