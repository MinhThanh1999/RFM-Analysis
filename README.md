# RFM-Analysis
Use Python to analyze customer segments to gain insights for the company

## Dataset:
We have two relational tables: the first table contains customer information and the second table contains RFM classification.

## Method:
- Clean the customer table, then categorize every CustomerID by three feature scores: R, F, and M.
- Combine the three feature scores in the following order: R, F, and M into the RFM Score column.
- Merge the cleaned table with the RFM classification by RFM score to get the Customer Segment.
- Visualize the distribution of each RFM classification to gain insights.

## Insights:
- If we look at the visualization, we will see that among the 11 different categories, the Champions segment has the largest quantity in customer segments and accounts for more than half of the company’s revenue (62.89%).
- The next segment that contributes the second most to revenue is Loyal Customers, with 11.2% of the company’s revenue.
⇒ These groups are both loyal customers, so we need to focus on customer service and provide personalized promotions to encourage them to buy more and increase their referrals to friends and family.

- The Promising and Can’t Lose Them segments are the two types of customers with the smallest quantity in customer segments but have high spending per order. We need some promotions to keep them buying and to convert them into loyal customers.
- Besides that, we should keep an eye on the Hibernating segment because they have a large quantity, just below the Champions segment. They used to buy our products often but have had no activity recently. This indicates that the company may have some issues, possibly with product quality or customer service, which we need to address soon.
⇒ Recommendation: Gather their feedback and understand what they want the company to improve.

- Other segments do not contribute much to revenue but should be analyzed to understand what causes them to buy less and less often. Is it due to alternative products or competitors? If it is from competitors, what are the different and attractive aspects, such as price, variety of models, etc.?
