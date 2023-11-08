# coupon-acceptance
Analysis of UCI Machine Learning repository data for acceptance of coupons among drivers

This project includes an exploration of data concerning coupon acceptance rates for drivers 
in different scenarios and across different categories. The analysis explores the impact of 
coupon type, patronage frequency, distance to an establishment, time of day, coupon 
expiration, and income of recipient. 

We find that the coupon campaign is most successful for coupons for (1) carry out orders and 
(2) restaurants that cost less than $20. Campaigns for both of these types are robust to both 
the frequency of patronage and the time of day, achieving acceptance rates upwards of 70% 
across subcategories. When only 1-day coupons are considered for these categories, 
extremely strong acceptance rates of 80-90% are achieved. 

There is more variability in acceptance rates for the other coupon types, viz. (3) restuarants 
$20-50, (4) coffee houses, and (5) bars. Here, too, one-day coupons have higher success rates 
in almost all circumstances. Still, even when only one-day coupons are considered, 
acceptance rates are generally in the 40-60% range for these categories. 

Further analysis of the data for category (3) indicates that there are sub-cohorts of coupon 
recipients with higher acceptance rates. For instance, those who usually patronize this type 
of establishment more than once a month are have higher acceptance rates than other 
participants. When only this cohort is considered, recipients are about 80% likely to accept 
coupons for establishments less than 15 minutes away, a significant improvement. This finding 
illustrates that, even in coupon categories where overall acceptance is lower, a targeted 
campaign may enjoy high success rates and generate customer traffic. 

On the basis of this analysis, we recommend coupon campaigns for carry out and cheaper 
(<$20 per person) restaurants, where 1-day coupons have extremely high use rates. For other 
coupon categories, more targeted analyses, like the one indicated above, are necessary to 
optimize campaigns. 
