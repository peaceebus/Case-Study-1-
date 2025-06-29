# Case-Study-1
DSA Project: Amazon Product Review Analysis 

The pivot table and dashboard will be pasted via screenshot

**The following questions that require formula;**

7. How many products have a discount of 50% or more?

   ANSWER: =IF(B3 >=50%, "Yes", "No")

9. What is the total potential revenue (actual_price × rating_count) by category?

    ANSWER: =B5 * C5

10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?

    ANSWER: =IF(C4 < 200, "<200", IF(C4 <=500, "200-500", ">500"))

12.  How many products have fewer than 1,000 reviews?

    ANSWER: =COUNTIF(B4, "<1000")




