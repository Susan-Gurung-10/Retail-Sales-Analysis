# Retail Sales Analysis
Exploratory analysis of 1,000 retail transactions in Python (pandas + matplotlib): data validation, headline KPIs, revenue by product category and the monthly revenue trend.

## Business Questions with Answers

**1. What is the total revenue?**
Total revenue is **456,000** from 1,000 transactions, an average of 456.00 per transaction.

**2. Which product category performs best?**
**Electronics** leads with 156,905 (34.4% of revenue), but Clothing is almost level at 155,580 (34.1%). The gap is only 1,325, or 0.3% of total revenue, so the two are effectively tied.

**3. How do sales change month by month?**
Monthly revenue moves between about 23,600 and 53,200 with no steady upward or downward trend. May 2023 is the peak (53,150 from 105 transactions), followed by October (46,580), December (44,690) and February (44,060). September is the lowest full month (23,620 from 65 transactions). January 2024 contains only one day of data, so it is excluded from this comparison.

**4. Which product category has the lowest sales?**
**Beauty**, with 143,515 (31.5% of revenue). That is 13,390 behind Electronics, or about 3% of total revenue, so the difference is small.

**5. Which actions could improve business performance?**
See Recommendations below.

## Recommendations

These are suggestions to test, not conclusions proven by the data.

1. **Investigate the weakest months, especially September.** September had both fewer transactions (65 vs 105 in May) and a lower value per transaction (about 363 vs 506). Check what differed, such as promotions, stock levels or the calendar.
2. **Learn from May.** Identify what drove its volume and higher basket value, then test whether it can be repeated in slower months.
3. **Test a Beauty promotion on a small scale.** Beauty trails by only about 3% of revenue, so a low-cost test such as bundling with other categories is more sensible than a large investment.
4. **Collect richer data.** Product-level data, promotion dates, repeat-customer identifiers and multiple years would allow product-level, retention and seasonality questions to be answered.
5. **Analyse customer segments.** Age and gender are in the dataset but not yet analysed. Revenue by segment could guide targeting.

## Dataset

[Download Retail Sales Dataset](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)

**Dataset file:** `retail_sales_dataset.csv`

## Tools Used
- Python(Pandas, Numpy)
- Data Visualization(Matplotlib, Seaborn)
- Jupyter Notebook

## Contact
[LinkdIn](https://www.linkedin.com/in/susangurung10)

