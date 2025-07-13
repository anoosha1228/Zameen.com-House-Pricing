# 🏡 Zameen.com Housing Data Analysis

This project explores and analyzes real estate data scraped from [Zameen.com]([https://www.kaggle.com/datasets/mohammadfaisal962/zameencom-properties-dataset](https://www.kaggle.com/datasets/huzzefakhan/zameencom-property-data-pakistan)). The goal is to clean, transform, and visualize the dataset to uncover patterns, trends, and actionable insights in the Pakistani housing market.

---

## 📦 Dataset

- **Source:** [Zameen.com Properties Dataset on Kaggle]([https://www.kaggle.com/datasets/mohammadfaisal962/zameencom-properties-dataset](https://www.kaggle.com/datasets/huzzefakhan/zameencom-property-data-pakistan))
- **Description:** Contains property listings with features such as location, number of bedrooms, bathrooms, area, price, and more.

---

## 📌 Project Steps

### 🔹 1. Load and Explore the Dataset
- Import and load the dataset using pandas.
- Display the first few rows and get a sense of its structure.
- Check the number of rows and columns.

### 🔹 2. Understand the Features
- Explore each feature, understand their datatypes and significance.
- Identify categorical and numerical features.

### 🔹 3. Analyze the Distribution of Each Feature
- Use **Seaborn**, **Matplotlib**, and **Plotly** to plot distributions.
- Visualize numerical distributions (e.g., area, price).
- Visualize categorical distributions (e.g., city, property type).

### 🔹 4. Descriptive Statistics
- Generate summary statistics (mean, median, mode, std, etc.) to understand central tendency and spread.

### 🔹 5. Handle Missing Values
- Detect missing/null values.
- Impute (e.g., using median or mode) or remove rows/columns based on analysis.

### 🔹 6. Normalize Features
- Apply feature scaling to normalize numerical features using methods like Min-Max or Standard Scaler.

### 🔹 7. Outlier Detection
- Identify outliers using box plots or Z-score methods.
- Decide whether to remove or cap the outliers.

### 🔹 8. Encode Categorical Variables
- Convert string categories (e.g., 'City', 'Property Type') to numerical form using One-Hot Encoding or Label Encoding.

### 🔹 9. Feature Engineering
- Create new features (e.g., price per marla/sqft).
- Combine or transform existing features if needed.
- Remove irrelevant or redundant features.

### 🔹 10. Data Visualization
- Visualize:
  - Correlation between features
  - Price distribution across cities and property types
  - Area vs Price relationships
  - Bedrooms/Bathrooms vs Price

### 🔹 11. Hypothesis Formulation
- 📌 **Hypothesis 1:** Houses located in Lahore have higher average prices than houses in other cities.
- 📌 **Hypothesis 2:** The number of bedrooms is positively correlated with the property price.
- 📌 **Hypothesis 3:** Plots with larger area have a non-linear relationship with price — after a certain point, the price increase slows down.

---

## 📈 KPIs Tracked

- 🏡 Average property price per city
- 📍 Price per unit area (Marla or sqft)
- 🛏️ Average number of bedrooms and bathrooms per city
- 🧮 Property count by city and property type
- 📊 Median vs. Mean price comparisons
- 📉 Missing value percentage per feature

---

## 📊 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly`
- `scikit-learn`

---

## 🛠 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/zameen-housing-analysis.git
   cd zameen-housing-analysis
