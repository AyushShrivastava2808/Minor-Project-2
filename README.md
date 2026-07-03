🛒 Customer Segmentation using K-Means
📌 Project Overview
This project demonstrates the application of unsupervised machine learning for customer segmentation using the Mall Customers dataset. The aim is to group customers into distinct clusters based on their Age, Annual Income, and Spending Score, enabling businesses to design personalized and targeted marketing strategies.

🎯 Objectives
Segment customers into meaningful groups.

Analyze spending behavior and income distribution.

Provide actionable insights for business decision-making.

📂 Dataset
Source: Mall Customers Dataset – Kaggle (kaggle.com in Bing)

Size: 200 entries, 5 features

Features:

CustomerID – Unique identifier

Gender – Male/Female

Age – Customer age

Annual Income (k$) – Annual income in thousands

Spending Score (1–100) – Score assigned based on spending habits

⚙️ Data Preprocessing
Checked for missing values → None found.

Removed duplicates → None found.

Applied Label Encoding to Gender.

Scaled numerical features using StandardScaler.

Conducted Exploratory Data Analysis (EDA):

Distribution plots for Age, Income, Spending Score.

Correlation heatmap.

Pairplots for feature relationships.

🤖 Model Development
Algorithm Used: K-Means Clustering

Steps:

Applied Elbow Method to determine optimal clusters.

Selected 5 clusters based on WCSS curve.

Evaluated clustering quality using Silhouette Score.

📊 Results
Silhouette Score: 0.417 (indicates reasonably good clustering).

Cluster Insights:

Cluster 0: Older customers, low income, low spending.

Cluster 1: Young customers, moderate income, high spending.

Cluster 2: Middle-aged, high income, high spending.

Cluster 3: Middle-aged, high income, low spending.

Cluster 4: Older customers, moderate income, average spending.

📈 Visualizations
Distribution plots (Age, Income, Spending Score).

Correlation heatmap.

Customer segmentation scatterplot (Income vs Spending Score).

Cluster summary tables.

✅ Conclusion
Customers were successfully grouped into 5 distinct clusters.

K-Means identified customers with similar spending habits.

These clusters can help businesses design personalized marketing campaigns.

Segmentation enables better decision-making and customer satisfaction.

👨‍💻 Author
Ayush Shrivastava  
B.Tech Computer Science, (2024–2028)
