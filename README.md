Link to Jupyter Notebook in Colab: https://colab.research.google.com/drive/1IfNWaa5cUaGMtQPEwfrQwVLegdagyGZ0?usp=sharing

For my independent investigation, I will be observing the Takeout coupon group and will try to determine the characteristics of passengers who accept these coupons.
Acceptance Rate: There is a 74% chance that drivers who receive a takeout coupon will accept it.

### **Destination**
People driving home are the most likely to accept a coupon for a takeout restaurant at 79%. This makes sense as buying takeout food implies the person will not eat in that immediate area and since they are already driving home, they can pickup food on the way.
Those driving to no urgent place are only a little less likely at 76%.
People driving to work are the least likely at 65%. This may be due to the fact that they do not want to be late to work by taking a detour.

### **Income**
People making less than 50k annually in income are more likely to accept a coupon for takeout, with those making $25000 - 37499 being the most common people accepting the coupon. This may be due to takeout food generally being cheaper.
One interesting observation is that those who make between 60k and 100k are among the least likely to accept a takeout coupon. However, those making 100k or more are among the most likely to accept the coupon.

## **Combination of Scenarios**

### **Takeout regular, kids in the car, married**

Additionally, those who order takeout often, such as more than once a month, have kids with them at the time of driving, and are married are more likely to accept the carryout coupon.

Logically, for those that order takout often, it would be in their best interest to accept the coupon.

Also, with a spouse and kids, it would seem this motivates acceptance of the coupon as there are people that the driver is responsible for making sure they have their meals.

### **Females older than 30**

Women older than 30 have a 61% of accepting a takeout coupon while driving. This is not a super strong indication that women older than 30 are likely to accept the coupon. Perhaps another metric can be incorporated such as income, age, and weather.

### **Regular of cheap restaurants, unemployed student, works in food service**

People who eat at cheap restaurants often, is an unemployed student, and works in food service have a 71% chance of accepting a takeout coupon. This may be due to takeout style food generally being on the cheaper end, catering towards people who prefer eating at cheaper restaurants.

### **Male and Single**

People who are male and single are around just as likely to accept the coupon than anyone else at a rate of 75%. Other people have an acceptance rate of 73%. Thus, there is no strong determination of acceptance based on the combination of gender and marital status.

## **Weather**

If the person who received the coupon is driving in sunny weather, they are considerably more likely to accept the coupon based on the high frequency of acceptance in the visualizations in the Jupyter notebook.
This may be because rainy and snowy weather motivate people to get to their destination as soon as possible and do not want to take detours which will prolong the amount of time they need to drive in bad weather.

## **Age**

In terms of age, people in their early to mid-twenties are the most common demographic likely to accept a coupon for takeout food.
Drivers in their 40's seem to be the most likely to reject the coupon but interestingly, those in their 50's seem to gravitate towards accepting the coupon.
The acceptance rate of those under 21 is very low, which may be due to the fact that a majority of these individuals may still be teenagers or even younger and are less likely to have their license to drive.

## **Next Steps** 
In terms of next steps, advertisers and businesses can utilize these observations to curate better content of the coupon and choose the optimal conditions to send these coupons to drivers.

For instance, it has been observed that people in their 20's are more likely to accept a coupon while driving. To get more acceptance of the coupons, the content of the coupon message itself may contain content more suitable for younger people to get their attention such as memes, popular slang, or collaborations with public figures that are well known to younger people.

Another use case can be determining the right time interval to send the coupons out. My observations have shown that those driving home are more likely to accept the coupon than those driving to work. On average, people drive home typically in the late afternoon to evening hours after they are done at work. This could indicate a prime time to send out these coupons to drivers.

The observation of weather also gives a very strong relationship between sunny weather and accepting the takeout coupon. Steps to improve the coupon sendout system to be dynamic according to the weather can be explored to optimize the chances of coupon acceptance.

## **Reccomendations**
There are a few reccomendations to flesh out this dataset and in turn leading to more accurate analysis of coupon acceptance characteristics.

One column that could be added for data collection are different distance ranges from the car to the establishment the coupon is involved with such as 0-5 miles, 5-10 miles, 50+ miles, etc.

This data can indicate how far people might be willing to drive to redeem their coupon.

Other more granular categories can be personal habits such as whether or not someone is vegetarian or does not drink, etc. Additionally, the coupon type can be fleshed out to be more specific whether or not a restaurant specializes in meat menu items or vegetarian items. We currently are only observing restaurants in terms of price, but the actual themes and food that the restaurants are associated with are not clearly defined.

For the coffee house and bar categories, data observing if the driver likes or is opposed to caffeine or alcohol can be collected as well. As these establishments are logically known to specialize in serving drinks with these stimulants, we can analyze if they are ok with these and whether or not they still chose to accept the coupon to bars or cafes with this knowledge.


As a general conclusion, based on these observations, a person is more likely to accept a coupon for a takeout restaurant while driving if they are in their mid to late twenties, weather is sunny, they make less than 50k in income, they regularly order takeout food every month, and they are driving home
