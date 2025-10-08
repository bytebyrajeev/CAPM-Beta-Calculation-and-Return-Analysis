# 💰 CAPM – Beta Calculation and Return Analysis

## 🧠 Project Overview
This project implements the **Capital Asset Pricing Model (CAPM)** to evaluate the **risk–return relationship of stocks** using historical financial data.  
It helps investors and analysts estimate **beta values**, **expected returns**, and visualize the **risk exposure** of multiple stocks through an interactive **Streamlit dashboard**.

By leveraging real-world data from **Yahoo Finance** and **FRED (Federal Reserve Economic Data)**, the project provides actionable insights into stock performance and portfolio optimization.

---

## 🎯 Business Objective
Financial analysts often need to understand how individual stocks move relative to the overall market.  
This project answers the question:  
> *How can we measure and visualize stock risk (beta) and expected returns using CAPM for smarter investment decisions?*

---

## 🧩 Tools & Libraries Used
- **Python**
- **Pandas**, **NumPy** – Data manipulation and computation  
- **yFinance**, **pandas_datareader** – Financial data extraction  
- **Plotly**, **Matplotlib** – Interactive data visualization  
- **Streamlit** – Web-based dashboard for analysis  
- **FRED API** – Fetching risk-free rate data  
- **Jupyter Notebook / VS Code** – Development environment  

---

## 📈 Methodology

### 1. Data Collection
- Pulled **historical stock prices** and **market index data** using Yahoo Finance API.
- Retrieved **risk-free rates** from FRED (U.S. 10-Year Treasury Yield).

### 2. Data Preparation
- Calculated **daily returns** for individual stocks and the market index.  
- Normalized price data for better visualization.  
- Handled missing or inconsistent values.

### 3. Beta Calculation
- Estimated each stock’s **beta coefficient** using covariance and variance.  
- Compared stock volatility against the benchmark market index (e.g., S&P 500).

### 4. CAPM Return Estimation
- Used the CAPM formula:  
  	**Expected Return = Risk-Free Rate + Beta × (Market Return – Risk-Free Rate)**  
- Calculated expected vs. actual returns for each stock.

### 5. Interactive Dashboard
- Built with **Streamlit** to allow users to:  
  - Select multiple stocks.  
  - View beta and expected return values.  
  - Visualize stock vs. market trends interactively.

---

## 📊 Key Features
- 🔹 Fetches live market data from Yahoo Finance and FRED.  
- 🔹 Computes **Beta**, **Expected Return**, and **Market Sensitivity** for each stock.  
- 🔹 Visualizes stock performance and volatility with **interactive Plotly charts**.  
- 🔹 Enables side-by-side comparison of multiple stocks in one dashboard.  

---

## 💡 Business Insights
- Stocks with **beta > 1** are more volatile than the market, implying higher risk and potential return.  
- **Defensive stocks** (beta < 1) offer lower risk and more stability.  
- CAPM-based expected return helps in **portfolio diversification** and **risk-adjusted performance evaluation**.  
- A **positive correlation** between market return and individual stock return indicates efficient market behavior.

---

## 🧰 How to Run the Project

1. **Clone this repository**
   ```bash
   git clone https://github.com/bytebyrajeev/CAPM-Beta-Calculation-and-Return-Analysis.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd CAPM-Beta-Calculation-and-Return-Analysis
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app**
   ```bash
   streamlit run CAPM_Return.py
   ```


---

## 🚀 Skills Demonstrated
- Financial Data Analysis  
- CAPM & Beta Calculation  
- Exploratory Data Analysis (EDA)  
- Interactive Dashboard Design (Streamlit)  
- Data Visualization (Plotly, Matplotlib)  
- Business Insights Communication  

---

## 🧾 Author
**Rajeev Ranjan** 

📧 [raeev108.tech@gmail.com]  
🔗 [www.linkedin.com/in/rajeev-tech1]  
📂 [https://github.com/bytebyrajeev]

