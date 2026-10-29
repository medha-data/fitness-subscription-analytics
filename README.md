Fitness Subscription Analytics — TripleTen Sprint 7
Project Overview
This project analyzes fitness subscription transactions to understand customer behavior, forecast subscription revenue, and evaluate customer acquisition cost recovery.

Tools: Tableau Desktop, Excel, GitHub

Key Findings
1. Subscription Duration
-The most common observed subscription-payment span was 3 months among customers with no subscription payment in the dataset’s final month.
-This is an estimate of payment cessation, not confirmed cancellation, because explicit cancellation dates are unavailable.

### 2. Subscription Revenue Forecast
- **Forecast period:** February 2026 – January 2027
- **Total projected subscription revenue:** $2,725,062
- **First forecast month:** February 2026 — $186,694
- **Forecast length:** 12 months
- **Ignore Last:** 0 (no periods ignored)
- **Seasonality:** None detected
- **Model quality:** OK

The forecast projects increasing subscription revenue over the next 12 months. Tableau identified no recurring annual seasonal pattern. Forecast values are estimates, subject to uncertainty, and should not be interpreted as guaranteed revenue.

### 3. Customer Acquisition Cost (CAC) vs. Lifetime Revenue

Cumulative customer revenue was compared with total customer acquisition cost for the 2024 and 2025 acquisition cohorts.

| Metric | 2024 Cohort | 2025 Cohort |
|---|---:|---:|
| Customers | 2,816 | 6,484 |
| Total CAC | $501,537 | $1,162,459 |
| Break-even month | Month 4 | Month 6 |
| Cumulative revenue at break-even | $505,199 | $1,208,333 |

The 2024 cohort recovered its acquisition costs by Month 4, while the 2025 cohort reached break-even by Month 6.

**Business recommendation:** Investigate differences in early customer activity and acquisition efficiency between the two cohorts. Improving retention and repeat subscription purchases may help shorten the CAC recovery period.

**Limitation:** CAC payback is measured using cumulative recorded revenue rather than gross profit. This analysis does not account for other operating costs.
   

