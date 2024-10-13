<b>Will the Customer Accept the Coupon</b>


This is a brief report for assignment 5.1. The dataset used is the coupons.csv data that was provided with the assignment. Following were the observations and findings from the dataset using pandas and seaborn

1.	Overall acceptance rate of all coupons was 56.84%

2.	Acceptance of Bar coupons
    a.	acceptance rate of those who go more than once a month and over the age of 25 is more than twice as high as others.
    b.	Folks who go to bar frequently (more than once a month) and have no kids passenger and below the age of 30 are likely to accept the bar coupons the most ~ 70% rate

3.	Effect of Income on coupon acceptance rate
    a.	High income group (> 50K) is likely to accept coupons to high-end restaurants more than low-income group
    b.	For all other coupons, the lower income group is likely to accept them over higher income group

4.	Comparison of carryout vs coffee coupons
    a.	The acceptance rate of carryout coupons doesn't change much across frequency of visits. Folks who never visit carryout places are likely to accept the coupon with same rate as folks who visit a lot
i   b.	The acceptance rate of coffee house coupons varies a lot across frequency of visits. Folks who never visit or visit less than once a month are less likely to accept the coffee coupons compared to the folks who visit a lot.

5.	Effect of gender on coupon acceptance rate
    a.	For all coupon types, males are more likely to accept coupons compared to females.
    b.	Having a partner changes the acceptance rate. Females with partners are more likely to accept Carryout and cheap restaurant coupons compared to males

6.	Effect of age on coupon acceptance rate
    a.	Folk’s age 30 and under are more likely to accept coupons except for carryout coupons.
    b.	No impact of age to carryout coupon acceptance rate

Following visualization techniques were used to analyze the data
    -	Seaborn histplot
    -	Seaborn barplot

<b>Overall Conclusion</b>

The various metrics and charts show that there are various factors that impact the coupon acceptance rate. Frequency of visit to a particular type of place has greater impact on the coupon acceptance rate for that place. The only exception to this was carryout places where folks who never visited were equally likely to accept the coupon as the folks who visited often.
Other factors like gender, marital status and age had an impact to the acceptance rate. Males were more likely to accept the coupons but females with partners had a higher acceptance rate in some cases.  Lower age group accepted coupons more than higher age group. Carry out coupons’ acceptance was not impacted by age.

Using pandas and seaborn visualization, it is possible to correlate various metrics to get higher acceptance rate.

