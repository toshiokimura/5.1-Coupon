# Analysis Report on the Coupon Acceptance Ratio 
## Summary of Findings (Coffee House Coupon)

The overall acceptance ratio was 50% and looking at each acceptance ratio by attribute, around 60%+ is relatively a high acceptance ratio, and around 40%- is relatively a low acceptance ratio. Refer to the bar graphs with acceptance ratios in the project file for each attribute provided by the dataset. As for Circumstance, all conditions with high acceptance ratios are associated with leisure or having a small free time, which makes sense considering a coffee shop utilization situation. Environments are not that important factor in general and the only tendency I observed is a slightly high acceptance ratio in a high-temperature case. Demographics again are not tightly related to the acceptance ratio in general except for occupation and income. These two factors indicate that lower-income people would be incentivized by coupons more. The number of times to Coffee House is highly correlated, which is quite natural. Location does not seem to have a significant influence, but it was interesting to see more about the correlation in these regards. So, I did another analysis by splitting the dataset into pure three distances and two directions and calculated the acceptance ratios. It turned out that in the same direction, 5 min and 15 min distances did not affect the acceptance ratio a lot, but in the opposite direction, it influenced a lot, which makes sense since users do not want to change their direction just for the coffee house as the distance gets longer. In conclusion, if we want to distribute a coffee house coupon with a high acceptance ratio, it should be done in the late morning with 1-day expiration to the cars in the same direction to the coffee house. If we know personal attributes, we can also target those who are on the lower income side or who visit a coffee house more frequently.

In contrast to “Coffee House”, I also checked the situation for “Restaurant $20 to $50”. Briefly saying, we need to offer the Restaurant $20 to $50 coupons in a more stable manner (longer expiration) or targets (Partner) in general.




### Acceptance ratio overviews and highlights with high and low acceptance ratio conditions 
(): Acceptance ratio

** Coffee House coupon **
Circumstances (Destination, Passenger, Time, Expiration)

There are certain differences in the acceptance ratio by all these factors

- Destination: No Urgent Place (58%) vs. Home (36%)
- Passenger: Friends(s) (60%) vs. Alone (44%)
- Time: 10 AM (64%) and 2 PM (55%) vs. 7 AM (45%), 6 PM (41%), and 10 PM (42%)
- Expiration: 1 day (58%) vs. 2 hours (43%)

Environments (Whether, Temperature) 

There is no significant difference in acceptance ratio by these factors

- Temperature: 80F (53%) vs. 30F (44%) 

Demographics (Gender, Marital Status, Has children, Education, Occupation, Income)

There is no significant difference in acceptance ratio by these factors in general except for Occupation and Income.

- Occupation: Students (63%), Unemployed (54%) vs. Sales & Related (39%)
- Income: $12.5K- (55%) vs. 75K- (30%)

Frequency (Bar, Coffee House, Carry Away, Restaurant Less Than $20, Restaurant $20 to $50 )
There is no significant difference by these factors except for Coffee House
- Coffee House => 1-3 (65%), 4-8 (69%) 

Location (toCoupon_GEQ5min, toCoupon_GEQ15min, toCoupon_GEQ25min, Direction_same, Directioin_opp)

There does not seem to be a significant difference by these factors

Interesting to see more about the correlation in these regards.



** Coffee House coupon vs. Restaurant $20 to $50 **
- Overall acceptance ratio: 50% vs. 44%
- Passenger - highest: Friend(s) (60%) vs. Partner (63%)
- Expiration - lowest: 2 hours (43%) vs. 2 hours (30%)
- Occupation: Students (63%), Unemployed (54%) vs. Students (44%), Unemployed (36%)
- Frequency to restaurant - highest: Coffee House 4-8 (69%) vs. Restaurant $20 to $50 gt8 (69%)
- Location: dependent vs. less dependent (See below graphs)
<br>
<br>
![image](https://github.com/toshiokimura/5.1_Coupon/assets/44044445/db349a6c-6083-4722-bb93-c63ba4c95fbc)

