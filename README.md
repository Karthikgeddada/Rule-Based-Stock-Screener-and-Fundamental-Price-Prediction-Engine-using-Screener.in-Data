# Rule-Based-Stock-Screener-and-Fundamental-Price-Prediction-Engine-using-Screener.in-Data
This project was built to help students, busy working professionals, and practical investors understand stock fundamentals clearly without spending hours on financial analysis.

Section 1 – Screener Data Extractor & Rule-Based Scoring System
Purpose:

This part of the system automatically:

Fetches financial data from Screener.in

Cleans raw data

Evaluates stocks using 23 transparent financial rules

How It Works:

User enters:

NSE / BSE / SME stock code

The system then:

Extracts:

Market Cap

ROE, ROCE

P/E Ratio

Borrowings

Reserves

Promoter holding

Debt, Cash Flow, etc.

Applies rules like:

Rule	Logic
Market Cap ≥ ₹20,000 Cr	Company stability
ROE ≥ 12%	Profit efficiency
Low Debt	Financial safety
Strong Cash Flow	Business health

Each rule gives:

1 if passed

0 if failed

None if data missing

Finally, the system calculates:

Final Score (0–25)

Percentage Score

Category:

Excellent

Best

Good

Average

Poor

This helps users quickly filter quality stocks.

4. Section 2 – Stock Price Prediction System (Positive Scenario)
Purpose:

This section gives a realistic future price range.

Instead of fake “exact predictions”, it calculates:

✅ Minimum possible growth
✅ Maximum possible growth
✅ Confidence level
✅ Future trend (Uptrend / Sideways / Weak Downtrend)

How It Works:

The system uses:

Sales Growth

Profit Growth

ROE

ROCE

Market Cap

Risk factors like:

Cash Conversion Cycle

Inventory Days

Debtor Days

Then it calculates:

Output
Expected CAGR (Low – High)
Future Price Range
Confidence %
Visual Line Graph

Example logic:

Price after 5 years = Current Price × (1 + Growth Rate) ^ Years


This does not promise profit.
It shows a realistic range.

5. Section 3 – Negative / Downside Prediction System
Purpose:

To protect users from over-confidence.

Most systems show only “best case”.
This section shows worst-case scenarios.

What It Does:

Reduces baseline growth

Expands downside range

Caps upside growth

This teaches users:

✅ Risk management
✅ Worst-case planning
✅ Capital protection mindset

It also plots a separate downside graph based on actual stock price.
