

# Citi Bike Tableau Analysis.

### Purpose



The purpose of this analysis is to provide insight into the effectiveness of the New York City Citi Bike program in order to gather support for the implementation of a similar program in Des Moines, Iowa. 



[Link to Dashboard](https://public.tableau.com/views/CitiBikeAnalysis_16032271376310/NYCCitiBikeStory?:language=en&:display_count=y&:origin=viz_share_link)



### Results

Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.

##### Overall Trip Characteristics

![](Resources\trips_by_weekday_hour.PNG)

The initial visualization, Trips by Weekday per Hour displays how trips are concentrated during each day of the week. It shows that most trips occur during the commuting hours of the weekdays, so Monday - Friday, in the 8am hour and the 5-7 pm hours. 



![overall_trip_duration](Resources\overall_trip_duration.png)

The next visualization shows the average trip duration throughout each hour of the day and the number of bikes 'checked out' during that hour. We can also drill down to look at a few hours more closely.



![drill_down_duration](Resources\drill_down_duration.PNG)

With this view it is easier to see the variation of trip duration in each hour. 



![cutsomer_types](Resources\cutsomer_types.PNG)

The pie chart above shows the proportion of trips taken by subscribers vs. non-subscribing customers. As would be expected, most trips are taken by subscribers. However, this isn't as powerful as it could be because the data is completely de-identified. Subscriptions very likely *do* outnumber individual customers, but it isn't clear without some sort of rider id. 



#### Gender Breakdown of Trips 

![gender](Resources\gender.PNG)

This chart shows the relative proportions of each gender among Citi Bike users. Users comprise of about 65% males, 25% women, and 10% unknown.



![trips_by_gender_weekday_hour](Resources\trips_by_gender_weekday_hour.PNG)

This chart is analogous to the first chart displaying the trips per hour of the weekday, but is  additionally broken down by gender. I excluded the "unkown" gender category, as the amount of data was very small compared to the other two options and didn't provide any additional information. Here, you can see that the same trends of commuting hours hold true, but many more trips are taken by men when compared to women. This is somewhat intuitive based on the proportion of all users belonging to each gender category. 



![duration_by_gender](Resources\duration_by_gender.PNG)

This chart displays the overall trip duration broken down by gender. As above, orange represents males, blue for females, and red for unknown. In general, this information displays the same trends as the overall trip duration chart, but does follow the expectations set by the user gender breakdown. 

#### User Type Breakdown

The user type breakdown includes two charts that we have seen before:

![gender_and_types](Resources\gender_and_types.png)

These are included as a reference for the additional chart added below, which also looks a bit familiar. 



![user_type_gender_weekday](Resources\user_type_gender_weekday.PNG)

This chart displays the daily usage rates of the Citi Bike service, broken down by day of the week, customer type, and gender. Again, the unknown gender category was excluded due to size. Basically, this chart shows a compilation of most of what was already determined above regarding gender and daily usage. However, it shows one additional interesting trend: the differences in utilization between customers and subscribers. Subscribers show the highest utilization during the weekdays (Monday through Friday), whereas Customers show higher utilization on the weekends (Saturday and Sunday). This indicates a major motivator for subscription: the commute. 



### Summary

In summary, the data shows that users are more likely to be male subscribers to the service. Based on time and usage data, these appear to be commuters, using the Citi Bike system for their work related local travel. Compared to Subscribers, the Customers utilize the bike system more on the weekends, indicating a possibility that this group is largely comprised of tourists, visitors, and others who utilize the bikes for leisure purposes. 



This data calls for additional research into the utilization purpose differences (and thus marketing plans) for customers and subscribers. Some additional visualizations that may be helpful would include: 

1. An additional heat map comparing user types by weekday per hour, and
2. An additional trip duration visualization comparing the average length of trips to the start time. 



