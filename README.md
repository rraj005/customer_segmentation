# 🛍️ Customer Segmentation Using K-Means Clustering

This project focuses on **Customer Segmentation** by applying **K-Means Clustering** on the popular **Mall Customer Segmentation Dataset**.

The aim is to categorize mall customers into distinct groups based on **Annual Income**, **Spending Score**, **Age**, and **Gender**, helping businesses target the right customer groups with tailored marketing strategies.

---

## 📂 Dataset Used

- **Mall_Customers.csv**
- Columns:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

---

## 📊 Project Workflow

1. **Data Loading and Cleaning**
   - Imported the dataset using `pandas`.
   - Checked for missing values and handled them using forward and backward fill.

2. **Exploratory Data Analysis (EDA)**
   - Univariate and bivariate analysis using `Seaborn` and `Matplotlib`.
   - Histograms of Annual Income, Spending Score, and Age.
   - Pie chart to visualize gender distribution.
   - Scatter plots and boxplots to explore relationships.

3. **Outlier Detection and Removal**
   - Used **Interquartile Range (IQR)** method on Spending Score to filter outliers.

4. **Feature Engineering**
   - Binned Annual Income into categories.
   - One-Hot Encoded the Gender feature for modeling.

5. **Customer Segmentation using K-Means**
   - Applied **K-Means Clustering**.
   - Determined optimal number of clusters (k) using the **Elbow Method**.
   - Visualized customer clusters.

6. **Pairplot Visualization**
   - Used Seaborn Pairplot to visually inspect how Gender, Income, and Spending Score interact across clusters.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (KMeans, OneHotEncoder)

---

## 📈 Results

- Successfully segmented customers into **distinct clusters** based on behavior patterns.
- Insights include high-income low-spending customers, low-income high-spending customers, etc.

These customer segments can help marketing teams design more targeted campaigns.

---

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/rraj005/customer-segmentation.git
