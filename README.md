Fitness Subscription Analytics: Key Insights

This repository contains an analysis of customer cohorts, revenue forecasting, and unit economics (CAC vs. LTV) for a fitness subscription business.

1. Customer Cohort Analysis

Business Question: After how many months do customers typically cancel their subscriptions?
 
Based on the cohort retention table, the highest volume of cancellations occurs within the first 3 months of a customer's lifecycle.
• Initial Drop-off: Across all cohorts (e.g., January 2024, June 2024, December 2024), there is a significant drop in active customers from Month 0 to Month 1 and another substantial drop from Month 1 to Month 2.
• Stabilization: By Month 4 or 5, the churn rate begins to flatten out. For example, the January 2024 cohort drops from 156 to 74 users by Month 4, but then only gradually declines to 57 users by Month 11.
• Conclusion: The critical retention period is the first 90 days. Customers who remain past Month 3 are significantly more likely to stay long-term.

2. Revenue Forecast
 
Business Question: What is the expected subscription revenue over the next 12 months? Does the revenue forecast show evidence of seasonality?
• Forecast: The revenue forecast chart shows a strong, non-linear upward trend. The historical data shows steady growth from late 2023 through 2025. The model projects that this growth will accelerate, with the 12-month forward-looking revenue rising steeply, potentially crossing the 1,400K mark by the end of 2026.
• Seasonality: No, there is no strong evidence of seasonality. The revenue curve is smooth and consistently upward-trending without the distinct peaks and valleys (e.g., summer slumps or New Year spikes) that typically characterize seasonal fitness businesses. The growth appears to be driven by consistent customer acquisition and compounding subscription revenue rather than cyclical demand. 

3. CAC vs. LTV
 
Business Question: How long does it take for the 2024 and 2025 cohorts to recover their customer acquisition cost?
 
Based on the CAC vs. LTV, we look for the "break-even point" where the cumulative LTV (Running Sum of Revenue) equals or exceeds the CAC (indicated by the horizontal line at 1,663,996).
• 2024 Cohorts: The cumulative revenue curve rises steadily. It takes roughly 9 to 11 months for the cohorts to break even against the assumed CAC baseline. The curve crosses the 1.6M threshold around the August 2025 data point, indicating that the early 2024 cohorts took nearly a year to fully recover their acquisition costs.
• 2025 Cohorts: For later cohorts (late 2024 and 2025), the cumulative revenue curve accelerates much faster. The slope becomes steeper, suggesting that recent cohorts are recovering their CAC in a shorter timeframe (likely 6 to 8 months) due to either higher initial spend or better retention in the early months compared to earlier cohorts.
