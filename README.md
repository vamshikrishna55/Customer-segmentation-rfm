# 🧠 Advanced Customer Segmentation Using Machine Learning & Power BI

## 📌 Project Overview
This project focuses on identifying and understanding different customer segments for a retail business using **RFM analysis (Recency, Frequency, Monetary)** and **K-Means clustering**, followed by an interactive **Power BI dashboard** to visualize and analyze customer behavior.

---

## 🎯 Objectives
- Segment customers based on purchasing behavior.
- Identify high-value customers, potential loyalists, and churn risks.
- Provide actionable business insights through visual analytics.

---

## 🛠️ Tools & Technologies
- **Python** – Data cleaning, RFM feature engineering, clustering
- **scikit-learn** – K-Means clustering algorithm
- **Pandas, NumPy, Matplotlib, Seaborn** – Data manipulation and visualization
- **Power BI** – Interactive dashboard and storytelling
- **Google Colab** – Cloud-based development

---

## 🔍 Methodology

### 1. Data Preprocessing
- Loaded historical retail transaction data.
- Removed missing values, negative quantities, and invalid prices.
- Parsed datetime for transaction timing.

### 2. RFM Feature Engineering
- **Recency**: Days since the last purchase.
- **Frequency**: Total number of transactions per customer.
- **Monetary**: Total amount spent per customer.

### 3. Clustering
- Normalized RFM features using `StandardScaler`.
- Determined optimal number of clusters using the **Elbow Method**.
- Applied **K-Means clustering** to group customers into segments.

### 4. Segment Naming
Clusters were labeled as:
- **Loyal Customers**
- **Potential Loyalists**
- **New Customers**
- **Churned Customers**

### 5. Visualization with Power BI
- Designed a one-page interactive dashboard with:
  - KPIs (Customer count, total revenue, average CLV)
  - Pie chart of customer segments
  - Revenue by segment bar chart
  - RFM comparison chart
  - CLV scatter plot
  - Slicers for Segment, Recency, Monetary, CLV

---

## 📈 Key Insights
- **Loyal customers** make up the majority of revenue despite being a smaller customer base.
- **Churned customers** have not purchased recently but had high historical spending.
- **New customers** need engagement strategies to become repeat buyers.
- **CLV analysis** helps prioritize marketing efforts on high-value clusters.

---

## 📁 Files Included
- `Advanced Customer Segmentation.pbix` – Power BI dashboard
- `Enhanced_RFM_Segmentation.csv` – Final dataset used in dashboard
- `rfm_analysis.ipynb` – Python notebook with data processing and clustering
- Dashboard screenshots
- This `README.md`

---

## 🚀 Future Enhancements
- Use DBSCAN or hierarchical clustering for comparison
- Automate pipeline using Apache Airflow
- Deploy as a web app with Streamlit or Flask

---

## 👤 Author
**Vamshi Krishna Reddy Attla**  
- 📧 vamshikrishna.reddy555@gmail.com  
- 🌐 [LinkedIn](https://www.linkedin.com/in/vamshikrishna11/)

---

## 💬 Feedback
If you found this useful or have suggestions, feel free to reach out or fork this repo!
