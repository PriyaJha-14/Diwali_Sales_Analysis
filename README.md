<div align="center">

# 🪔 Diwali Sales Analysis

### Exploratory Data Analysis (EDA) on Diwali Festival Sales Data

[
[
[
[
[

</div>

***

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Diwali festival sales data to uncover key insights about customer behavior, demographics, purchasing patterns, and product preferences. The goal is to help businesses make **data-driven decisions** — from inventory management to targeted marketing — during one of India's biggest shopping seasons.

> 💡 **Key Goal:** Identify the most valuable customer segments and top-performing product categories to improve customer experience and boost sales revenue.

***

## 📂 Repository Structure

```
Diwali_Sales_Analysis/
│
├── Diwali Sales Analysis.ipynb   # Main Jupyter Notebook with full EDA
├── Diwali_Sales_Data.csv         # Raw dataset (11,251 records × 15 columns)
└── README.md                     # Project documentation
```

***

## 📊 Dataset Description

The dataset contains **11,251 rows** and **15 columns** representing individual customer transactions during the Diwali season.

| Column | Description |
|--------|-------------|
| `User_ID` | Unique customer identifier |
| `Cust_name` | Customer name |
| `Product_ID` | Unique product identifier |
| `Gender` | Male / Female |
| `Age Group` | Age bracket (e.g., 18-25, 26-35) |
| `Age` | Exact age of the buyer |
| `Marital_Status` | 0 = Unmarried, 1 = Married |
| `State` | Indian state of the buyer |
| `Zone` | Geographic zone (North / South / East / West / Central) |
| `Occupation` | Buyer's profession |
| `Product_Category` | Category of product purchased |
| `Orders` | Number of orders placed |
| `Amount` | Total purchase amount (₹) |
| `Status` | Dropped (irrelevant) |
| `unnamed1` | Dropped (irrelevant) |

***

## 🛠️ Technologies Used

| Library | Purpose |
|---------|---------|
| `Python 3.x` | Core programming language |
| `NumPy` | Numerical computations |
| `Pandas` | Data loading, cleaning, and manipulation |
| `Matplotlib` | Basic charts and plots |
| `Seaborn` | Advanced statistical visualizations |

***

## 🔄 Project Workflow

```
1. Data Loading        →  Load CSV using Pandas
2. Data Exploration    →  shape, info(), describe(), head()
3. Data Cleaning       →  Drop nulls, irrelevant columns, fix dtypes
4. EDA                 →  Demographic & Product-level analysis
5. Visualization       →  Bar charts, count plots using Seaborn/Matplotlib
6. Insights            →  Business recommendations from findings
```

***

## 🔍 Exploratory Data Analysis

### 👩 Gender Analysis
- Female buyers out number male buyers in total orders.
- Female buyers also have **higher total spending** than male buyers.
- ✅ **Insight:** Women are the primary consumer segment during Diwali.

***

### 🎂 Age Group Analysis
- The **26–35 age group** dominates in both orders and revenue.
- Females aged 26–35 represent the **highest-value customer segment**.
- ✅ **Insight:** Target marketing campaigns towards the 26–35 female demographic.

***

### 🗺️ State-wise Analysis
- Top 3 states by orders and revenue:
  1. 🥇 Uttar Pradesh
  2. 🥈 Maharashtra
  3. 🥉 Karnataka
- ✅ **Insight:** Focus logistics and stock in these high-performing states.

***

### 💍 Marital Status Analysis
- **Married women** are the largest single buying group.
- Married buyers show higher average transaction value.
- ✅ **Insight:** Festive combo offers resonate most with married women.

***

### 💼 Occupation Analysis
- Highest-spending professions:
  - IT Sector
  - Healthcare
  - Aviation
- ✅ **Insight:** Premium product promotions should target IT and Healthcare professionals.

***

### 🛒 Product Category Analysis
| Rank | Category | Metric |
|------|----------|--------|
| 🥇 1 | Food | Highest number of orders |
| 🥈 2 | Clothing & Apparel | Second most popular |
| 🥉 3 | Electronics & Gadgets | Highest revenue per unit |

- ✅ **Insight:** Stock up on Food and Clothing for volume; Electronics for high-margin revenue.

***

## 💡 Key Findings

> **Most Valuable Customer Profile:**
> *Married women aged 26–35, from Uttar Pradesh / Maharashtra / Karnataka, working in IT / Healthcare / Aviation — purchasing Food, Clothing, and Electronics.*

| Dimension | Finding |
|-----------|---------|
| Best Customer Segment | Married women, age 26–35 |
| Top Revenue States | Uttar Pradesh, Maharashtra, Karnataka |
| Top Product Categories | Food, Clothing, Electronics |
| Best Occupation Targets | IT, Healthcare, Aviation |
| Purchasing Power | Female > Male |

***

## 🚀 How to Run This Project

### Prerequisites
Make sure you have Python 3.x installed along with the following libraries:

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/PriyaJha-14/Diwali_Sales_Analysis.git

# 2. Navigate into the project directory
cd Diwali_Sales_Analysis

# 3. Launch Jupyter Notebook
jupyter notebook

# 4. Open and run the notebook
# → Diwali Sales Analysis.ipynb
```

***

## 📈 Sample Visualizations

The notebook includes the following charts:

- 📊 Gender vs. Total Amount (Bar Chart)
- 📊 Age Group vs. Total Orders and Amount (Bar Chart)
- 📊 Top 10 States by Orders and Amount
- 📊 Marital Status vs. Amount by Gender
- 📊 Occupation vs. Total Amount
- 📊 Product Category vs. Orders and Amount
- 📊 Top 10 Most Sold Products

***

## 🔮 Future Scope

- [ ] Add time-series analysis of sales trends across Diwali days
- [ ] Build a customer segmentation model using K-Means Clustering
- [ ] Develop a sales prediction model using Linear Regression
- [ ] Create an interactive dashboard using Plotly Dash or Power BI
- [ ] Add geographic heatmaps for state-wise performance

***

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes and commit (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

***

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

***

## 👩‍💻 Author

**Priya Jha**



***

<div align="center">

⭐ **If you found this project useful, please give it a star!** ⭐

</div>
