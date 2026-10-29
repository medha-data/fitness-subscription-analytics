Fitness Subscription Analytics — TripleTen Sprint 7
Project Overview
This project analyzes fitness subscription transactions to understand customer behavior, forecast subscription revenue, and evaluate customer acquisition cost recovery.

Tools: Tableau Desktop, Excel, GitHub

Key Findings
1. Subscription Duration
-The most common observed subscription-payment span was 3 months among customers with no subscription payment in the dataset’s final month.
-This is an estimate of payment cessation, not confirmed cancellation, because explicit cancellation dates are unavailable.

2. Subscription Revenue Forecast
-Forecast period: January–December 2026
-Total projected subscription revenue: $3,879,041
-Forecast model quality: Good
-Annual seasonality: None detected
The forecast suggests increasing subscription revenue, although prediction uncertainty must be considered.

4. Customer Acquisition Cost Payback
Cohort          Average CAC      Revenue-Based Payback

2024             $178.10          Month 7

2025             $179.28          Not recovered by Month 12

The 2024 cohort recovered its average customer acquisition cost sooner than the 2025 cohort within the observed period.

Business Recommendations
1. Investigate early subscription inactivity and introduce retention initiatives during the first three months.
2. Monitor actual subscription revenue against the forecast each month.
3. Review acquisition spending and customer retention for the 2025 cohort to improve CAC recovery.
   
Methodology and Limitations
-Customers and transactions were related using Customer ID.
-Cohorts were defined using each customer’s first recorded transaction.
-Retention was estimated from repeat transaction activity.
-Subscription duration was measured using first and last recorded subscription-payment months.
-CAC payback was calculated using cumulative subscription revenue per original cohort customer against average cohort CAC.
-Revenue-based CAC recovery does not account for operating costs or profitability.
-The dataset lacks explicit cancellation events.
-The forecast represents modeled estimates rather than actual 2026 revenue.

Deliverables
-Tableau packaged workbook (.twbx)
-Tableau dashboard and analysis screenshots
-Data model screenshot
-Original dataset, where redistribution is permitted
# fitness-subscription-analytics
