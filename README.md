Analysis report with regards to the Coupon acceptance ratio based on the UCI Machine Learning repository

Summary:

Here is the acceptance ratio overview 
The overall acceptance ratio is 50%
Circumstance conditions (Destination, Passenger, Time, Expiration)
o	There is a certain correlation to Destination, Time, Passenger, and Expiration
	Destination: No Urgent Place (58%), Home (36%)
	Passenger: Frends(s)
	Time: 10 AM and 2 PM are two time zones with the most significant acceptance ratio vs. 7 AM, 6 PM and 10 PM
	Expiration: 1Day is more higher acceptance ratio (58%) vs 2 hour (43%)
•	This is reasonable considering coffee shop is somewhat related to leisure activity. We need to understand a little bit more about why expiration matters. 

Environmental conditions (Whether, Temperature) 
•	There is no significant difference in acceptance ratio by these factors.
	Temperature: it looks high when higher temperature case slightly acceptance raito gets higher (53%)

Demographics (Gender, Marital Status, Has children, Education, Occupation, Income)
o	There is no significant difference in acceptance ratio by these factors in general except for Occupation and Income.
	Occupation: Among major occupations, Students had the highest acceptance ratio (63%) followed by Unemployed (54%).
	Income: The lower income side has a slight tendency to accept the coupon. less than $12.5K has (55%)
•	These two indicate that lower-income people would be affected by the coupon incentive more.

User attributes (Number of times that he/she goes to a Bar, Coffee House, Carry Away, Restaurant Less Than $20, Restaurant $20 to $50 )
o	There is no significant difference by the below factors except Coffee House
	Coffee House => 1-3 (65%), 4-8 (69%) 

Location (toCoupon_GEQ5min, toCoupon_GEQ15min, toCoupon_GEQ25min, Direction_same, Directioin_opp)
o	It does not seem to be a significant difference by this factor


