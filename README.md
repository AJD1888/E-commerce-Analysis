# E-commerce Sales & Customer Analytics 

## Project Overview 

This project analyses e-commerce sales and customer data to investigate purchasing behaviour, profitablity, makreting performance, and customer experience. Using Python and pandas, the aim is to idenitfy meaningful patterns in the data and develop evidence-based recommendations to support business decision making.

## Research Questions

1. How does purchasing behaviour and profitablity differ between repated and non-repeat customers?
2. How are discount levels associated with sales peformance and profit margins? 
3. How do sales and profitability vary acorss marketing channels and campaigns? 
4. What relationships exist between deilvery performance, returns, customer ratings, and profitablity? 

## Inital Findings 

Firstly, I aimed to compare returning customers with first time customers. Four metrics were used to compare the two customer groups:

- Total profit ($): $75953655.03 for returning customers vs $192740.73 for first time customers 
- Average profit per sale ($): $551.26 for returning customers vs 577.07 for first time customers 
- Profit margin (%): 43.0% for returning customers vs 44.3% for first time customers 
- Average profit per customer ($): $3,090.44 for returning customers vs $577.07 for first time customers 

The findings suggest that first-time customers generate slightly higher profit margins and average profit per sale, while returning customers contribute substantially more profit overall. It is important to note that this dataset contains a much larger number of returning customers comapared to non returning customers, hence the massive difference in total profits generated. However, with the average profit per customer being approximately five times higher, this does suggest that repeat purchasing plays a crucial roles in driving profits for the business.

To investigate customer behaviour, two other metrics were looked at. These were the following:

- Average Order Frequency Per Customer: Returning customers had a significantly higher average order frequency per customer, which was 5.61 compared to just 1.0 for first-time customers.
- Average Order Value : The average order value of first-time customers was $1303.76, which was slightly higher than the $1282.45 for returning customers.

These findings suggest that while returning customers will clearly have a much higher purchasing frequency as they are coming back to the business to make another purchase, on average, first time customers tend to spend slightly more on one individual order.

Moving on to the second research question, pearsons correlation was used to investigate the relationship between the discount amount and net sales/profit margin. Starting with discount amount and net sales, these two variables had a correlation coefficient of 0.53, suggesting a moderately positive relationship. This was the visualised with a scatter plot, which shows that despite some unusually large observations of net sales for lower discount amounts and a large cluster between discount amounts 0 - 4000, increasing the discount amount tends to be associated with higher net sales.

Furthermore, the correlation coefficient was then calculated for discount amount and profit margin percentage. This returned a value of -0.6, and again a scatter plot was used to visualise the realtionship. The scatter plot supports this finding, with higher discount amoints generally being associated with lower profit margins. However, ther is considerable variation across orders, as factors such as order size could also contribute to the observed pattern.

It is important to note in both cases that the relationships do not establish that discounts alone cause higher net sales and lower profit margins. 
 