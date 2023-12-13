# Analysis Report on the Coupon Acceptance Rate
Link to notebook: https://github.com/toshiokimura/5.1_Coupon/blob/main/prompt.ipynb

(): Acceptance rate

## Summary of Findings (Bar Coupon)
- Proportion of bar coupons were accepted: (41%)

  Accceptance rates for those who: <br>
- went to a bar 3 or fewer times a month to those who went more: (37%) vs. (77%) <br>
- go to a bar more than once a month and are over the age of 25 to the all others: (70%) vs. (34%) <br>
- go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry: (71%)<br>
- go to bars more than once a month, had passengers that were not a kid, and were not widowed: (71%) <br>
- go to bars more than once a month and are under the age of 30: (72%) <br>
- go to cheap restaurants more than 4 times a month and income is less than 50K: (45%) <br>

  Hypothesis: Those who go to a bar frequently will be more likely to acccept the bar coupon. <br>
<br>
<br>
<br>

## Summary of Findings (Independent Investigation: Coffee House Coupon)

The overall acceptance rate was 50% and looking at each acceptance rate by attribute, around 60%+ is relatively a high acceptance rate, and around 40%- is relatively a low acceptance rate. Refer to the bar graphs with acceptance rates in the project file for each attribute provided by the dataset. As for Circumstance, all conditions with high acceptance rates are associated with leisure or a small free time, which makes sense considering a coffee shop utilization situation. Environments are not that important factor in general and the only tendency I observed is a slightly high acceptance rate in a high-temperature case. Demographics again are not tightly related to the acceptance rate in general except for age, occupation, and income. These three factors' results indicate that lower-income people would be incentivized by coupons more. The number of times to Coffee House is highly correlated, which is quite natural. Location did not seem to have a significant influence, but it was interesting to see more about the correlation in these regards. So, I did another analysis by splitting the dataset into pure three distances and two directions and calculated the acceptance rates. It turned out that in the same direction, 5 min and 15 min distances did not affect the acceptance rate a lot, but in the opposite direction, it influenced a lot, which makes sense since users do not want to change their direction just for the coffee house as the distance gets longer. In conclusion, if we want to distribute a coffee house coupon with a high acceptance rate, it should be done in the late morning with 1-day expiration to the cars in the same direction to the coffee house. If we know personal attributes, we can also target those who are on the lower income side or who visit a coffee house more frequently.

In contrast to “Coffee House”, I also checked the situation for “Restaurant $20 to $50”. Briefly saying, we need to offer the Restaurant $20 to $50 coupons in a more stable manner (longer expiraten) or targets (Partner) in general.

<br>

### Acceptance Rate Highlights 

#### ■ Coffee House coupon: High rate vs. Low rate ###
**Circumstances (Destination, Passenger, Time, Expiraten)** <br>
There are certain differences in the acceptance rate by all these factors.
- Destination: No Urgent Place (58%) vs. Home (36%)
- Passenger: Friends(s) (60%) vs. Alone (44%)
- Time: 10 AM (64%) and 2 PM (55%) vs. 7 AM (45%), 6 PM (41%), and 10 PM (42%)
- Expiraten: 1 day (58%) vs. 2 hours (43%)

**Environments (Whether, Temperature)** <br>
There is no significant difference in acceptance rate by these factors.
- Temperature: 80F (53%) vs. 30F (44%) 

**Demographics (Gender, Age, Marital Status, Has children, Education, Occupation, Income)** <br>
There is no significant difference in acceptance rate by these factors in general except for Age, Occupation, and Income.
- Age: Below21 (70%) vs. 50Plus(42%)
- Occupation: Students (63%), Unemployed (54%) vs. Sales & Related (39%)
- Income: $12.5K- (55%) vs. 75K- (30%)

**Frequency (Bar, Coffee House, Carry Away, Restaurant Less Than $20, Restaurant $20 to $50)** <br>
There is no significant difference by these factors except for Coffee House.
- Coffee House: 1-3 (65%), 4-8 (69%) 

**Location (toCoupon_GEQ5min, toCoupon_GEQ15min, toCoupon_GEQ25min, Direction_same, Directioin_opp)** <br>
There does not seem to be a significant difference by these factors. See below graphs more about the correlation.
<br>
<br>


#### ■ Coffee House coupon vs. Restaurant $20 to $50 coupon ###
- Overall acceptance rate: 50% vs. 44%
- Passenger - highest: Friend(s) (60%) vs. Partner (63%)
- Expiraten - lowest: 2 hours (43%) vs. 2 hours (30%)
- Occupation: Students (63%), Unemployed (54%) vs. Students (44%), Unemployed (36%)
- Frequency to restaurant - highest: Coffee House 4-8 (69%) vs. Restaurant $20 to $50 gt8 (69%)
- Location: dependent vs. less dependent (See below graphs)
<br>

#### ■ Acceptance Rate Depandency to Distance and Direction

![image](https://github.com/toshiokimura/5.1_Coupon/assets/44044445/879b4f9c-2beb-41a9-beda-49c467682d89)


