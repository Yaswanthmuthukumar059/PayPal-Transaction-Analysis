# PayPal Transaction Analysis
A data analysis project exploring retail transaction trends, with a focus on PayPal usage, for a PayPal internship application.

## Overview
- **Dataset**: Retail transactions (100,000 rows) from Kaggle, including PaymentMethod (Cash, Credit Card, Debit Card, PayPal).
- **Tools**: Python (pandas, matplotlib, seaborn, plotly) in Google Colab.
- **Objective**: Analyze transaction volume and PayPal’s performance in a retail context.

## Key Insights
- PayPal holds a 25.1% transaction share in this retail dataset.
- Busiest day: Thursday ($3.60M in sales).
- PayPal peaks at 5 PM ($283K), suggesting after-work online shopping.
- Opportunity: PayPal’s avg transaction ($248.13) trails Debit Card ($249.21)—target higher-value purchases.
- Seasonal peaks in December/January (~$2.13M each) reflect holiday shopping.

## Visuals
- **Daily Volume**: `daily_volume.png`
- **Monthly Trend**: `monthly_volume.png`
- **Payment Distribution**: `payment_dist.png`
- **Avg Amount by Payment**: `avg_amount_payment.png`
- **PayPal Hourly Trend**: `paypal_hourly.html` (interactive)

## Files
- `.ipynb`: Full code and analysis.
- `.png`: Static visualizations.
- `.html`: Interactive PayPal hourly plot(Download to view the chart).
- `insights.txt`: Summary of findings.
