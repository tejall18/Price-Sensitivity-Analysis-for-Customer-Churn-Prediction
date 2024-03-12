# Price-Sensitivity-Analysis-for-Customer-Churn-Prediction
 Conducted in-depth analysis to identify price sensitivity factors influencing customer churn.


Key Findings & Data Augmentation Suggestions:

Insights from Client Data:

1.Consumption Patterns: Avg. annual consumption: 159,220 kWh, wide range, notable zero gas consumption.
2. Forecasting: Significant difference between average last month and forecasted consumption, indicating changing patterns.
3. Discounts and Meter Rent: Avg. forecasted energy discount: 0.97, avg. forecasted meter rent: 63.
4. Price Forecast: Varying forecasted energy prices, higher off-peak prices. Avg. forecasted power price: 43.13.
5. Customer Characteristics: Avg. slightly more than one product per customer, avg. net margin: 189.26.
6. Churn Rate: Relatively low, avg.: 9.72%, suggesting a significant portion of customers not churning.
7. Power and Consumption Limits: Avg. max power: 18.14, substantial portion with zero consumption last month.
8. Historical Information: Avg. customer tenure: Almost five years.

Insights from Pricing Data:

1. Variable Prices: Avg. off-peak variable price: 0.141, spread (SD: 0.025).
2. Fixed Prices: Avg. off-peak fixed price: 43.33, variability (SD: 5.41).
3. Price Spread: Considerable variability in variable prices, especially during peak hours.
4. Minimum Prices: Instances of zero values suggest instances of zero or no applied pricing.
5. Price Distribution: Positively skewed distribution of variable prices during off-peak hours. Instances of zero values in peak and mid-peak hours.
6. Fix vs. Variable Price Ratio: Variable ratios across periods, higher fixed prices during peak and mid-peak hours.
7. Price Fix Component: Significant contribution of fixed component, particularly during off-peak hours.
8. Price Quartiles: Relatively small interquartile range for variable prices during off-peak hours.

Data Augmentation Suggestions:

1. External Consumption Data: Incorporate regional consumption patterns for enhanced understanding.
2. Competitor Pricing Data: Obtain competitor pricing data to assess competitiveness.
3. Economic Indicators: Include economic indicators data for analyzing correlation with churn.
4. Customer Satisfaction Surveys: Conduct surveys for direct feedback on satisfaction and non-price-related churn factors.
