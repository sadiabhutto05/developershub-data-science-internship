# Customer Segmentation Using K-Means Clustering

## Project Overview

Customer segmentation is an important business strategy that helps organizations understand different groups of customers based on their purchasing behavior. In this project, machine learning techniques were used to analyze customer data and divide customers into meaningful segments.

Using the Mall Customers Dataset, K-Means Clustering was applied to identify groups of customers with similar characteristics. These segments can help businesses design targeted marketing campaigns, improve customer satisfaction, and increase overall sales performance.

---

## Objective

The main objective of this project is to segment customers based on their annual income and spending behavior using unsupervised machine learning techniques. The identified customer groups can then be used to develop personalized marketing strategies for different customer categories.

---

## Dataset Information

The project uses the Mall Customers Dataset, which contains basic customer information collected by a shopping mall.

### Features

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

The Spending Score represents customer purchasing behavior and spending habits assigned by the mall.

---

## Project Workflow

### 1. Data Exploration and Analysis

The dataset was explored to understand customer demographics and spending patterns. Various visualizations were created to analyze distributions of age, income, gender, and spending scores.

### 2. Data Preprocessing

Relevant features were selected and standardized to ensure all variables contributed equally to the clustering process.

### 3. Customer Segmentation using K-Means

The K-Means clustering algorithm was applied to group customers into distinct segments. The Elbow Method was used to determine the optimal number of clusters.

### 4. Cluster Visualization

Principal Component Analysis (PCA) was used to reduce the dimensions of the data and visualize customer segments in a two-dimensional space.

### 5. Business Insights

Each cluster was analyzed to understand customer behavior and develop suitable marketing recommendations.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Results

The K-Means algorithm successfully identified five distinct customer segments based on income and spending behavior. These segments reveal different customer types such as high-value customers, budget-conscious customers, and average shoppers.

The clustering results can help businesses:

* Improve customer targeting
* Design personalized promotions
* Increase customer retention
* Enhance marketing effectiveness
* Maximize business revenue

---

## Marketing Strategies

### High Income – High Spending Customers

* Offer premium memberships and exclusive rewards.
* Provide early access to new products and services.

### High Income – Low Spending Customers

* Use personalized marketing campaigns to encourage purchases.
* Recommend products based on customer preferences.

### Low Income – High Spending Customers

* Provide discounts, coupons, and loyalty rewards.
* Promote seasonal sales and special offers.

### Low Income – Low Spending Customers

* Focus on affordable products and awareness campaigns.
* Encourage engagement through promotional activities.

### Average Customers

* Apply cross-selling and upselling strategies.
* Introduce membership programs and incentives.

---

## Conclusion

This project demonstrates how unsupervised machine learning can be used to identify meaningful customer segments. By applying K-Means Clustering and PCA visualization, customer behavior patterns were successfully discovered. These insights can help businesses make data-driven decisions and implement targeted marketing strategies that improve customer engagement and profitability.
