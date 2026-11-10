# Customer Sales MIS Report – Electronics Retail | Excel

An MIS report that turns a raw, error-prone customer sales sheet into a clean dashboard: **49 electronics orders, Jan–Aug 2026, 10 cities in North India**.

## Build
- **Data Quality** sheet: live COUNTIF checks on the raw data, with the fix applied for each issue
- **Clean Data** with helper columns for month and age band, and a cleaning note on every changed row
- **Dashboard**: KPI cards, five summary tables (SUMIFS / COUNTIFS), five charts and findings written as formulas
- **PDF report** with charts, tables, data-quality log and recommendations

## Data cleaning
- A header row pasted over a customer record, and two rows reusing other customers' IDs with mismatched emails and decimal ages: orders kept, IDs re-keyed, details flagged
- "N/A" and blank gender, age and city values marked Not recorded
- An AI-function error cell, broken pivot sheets and broken references removed
- Phone numbers and emails replaced with Present / Missing flags for privacy

## Key findings
- Total sales **₹2.63 lakh** from 49 orders; average order value **₹5,377**
- **April** is the peak month: ₹90,887 (34.5% of sales)
- **Faridabad** leads cities (19.6%); **Monitors** lead products by value, **Headphones** by orders
- **12 orders of ₹9,999+ make up 61.5% of sales**
- 7 of 49 records (14%) needed cleaning

## Files
- `Customer_Sales_MIS_Report.xlsx`
- `Customer_Sales_MIS_Report.pdf`

## Tools
MS Excel (SUMIFS, COUNTIFS, COUNTIF, data cleaning, charts) · PDF report

## Note
Sample practice data; order values do not always match the product, so findings describe this dataset only.

## Author
**Aditya Kushwaha** · [LinkedIn](https://www.linkedin.com/in/aditya-kushwaha16)
