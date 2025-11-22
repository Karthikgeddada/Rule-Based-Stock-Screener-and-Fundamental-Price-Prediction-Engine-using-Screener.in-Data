# Rule-Based Stock Screener & Fundamental Price Prediction Engine  
### Using Screener.in Data

This project is built to help **students, busy working professionals, and practical investors** understand stock fundamentals clearly without spending hours on financial analysis.

The system uses **explainable, rule-based logic** instead of black-box AI, so every output is transparent and easy to understand.

> ⚠️ This is a **learning and research project**.  
> It is **not financial advice**.

---

## 🔹 Section 1 – Screener Data Extractor & Rule-Based Scoring System

### Purpose
This module automatically:

- Fetches financial data from **Screener.in**
- Cleans and structures raw data
- Evaluates stocks using **23 transparent financial rules**

### How It Works

User inputs:
- NSE / BSE / SME stock symbol

The system extracts key data such as:

- Market Cap  
- ROE, ROCE  
- P/E Ratio  
- Borrowings  
- Reserves  
- Promoter Holding  
- Debt and Cash Flow  

Then applies rules like:

| Rule | Logic |
|------|--------|
| Market Cap ≥ ₹20,000 Cr | Company stability |
| ROE ≥ 12% | Profit efficiency |
| Low Debt | Financial safety |
| Strong Cash Flow | Business health |

Each rule returns:

- `1` → Passed  
- `0` → Failed  
- `None` → Data not available  

### Output

The system calculates:

- Final Score (0–25)
- Score Percentage
- Category:
  - Excellent
  - Best
  - Good
  - Average
  - Poor

This helps users **quickly filter fundamentally strong stocks**.

---

## 🔹 Section 2 – Fundamental Price Prediction System (Positive Scenario)

### Purpose
This module generates **realistic future price ranges** instead of fake exact predictions.

It calculates:

- Minimum expected growth  
- Maximum expected growth  
- Confidence level  
- Trend (Uptrend / Sideways / Weak Downtrend)

### How It Works

Uses financial inputs:

- Sales Growth  
- Profit Growth  
- ROE  
- ROCE  
- Market Cap  
- Risk indicators:
  - Cash Conversion Cycle  
  - Inventory Days  
  - Debtor Days  

### Prediction Formula Used

