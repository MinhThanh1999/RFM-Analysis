# RFM-Analysis
Use Python to analyze customer segments to get insights for company

## DATASET:
    we have 2 relational tables with 1st table about customer information and 2nd table about RFM classification.
    
## METHOD:
    - Clean customer table then categorize every CustomerID  by 3 features score: R-F-M
    - put 3 features score together by following order: R-F-M into RFM Score column
    - merge the cleaned table with RFM classification by RFM score to get Customer Segment
    - visualize distribution each RFM classification to get insights:
    
## INSIGHTS:
    - if we look into the visualization we will see that 11 different categories show Champions segment has the largest quantity in customer segments and accounts for more than half of the company’s revenue **(62,89%).**
    - the next segment has 2nd contribution to revenue, which is Loyal Customers with 11,2% in the company’s revenue
    ⇒ These groups are both loyal customers so we need to focus on customer service and have some personalize promotions to make them buy more and increase references from them to their friends and family.
    
    - Promising and Can’t Lose Them Segment are the 2 types of customers who have the smallest quantity in customer segments but have high spending per order. We need some promotion to keep them buying and become loyal customers.
    - Besides that, we should keep an eye on the Hibernating Segment because they have large quantity just below the Champions segment, they used to buy our product often but they have had no activity recently. That means the company has some problems, maybe from product quality or customer service not very well so we have to figure it out soon.
    ⇒ Recommendation: take their feedback and what they want the company to improve.
    
    - Other segments, do not contribute much in revenue but should be concerned about what makes them buy less and not often. Is it from alternative products or competitors? If it from competitors what are the different and attractive things, such as price, variety of models,.…
