# Palantir (PLTR) Three-Scenario DCF Valuation

[Please find the download](https://github.com/tndntb9ym9-rgb/DCF-Palantir-Three-Scenario-Valuation/blob/main/Palantir_DCF.xlsx)

A discounted cash flow model valuing Palantir Technologies under three scenarios (Conservative, Base, Optimistic), built in Excel from 2018-2024 financial data.

**Data source:** FactSet Fundamentals

## Overview
This model projects Palantir's free cash flows and discounts them to derive an intrinsic value per share. It compares the result with the market price to test what the market is pricing in.

## Method
1. **Historical analysis:** extracted income statement and cash flow data for 2018-2024
2. **Key drivers:** calculated revenue growth, EBIT margin, tax rate, D&A, capex and net working capital as a percentage of sales
3. **Discount rate:** estimated WACC using CAPM (4.18% risk-free rate, 2.66 beta, 3.85% market risk premium), giving 14.4%
4. **Scenarios:** built Conservative, Base and Optimistic cases with different assumptions on revenue growth, margin expansion and risk
6. **Valuation:** discounted projected free cash flows to derive an intrinsic share price

Market price at the time of analysis: **$69.85**

## Key takeaway
The model values Palantir well below the market price. This gap suggests the market is pricing in AI adoption, execution and long-term growth that a traditional DCF struggles to capture. The model is best used to frame and test assumptions, not as a definitive measure of intrinsic value.


## Limitations
- Results are highly sensitive to the discount rate, terminal value assumptions and long-term growth
- The 2.66 beta produces a high WACC, which lowers the valuation
- Forecasts rely on my own assumptions and are not predictions
