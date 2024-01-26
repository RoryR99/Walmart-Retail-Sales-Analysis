# Walmart-Retail-Sales-Analysis

## Description

Walmart, a leading US retail store, aimed to enhance sales and demand prediction accuracy, particularly during events and holidays that impact daily sales. With available sales data from 45 Walmart stores, the challenge was to address unforeseen demands and stockouts caused by suboptimal machine learning algorithms. The ideal machine learning model would accurately predict demand, considering factors such as economic conditions (CPI, Unemployment Index) and promotional markdown events associated with major holidays like Super Bowl, Labour Day, Thanksgiving, and Christmas.

## Dataset Description

The historical sales data spanned from 2010-02-05 to 2012-11-01, available in the file Walmart_Store_sales. Key fields in the dataset included:

- Store: Store number
- Date: Sales week
- Weekly_Sales: Sales for the given store
- Holiday_Flag: 1 – Holiday week, 0 – Non-holiday week
- Temperature: Temperature on the day of sale
- Fuel_Price: Cost of fuel in the region
- CPI: Prevailing consumer price index
- Unemployment: Prevailing unemployment rate

## Holiday Events

- Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
- Labour Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
- Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
- Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13

## Analysis Tasks

### Basic Statistics Tasks
- Identified the store with maximum sales.
- Determined the store/s with maximum standard deviation (sales variability) and calculated the coefficient of mean to standard deviation.
- Identified stores with a good quarterly growth rate in Q3’2012.
- Identified holidays with higher sales than the mean sales in the non-holiday season for all stores together.
- Provided a monthly and semester view of sales in units and offered insights.

### Statistical Model

For Store 1:
- Built prediction models using Linear Regression to forecast demand.
- Utilized variables like date, restructuring dates as 1 for 5 Feb 2010.
- Hypothesized the impact of CPI, unemployment, and fuel price on sales.
- Changed dates into days by creating a new variable.
- Selected the model that provided the best accuracy.
