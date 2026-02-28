# Integrated-Financial-Model
---

Overview
---
This model presents an integrated three-statement financial forecasting framework built on structured, assumed historical financial data designed to simulate realistic corporate financial performance. The dataset does not represent an actual company but is constructed to reflect reasonable operating and financial behavior. Projections are driven by defined assumptions across revenue growth, margins, working capital, capital expenditure, and capital structure, enabling structured multi-year forecasting while maintaining full integration between the Income Statement, Balance Sheet, and Cash Flow Statement. The framework allows key drivers to be adjusted to evaluate alternative financial outcomes under different operating assumptions.


Objective
---

The objective of this model is to translate clearly defined operating and financial assumptions into structured multi-year projections, showing how changes in growth rates, margins, and capital requirements affect profitability, balance sheet composition, and cash flow outcomes within an integrated framework.


## Structure
---
• Assumed Historical Data – Built a structured historical base to extract stable ratios and operating relationships for forecasting.
• Assumptions Framework – Centralized key drivers such as growth rate, margin ratios, working capital days, and capital turnover to control projections.
• Income Statement Projection – Revenue forecast using assumed growth, with historical ratios reapplied to maintain cost and profitability structure.
• Balance Sheet Projection – Assets and liabilities scaled using efficiency ratios and working capital metrics linked directly to revenue and COGS.
• Cash Flow Statement – Indirect method derived from projected net income and balance sheet movements.
• Validation Check – Ensured Assets = Liabilities + Equity across all forecast periods.


Methodology
---
The model applies a ratio-driven forecasting approach derived from a historical numbers:
• Gross Profit Margin
Gross Profit Margin = Gross Profit / Sales Revenue
Reason: Determines profitability efficiency relative to revenue.

• SG&A Ratio
SG&A Ratio = SG&A Expense / Sales Revenue
Reason: Captures operating cost intensity relative to scale.

• Depreciation Ratio
Depreciation Ratio = Depreciation / Sales Revenue
Reason: Measures asset consumption relative to revenue base.

• Interest Ratio
Interest Ratio = Interest Expense / Long-Term Liabilities
Reason: Reflects cost of debt structure.

• Tax Ratio
Tax Ratio = Tax / Profit Before Tax
Reason: Identifies effective tax burden.

Working Capital & Efficiency Ratios

• Capital Turnover Ratio
Capital Turnover = Sales Revenue / PPE (or Operating Assets)
Reason: Measures asset utilization efficiency.

• Receivables Days
Receivables Days = (Accounts Receivable / Sales Revenue) × 365
Reason: Converts revenue relationship into collection cycle.

• Inventory Days
Inventory Days = (Inventory / Cost of Sales) × 365
Reason: Measures inventory holding period relative to COGS.

• Payables Days
Payables Days = (Accounts Payable / Cost of Sales) × 365
Reason: Measures supplier credit cycle.

Forecasting Application

Safe assumption values were selected using:
• Historical averages
• Stable trend observation
• Industry-aligned conservative benchmarks

Revenue was projected as:
Revenueₜ = Revenueₜ₋₁ × (1 + Assumed Growth Rate)

Historical data → Ratio extraction → Assumption selection → Revenue forecast → Reapplication of ratios → Integrated projection.


Conclusion
---
This framework applies with a 10% annual revenue growth assumption, the model projects sales forward and applies a 62% gross margin, 20% SG&A, and 10% depreciation intensity to determine operating profitability. Interest is calculated at 3% of long-term debt and tax at 30% of profit before tax, translating operating performance into net income. Working capital balances are derived using receivable, inventory, and payable days, while total assets scale through capital turnover assumptions. These linked drivers flow through all three statements, ensuring that growth, efficiency, and financing assumptions collectively shape profitability, liquidity, and capital structure across forecast periods.
