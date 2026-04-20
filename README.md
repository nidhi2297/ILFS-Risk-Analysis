# 📊 IL&FS Risk Analysis: Early Warning Signals Before Collapse (2013-2018)

## 🔍 Project Overview
IL&FS Financial Services Limited (IFIN), a systemically important NBFC in India, collapsed in 2018 despite maintaining a **AAA credit rating**, until the very month of default in 2018.

This project aims to answer a critical question:

👉 *Could the collapse have been predicted using financial data?*

Using annual financial statements from 2013–2018, this project identifies the "red flags" that credit rating agencies missed and builds a **Composite Risk Score Model** to quantify the deterioration of the firm's solvency

## ⚠️ Why This Case Matters

- One of India’s largest financial crises
- ₹90,000+ crore debt exposure
- Contagion impact across NBFC and banking sector
- Highlighted gaps in Risk assessment, Credit rating frameworks and Liquidity management  

## 🧠 Methodology

A data-driven financial analysis was performed using key risk indicators

### 📌 Risk Indicators Used

| Indicator | Metric | Interpretation |
|----------|--------|---------------|
| Leverage | Debt / Equity | Higher = higher financial risk |
| Liquidity Risk | Short-term obligations / Total Debt | Higher = refinancing pressure |
| Coverage | EBIT / Interest Expense | Lower = stress in servicing debt |
| Cash Flow Health | CFO / Total Debt | Negative = liquidity stress |
| Asset Quality | Provisions / Total Assets | Rising = deteriorating asset quality |
| Market Dependence | Commercial Paper / Total Debt | Higher = reliance on market funding |

## 📈 Composite Risk Score 
To move beyond basic ratio analysis, I developed a weighted **Composite Risk Score (CRS)** to aggregate different dimensions of distress. 

0.20 × Liquidity +
0.25 × Cash Flow +
0.20 × Coverage +
0.20 × Leverage +
0.10 × Provision +
0.05 × Market Dependence

* **Normalization:** All variables were scaled from 0 (Low Risk) to 1 (High Risk).
* **Directional Adjustment:** Inverted metrics (like Interest Coverage) were adjusted so that a lower ratio leads to a higher risk score.


## 📊 Key Insights

- 📈 Risk score increased sharply by FY2017–18  
- ⚠️ Liquidity risk increased due to rising short-term borrowings  
- 📉 Cash flows turned negative before default  
- 📉 Coverage ratio declined steadily  
- 📊 Provision levels increased, indicating asset stress  
- 🚨 Despite these signals, credit rating remained **AAA**

| Financial Year | Credit Rating | Composite Risk Score | Market Context |
| :--- | :--- | :--- | :--- |
| **FY 2013-14** | AAA | 0.13 (Stable) | Steady growth in infra book; ALM manageable. |
| **FY 2014-15** | AAA | 0.18 (Stable) | Static Assets and focus on curbing delinquencies. |
| **FY 2015-16** | AAA | 0.47 (Caution) | **CFO turns negative**; reliance on short-term debt |
| **FY 2016-17** | AAA | 0.28 (Caution) | Interest coverage drops; focus on managing NPAs and stressed assets. |
| **FY 2017-18** | AAA | **0.78 (High Risk)** | Provisions rise, Cash flows negative, coverage drops significantly, leverage rises, liquidity risk |

In FY 2018-19, the Credit ratings dropped to D (Default) indicating systemic collapse leading to a turmoil in the NBFC sector in India. 

## 📊 Dashboard Preview
The analysis was visualized in Power BI to track the Y-o-Y deterioration of solvency and liquidity.
<p align="center">
  <img src="IL&FS Dashboard preview.png" width="90%">
</p>

## 🏗️ Structural Weaknesses Identified

### 1. ALM Mismatch
IL&FS used **short-term commercial paper** (low cost but high turnover) to fund **long-term infrastructure projects** (illiquid). When market liquidity dried up, the "house of cards" collapsed.

### 2. Hidden Liabilities
The parent company leveraged its equity to fund subsidiaries, which then took on additional debt. Extensive **guarantees to related parties** acted as off-balance-sheet liabilities that materialized during the stress period.

### 3. Debt Distribution Model Risk
Risk was transferred but retained through guarantees.

### 4. The "AAA" Mirage
Despite a negative **Cash Flow from Operations (CFO)** and a declining **Interest Coverage Ratio**, credit agencies maintained a AAA rating, highlighting a massive failure in external risk assessment frameworks.

### 5. Complex Group Structure
IL&FS used complex debt products with senior and subordinate debts and varying charges.Reduced transparency and masked underlying financial risks. 

## 🛠️ Tools & Skills Used

* **Financial Modeling:** Ratio Analysis, Normalization, Weighted Scoring Models.
* **Power BI:** Implemented `Time Intelligence DAX` to visualize multi-year financial trends.
* **Excel:** Forensic data cleaning and Z-score calculation.

## 📂 Repository Contents
- `IL&FS data.xlsx` → Cleaned dataset  
- `IL&FS analysis.pbix` → Power BI dashboard  
- `IL&FS.docx` → Detailed case study  
- `IL&FS Dashboard preview.png` → Dashboard snapshot
  
## 🎯 Key Takeaway

The IL&FS crisis was not sudden.

👉 Financial indicators clearly showed early warning signals  
👉 However, these were not reflected in credit ratings  

This highlights the importance of **independent financial risk analysis**.

## 📌 Disclaimer

This project is for educational and portfolio purposes.  
Data was sourced from public financial reports (2013-2018)

## 👤 About the Author
[Nidhi Sharma] * Aspiring Quantitative Analyst | CFA Level 1 Candidate | ISI Alumnus*

📧 Contact & Connect
LinkedIn: Nidhi Sharma
Portfolio: [(https://github.com/nidhi2297/ILFS-Risk-Analysis)]
