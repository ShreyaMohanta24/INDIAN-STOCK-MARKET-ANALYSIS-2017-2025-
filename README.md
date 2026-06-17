# 📈 Indian Stock Market Analysis (2017–2025)

### 6 Companies | NIFTY 50 Analysis | ANOVA Testing | Tableau Dashboard

---

## 📖 Project Overview

The Indian stock market experiences frequent fluctuations, making it difficult for investors to understand price trends, compare returns, and assess market risk. This project analyzes the stock price trend of a selected company, compares returns of companies, and examines the volatility of major index like NIFTY using historical data to support better investment decisions.

---

## 📂 Project Structure

```text
Stock_Market_Project/
│   ├── Descriptive_Analysis_Project.ipynb
│   ├── Reliance_Industries_Analysis.ipynb
│   ├── HDFC_Bank_Analysis.ipynb
│   ├── ITC_Limited_Analysis.ipynb
│   ├── Maruti_Suzuki_Analysis.ipynb
│   ├── Ballarpur_Industries_Analysis.ipynb
│   ├── RCOM_Analysis.ipynb
│   └── Stock_EDA_Analysis.ipynb

└── Final_Dashboard.twbx

└── README.md
```

---

## Data Source

Historical stock market data was collected using the `yfinance` Python library, which provides access to financial data from Yahoo Finance. The dataset includes stock prices of selected Indian companies and NIFTY 50 index data from 2017 to 2025.

---

## Technologies Used

- Python
- Jupyter Notebook
- yfinance
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Tableau
  
---

## 📊 Analysis Performed

### Exploratory Data Analysis (EDA)

- Collected historical stock data using the yfinance library
- Cleaned and preprocessed stock price data
- Calculated daily stock returns
- Handled missing values

### Annualized Return Analysis

- Calculated annualized returns for selected companies
- Compared stock performance across multiple companies
- Identified high-performing and low-performing stocks
- Visualized return comparisons using bar charts

### Volatility (Risk) Analysis

- Calculated annualized volatility of stock returns
- Compared risk levels among selected stocks
- Identified high-risk and low-risk stocks
- Visualized volatility through comparative charts

### Risk-Return Analysis

- Examined the relationship between risk and return
- Created risk-return scatter plots
- Evaluated investment attractiveness of stocks
- Compared stable and highly volatile stocks

### Correlation Analysis

- Generated a correlation matrix of stock returns
- Visualized correlations using heatmaps
- Identified relationships between stock movements
- Analyzed diversification opportunities

### Risk Segmentation and Grouping

- Classified stocks into Low Risk, Medium Risk, and High Risk categories
- Grouped stocks based on volatility levels
- Compared average returns across risk categories
- Analyzed the distribution of stocks by risk level

### Statistical Analysis (ANOVA)

- Performed One-Way ANOVA on stock returns
- Tested whether significant differences exist among stock returns
- Evaluated statistical significance using p-values
- Interpreted results based on hypothesis testing

---

## Dataset Information

| Feature | Description |
|----------|------------|
| Date | Trading date |
| Open | Opening price |
| High | Highest price |
| Low | Lowest price |
| Close | Closing price |
| Volume | Number of shares traded |

---

## 🎯 Key Insights

1. Historical stock data was analyzed to identify market trends.
2. Return analysis was used to compare the performance of selected companies.
3. Volatility analysis helped assess the risk associated with different stocks.
4. Correlation analysis showed relationships between stock price movements.
5. Statistical methods were applied to support data-driven conclusions.

---

## 📊 Tableau Dashboard

The Tableau dashboard provides:

- Interactive stock trend visualization
- Risk and return analysis
- Return and volatility comparison charts
- Trading volume analysis
- Stock correlation heatmap
- Market performance insights
  
---

## 🚀 How to Run

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Open Jupyter Notebook

```bash
jupyter notebook
```

### Launch Tableau Dashboard

Open `Final_Dashboard.twbx` in Tableau Desktop.

---

## 👩‍💻 Author

**Shreya Mohanta**

B.Tech Computer Science and Engineering  
Lovely Professional University
