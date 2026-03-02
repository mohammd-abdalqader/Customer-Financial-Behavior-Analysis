# Customer-Financial-Behavior-Analysis
This project explores customer financial behavior by analyzing transaction data alongside demographic and credit information to understand how different customer groups manage their spending relative to their financial capacity.

The objective of this analysis is to identify spending patterns, segment customers based on financial characteristics, and evaluate how income and credit limits influence customer behavior.

Project Goals

Understand customer spending behavior

Compare spending relative to income and credit limits

Identify key financial customer segments

Detect conservative vs aggressive spending patterns

Provide interactive visual insights through a dashboard

Key Business Questions

Do higher income customers spend more?

Which customer segment contributes the most revenue?

Are some customers spending beyond their financial capacity?

How does credit availability influence spending behavior?

Which customer groups are financially conservative vs aggressive?

Data Used

This project combines multiple datasets:

Transactions Data – Customer purchases and spending records

Users Data – Demographics such as income and credit score

Cards Data – Credit limits and card information

Due to the large size of the transaction dataset, a sampled version was used for analysis.

Data Processing

Using Python (Pandas):

Cleaned transaction amount values

Converted financial fields into numeric format

Merged transaction, user, and card datasets

Aggregated spending at the customer level

Calculated behavioral financial ratios

Segmented customers by income and spending behavior

Customer Segmentation

Customers were grouped based on:

Income Level: Low, Mid, High

Spending Behavior: Conservative, Balanced, Aggressive

These were combined to create customer financial types such as:

High Income – Conservative

Mid Income – Balanced

Low Income – Aggressive

Dashboard Insights

The interactive Tableau dashboard highlights:

Revenue contribution by customer segment

Distribution of financial behavior groups

Relationship between income and spending

Credit capacity vs actual spending

Average transaction value by segment

Dashboard Link:
https://public.tableau.com/app/profile/mohammad.abd.alqader/viz/CustomerFinancialBehaviorAnalysis/Dashboard1

Tools Used

Python (Pandas)

Google Colab

Tableau

Data Source

The original dataset is not included in this repository due to file size limitations.

You can access the dataset from Kaggle:

https://www.kaggle.com/datasets/computingvictor/transactions-fraud-datasets?select=cards_data.csv

Conclusion

This project demonstrates how combining transaction data with financial capacity metrics can provide deeper insight into customer behavior. By segmenting customers into meaningful financial profiles, organizations can better understand spending patterns, identify valuable customers, and assess potential financial risks.
