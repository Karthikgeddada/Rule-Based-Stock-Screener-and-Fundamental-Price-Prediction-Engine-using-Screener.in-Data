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

Future Price = Current Price × (1 + Growth Rate) ^ Years


### Output

| Output Type |
|------------|
| Expected CAGR (Low – High) |
| Future Price Range |
| Confidence % |
| Price Growth Line Graph |

⚠️ This system **does not guarantee profit**.  
It only shows a **realistic growth range**.

---

## 🔹 Section 3 – Negative / Downside Prediction System

### Purpose
This module focuses on **risk awareness and downside protection**.

Instead of showing only “best case”, it shows **worst-case scenarios**.

### What It Does

- Reduces baseline growth
- Expands downside range
- Caps unrealistic upside

### Helps Users Learn

✅ Risk management  
✅ Worst-case planning  
✅ Capital protection mindset  

It also generates a **separate downside price graph**.

---

## 🧠 My Investment Logic (Used in Real Life)

This system follows a **tested, real-world rule-based strategy** that I personally use.

### ✅ Top Pick (High Conviction)

A stock becomes a **Top Pick** when:

- Score category is **Good or Excellent**
- **3-Year growth (CAGR) is positive**
- **6-Year growth (CAGR) is positive**

✅ These stocks are treated as **long-term strong investments**.

---

### ✅ Good Pick (Medium Conviction)

A stock becomes a **Good Pick** when:

- Score category is **Average**
- **3-Year growth (CAGR) is positive**

✅ These stocks are treated as **moderate-risk opportunities**.

---

## 📊 Strategy Summary Table

| Category | Score Range | Growth Condition | Decision |
|----------|-------------|------------------|---------|
| Top Pick | Good / Excellent | 3Y ✅ + 6Y ✅ | Strong Buy / Long-term |
| Good Pick | Average | 3Y ✅ | Moderate Buy |

---

## 📈 Real Investment Validation

This project is supported by **real portfolio performance**.

In this repository, you will find:

📁 `/images/` → Screenshots of **Groww portfolio profits**  
Showing how this strategy performed in real investments.

---

## 🛠 Technologies Used

- Python  
- Pandas  
- BeautifulSoup  
- Requests  
- NumPy  
- Matplotlib  

---

## ⚠️ Disclaimer

This project is for:

✅ Learning  
✅ Research  
✅ Decision support  

It is **not financial advice**.  
Always do your own research before investing.

---

## 📌 Project Status

Actively improving:

- Adding better risk models
- Improving growth prediction logic
- Testing with more real-world data

