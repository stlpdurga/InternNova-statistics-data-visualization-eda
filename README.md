# InternNova-statistics-data-visualization-eda
# Statistics, Data Visualization & Exploratory Data Analysis

## 📌 Project Overview

This project is based on statistical analysis, data visualization, and exploratory data analysis (EDA) using the Superstore dataset.

The objective of this project is to apply statistical concepts, create meaningful visualizations, analyze relationships between variables, identify patterns and outliers, and provide data-driven business recommendations.

## 📂 Dataset

**Dataset:** `cleaned_superstore.csv`

The dataset contains **1,000 records and 14 columns**, including:

- Order ID
- Order Date
- Ship Mode
- Customer Name
- Segment
- Region
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit
- Month

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Task 1: Statistical Analysis – Mean, Median & Mode

The `Quantity` variable was selected for statistical analysis.

- Mean: **5.532**
- Median: **6**
- Mode: **1**

### Interpretation

The mean represents the average quantity ordered. The median indicates the middle value of the dataset, while the mode represents the most frequently occurring quantity.


<img width="390" height="167" alt="Screenshot 2026-10-05 203429" src="https://github.com/user-attachments/assets/b7e35332-7d7f-4e45-9f82-8b907f38a043" />

---

## 📈 Task 2: Variance & Standard Deviation

Variance and standard deviation were calculated using the `Quantity` variable.

- Variance: **8.775**
- Standard Deviation: **2.962**

### Interpretation

The standard deviation indicates how much the quantity values vary from the average quantity.


<img width="428" height="73" alt="Screenshot 2026-10-05 203815" src="https://github.com/user-attachments/assets/95ac067c-69aa-46e6-acbb-e4b02a203f5b" />

---

## 🔗 Task 3: Correlation & Probability

### Correlation

The correlation between **Sales and Profit** was calculated.

- Correlation: **0.054**
- Relationship: **Very weak positive correlation**

### Probability

The probability of randomly selecting an order from the **Technology** category was calculated.

- Probability: **35.3%**

<img width="497" height="98" alt="Screenshot 2026-10-05 204103" src="https://github.com/user-attachments/assets/34cb188b-e2d0-4e94-814f-72b7f00a93f3" />

---

## 🔍 Task 4: Outlier Detection

The **IQR (Interquartile Range)** method was used to identify potential outliers in Sales.

- Q1: **278.3725**
- Q3: **754.51**
- IQR: **476.1375**
- Lower Bound: **-435.83375**
- Upper Bound: **1468.71625**
- Detected Outliers: **0**

No Sales values were identified as outliers using the IQR method.

<img width="316" height="118" alt="Screenshot 2026-10-05 204547" src="https://github.com/user-attachments/assets/e091005c-deaa-45b2-9012-9618416f59ab" />

---

# 📊 Task 5: Matplotlib Visualization

The following visualizations were created using Matplotlib:

1. Line Chart – Monthly Sales
2. Bar Chart – Sales by Category
3. Pie Chart – Sales Distribution by Category
4. Histogram – Profit Distribution
5. Scatter Plot – Sales vs Profit

These visualizations were used to understand sales trends, category performance, profit distribution, and relationships between variables.

<img width="713" height="470" alt="Line Chart" src="https://github.com/user-attachments/assets/e68b3365-618a-4f16-8a20-a5e0746ad834" />
<img width="721" height="470" alt="Bar Chart" src="https://github.com/user-attachments/assets/2d14cd7a-996b-4731-814f-995d45524719" />
<img width="630" height="581" alt="Pie Chart" src="https://github.com/user-attachments/assets/65f02251-54b8-4b24-95ea-45aa994c12c2" />
<img width="686" height="470" alt="Histogram" src="https://github.com/user-attachments/assets/2b0a2deb-f39a-4caa-a733-4858e5093f32" />
<img width="698" height="470" alt="Scatter Plot" src="https://github.com/user-attachments/assets/639cf65e-578d-4e04-bd4c-e4ee023baaeb" />


---

# 📉 Task 6: Seaborn Visualization

The following Seaborn visualizations were created:

1. Count Plot – Orders by Category
2. Box Plot – Profit by Category
3. Heatmap – Correlation Analysis
4. Pair Plot – Numerical Variables

These visualizations helped identify patterns, distributions, and relationships among the variables.

<img width="695" height="470" alt="Count Plot" src="https://github.com/user-attachments/assets/1d42c1de-86e6-4b4c-86ce-423857aee68d" />
<img width="698" height="470" alt="Box Plot" src="https://github.com/user-attachments/assets/0bd5c1ad-a6e3-482b-9a58-0b8cf1ec0024" />
<img width="625" height="528" alt="HeatMap" src="https://github.com/user-attachments/assets/40a433ea-7449-4845-ac35-f0ecd88969af" />
<img width="985" height="986" alt="Pair Plot" src="https://github.com/user-attachments/assets/80774333-48fb-4836-a272-34d175491239" />

---

# 🔎 Task 7: Exploratory Data Analysis

### Data Inspection

The dataset contains:

- **1,000 rows**
- **14 columns**

The columns, data types, and statistical summary were examined.

### Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Incorrect data types
- Inconsistent values
- Invalid numerical values

No missing values or duplicate records were found. The dataset was prepared for further analysis.

<img width="596" height="437" alt="Screenshot 2026-10-05 210145" src="https://github.com/user-attachments/assets/70a73396-3c66-4320-ad20-ed9ff487786a" />
<img width="622" height="607" alt="Screenshot 2026-10-05 210156" src="https://github.com/user-attachments/assets/85e7805a-ffcf-4163-a2a8-0a66b5ca3fc2" />

---

# 📌 Task 8: EDA – Correlation & Insights

Correlation analysis was performed on:

- Sales
- Quantity
- Discount
- Profit

### Important Correlations

| Variables | Correlation |
|---|---:|
| Sales & Profit | 0.054 |
| Quantity & Profit | -0.052 |
| Discount & Profit | -0.032 |

### Key Insights

1. **Technology is a strong-performing category** in terms of sales and profit.

2. **Central region has the highest sales** among the regions in the dataset.

3. **Sales and Profit have a very weak positive correlation (0.054)**, indicating that sales alone do not strongly determine profitability.

<img width="675" height="651" alt="Screenshot 2026-10-05 211203" src="https://github.com/user-attachments/assets/b2278421-c0f9-4e43-9021-28b11a17cdf1" />

---

# 💼 Task 9: Business Recommendations

### Recommendation 1: Focus on Technology Products

Technology generated the highest sales and profit among the categories. The business should maintain sufficient inventory and focus on profitable Technology products.

### Recommendation 2: Improve West Region Performance

The West region recorded the lowest sales among the regions. The business should analyze customer preferences and introduce targeted marketing strategies to improve sales in this region.

---

## 👩‍💻 Author

**Saga Tejaswi Lakshmi Priya Durga**
