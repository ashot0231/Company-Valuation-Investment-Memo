# Microsoft Financial Analysis & Investment Evaluation

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Finance](https://img.shields.io/badge/Finance-Equity%20Research-green?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)

</p>


---

# Project Overview

This project presents a comprehensive financial analysis and investment evaluation of Microsoft Corporation (NASDAQ: MSFT).

The analysis follows a structured equity research workflow used to evaluate a company's:

- financial performance;
- profitability;
- cash flow generation;
- financial position;
- market valuation;
- intrinsic value.

The main objective is to assess whether Microsoft's current valuation is supported by its financial fundamentals and long-term business performance.

---

# Business Objective

This project evaluates Microsoft from an investor's perspective by answering the following questions:

- Is Microsoft consistently growing its revenue and earnings?
- Does the company maintain strong profitability?
- Is Microsoft generating sustainable operating and free cash flow?
- Does the company have a healthy financial structure?
- Is the current market valuation justified by financial performance?
- What is Microsoft's estimated intrinsic value based on a DCF valuation model?
- What key risks should investors consider?

---

# Data Source

Financial and market data were collected using the **Yahoo Finance API (yfinance)**.

The analysis includes:

- Income Statement
- Balance Sheet
- Cash Flow Statement
- Market Valuation Data

Analysis period:

**Fiscal Years 2022–2025**

---

# Technologies Used

| Category | Tools |
|---|---|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Financial Data | yfinance |
| Development Environment | Jupyter Notebook |

---

# Project Workflow

The analysis follows a complete financial evaluation pipeline:

```
1. Company Overview
        |
2. Data Collection
        |
3. Financial Performance Analysis
        |
4. Profitability Analysis
        |
5. Cash Flow Analysis
        |
6. Financial Health Analysis
        |
7. Valuation Analysis
        |
8. Discounted Cash Flow (DCF) Valuation
        |
9. Sensitivity Analysis
        |
10. Investment Risks
        |
11. Final Investment Conclusion
```

---

# Financial Analysis Performed

## Financial Performance

Analyzed metrics:

- Revenue
- Revenue Growth
- Gross Profit
- Gross Profit Margin
- Operating Income
- Net Income
- Earnings Growth

---

## Profitability Analysis

Evaluated Microsoft's profitability using:

- Gross Margin
- Operating Margin
- Net Profit Margin
- EBITDA Margin

---

## Cash Flow Analysis

Analyzed:

- Operating Cash Flow
- Free Cash Flow
- Free Cash Flow Growth
- Free Cash Flow Margin

The analysis evaluates Microsoft's ability to generate sustainable cash and support future investments.

---

## Financial Health Analysis

Evaluated:

### Liquidity

- Current Ratio
- Quick Ratio

### Capital Structure

- Total Debt
- Cash Position
- Net Debt

The analysis assesses Microsoft's financial stability and ability to meet short-term and long-term obligations.

---

# Valuation Analysis

The project evaluates Microsoft's market valuation using:

- Trailing P/E Ratio
- Forward P/E Ratio
- Price-to-Sales Ratio
- Price-to-Book Ratio
- EV/EBITDA
- PEG Ratio

These metrics provide insight into how the market values Microsoft's future growth expectations.

---

# Discounted Cash Flow (DCF) Valuation

A simplified DCF model was developed to estimate Microsoft's intrinsic value.

The valuation includes:

- Five-year Free Cash Flow projection
- Discounted future cash flows
- Terminal Value calculation
- Enterprise Value estimation
- Equity Value calculation
- Intrinsic Value per Share

DCF assumptions:

| Parameter | Value |
|---|---:|
| Forecast Period | 5 Years |
| FCF Growth Rate | 8% |
| Discount Rate (WACC) | 8.5% |
| Terminal Growth Rate | 2.5% |

---

# Sensitivity Analysis

A sensitivity analysis was performed to evaluate how changes in:

- Discount Rate (WACC)
- Terminal Growth Rate

impact Microsoft's estimated intrinsic value.

This demonstrates the importance of assumptions when applying DCF valuation methods.

---

# Key Findings

The analysis identified several important characteristics of Microsoft's business:

- Revenue demonstrated consistent growth between 2022 and 2025.
- Gross margins remained close to 69%, reflecting strong profitability and pricing power.
- Microsoft generated significant operating cash flow and free cash flow.
- The company maintained a strong balance sheet with a net cash position.
- Liquidity ratios remained above 1, indicating healthy short-term financial stability.
- Valuation multiples suggest that Microsoft trades at a premium compared with many companies.
- DCF valuation indicates that estimated intrinsic value depends heavily on future growth assumptions and discount rates.

---

# Investment Risks

Despite strong fundamentals, several risks should be considered:

### Artificial Intelligence Competition

Increasing competition in AI could affect Microsoft's ability to maintain its market position.

### Cloud Market Competition

Azure operates in a highly competitive cloud market with major players such as Amazon Web Services and Google Cloud.

### Valuation Risk

Premium valuation multiples create downside risk if future growth expectations are not achieved.

### Regulatory Risk

Large technology companies face increasing regulatory scrutiny globally.

### Macroeconomic Risk

Changes in interest rates and enterprise spending could impact future growth and valuation.

---

# Final Investment Conclusion

Microsoft demonstrates strong financial fundamentals, supported by:

- consistent revenue growth;
- high profitability;
- strong free cash flow generation;
- healthy financial position.

However, valuation analysis indicates that the current market price reflects significant expectations for future growth.

The DCF model suggests that intrinsic value is highly dependent on assumptions related to cash flow growth, discount rates, and terminal growth.

Overall, Microsoft represents a high-quality company with strong long-term fundamentals, but investors should carefully evaluate valuation levels and potential risks before making investment decisions.

---

# Repository Structure

```
Microsoft-Financial-Analysis/

│
├── notebooks/
│   └── Microsoft_Financial_Analysis.ipynb
│
├── images/
│   ├── revenue_trend.png
│   ├── cash_flow_analysis.png
│   ├── valuation_analysis.png
│   └── dcf_sensitivity_heatmap.png
│
├── README.md
│
└── requirements.txt
```

---

# Future Improvements

Possible extensions:

- Comparable Company Analysis
- Peer benchmarking against competitors
- Revenue forecasting models
- Earnings forecasting
- Scenario-based valuation (Bull/Base/Bear cases)
- Automated financial reporting dashboard

---

# Disclaimer

This project was created for educational and portfolio purposes.

All financial information was obtained from publicly available sources. The analysis represents an interpretation of historical financial data and valuation assumptions and should not be considered financial advice.
