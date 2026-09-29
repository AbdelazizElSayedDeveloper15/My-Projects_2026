# My-Projects_2026
I'll be posting my projects that I 've completed whether in the university or after graduation from university
# Sales Data Analysis & Visualisation

Exploratory analysis of a retail sales dataset (9,800 orders, 18 columns, 2015-2018) using Python, Pandas and Matplotlib.

**Dataset:** [train.CSV] - [https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting]

## Business questions
1. Which categories and sub-categories drive the most sales?
2. Which region underperforms?
3. How did sales change from 2015 to 2018, and is there seasonality?
4. Which customer segment brings the most revenue?

## Data cleaning
- Converted order and ship dates (day/month/year) to datetime
- Checked for duplicates (was found and cleaned up)
- Handled 11 missing postal codes [What I did was as follows I used the command df.isnull() .sum()]
- Added a Year column for trend analysis

## Key findings
- [Finding 1:The most sold category out of all the categories is the Technology Category by = 800,000]
- [Finding 2:As we understood from the previous chart that the most sold sub category out 10 which is Phones by = 300,000]
- [Finding 3:The monthly sales trend as shown in the above figure is the time = 01/2019]

## Charts
![Sales by category](Sales by category.png)
![Monthly trend](chart3_monthly.png)

## Tools
Python, Pandas, Matplotlib, Google Colab

## Limitations
The dataset has no profit column, so the analysis covers sales only.
