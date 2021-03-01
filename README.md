# bikesharing by Ketaki
## Overview of the analysis:
This project analyzes the CitiBike data from New York City for the year 2019 to understand if bike sharing is a good idea for other cities such as Des Moines. For this purpose, we have used Tableau and highlighted the details using a Tableau Story.
[Link to Dashboard](https://public.tableau.com/views/NY_CitiBike_Challenge/NYCCitibikeAnalysis?:language=en&:display_count=y&publish=yes&:origin=viz_share_link)

## Results: 
Here are the resuts from some of the visualizations we performed on the NY CitiBike dataset.
1. Bike Usage by Gender ![](https://github.com/ketpradh/bikesharing/blob/main/Resources/Bike%20Usage%20by%20Gender.PNG) We find that the overall bike usage is the highest for Male Users(~65%), followed by Female Users(~25%) and Unknown Gender Users(~9.6%).
2. Peak Hours for August Usage ![](https://github.com/ketpradh/bikesharing/blob/main/Resources/August%20Peak%20Hours.PNG) August being a popular time in NYC, the bike usage(number of rides) in August was calculated in terms of usage in peak hours(in local NY time). It was found that the usage is the higher during early mornings(8AM-9AM) and in the evenings from 4PM-7PM, with having the highest number of rides(224,566) being at 5 PM. This is probably as these are work commute hours.
### To check how long a bike is checked out for by a user, the next two visualizations were performed.
3. Checkout times for Users ![](https://github.com/ketpradh/bikesharing/blob/main/Resources/Checkout%20Time%20for%20Users.PNG)  It was found that most bike were checked out for **under 1 hour** and peaked at 5 minutes. The datas suggests that very few users use the bike for a longer duration.
4. Checkout Times by Gender ![](https://github.com/ketpradh/bikesharing/blob/main/Resources/Checkout%20Times%20by%20Gender.PNG) Using similar parameters for 3., it was seen that the checkout times were higher for male users than female and unknown gender users. The most popular longest checkout times were as follows- Males(5 minutes), Females(5 minutes), Unknown(11-24 minutes).
### The next two visualizations help to find Bike Usage during the week.
5. Trips by Weekdays per Hour 
- ![](https://github.com/ketpradh/bikesharing/blob/main/Resources/Trips%20by%20Weekday%20per%20Hour.PNG) 
- Bike Trips were found to be the highest during Monday through Friday around 8 AM and between 5-6 PM which are the popular work commute times. For the weekend, the bike trips were highest between 10 AM - 7 PM, throughout the day time, suggesting tourist usage.
6. Trips by Gender(Weekday per Hour) 
- ![](https://github.com/ketpradh/bikesharing/blob/main/Resources/Trips%20by%20Gender(Weekday%20per%20Hour).PNG) 
- Performing similar analysis like 5., we broke down trips by gender and found that trips by male users were higher during Monday to Friday(peaked at ~30k) compared to the weekend(peaked at ~15k). Trips made by Female users were higher during Monday to Friday(peaked at ~11k) than the weekends(peaked at ~9k), however not significantly higher. The number of trips were actually higher for Unknown gender users during the weekend(peaked at ~5k) compared to weekdays(peaked at ~2.9k).
7. User Trips by Gender by Weekday 
- ![](https://github.com/ketpradh/bikesharing/blob/main/Resources/User%20Trips%20by%20Gender%20by%20Weekday.PNG) 
- Depending on the type of users, which are customers or subscribers, we found that:
  - Overall subscribers account for the most number of rides than customers and is usually highest during Monday-Friday. 
  - Male Subscribers have the highest number of trips during the weekdays, than any other gender. 
## Summary: 
- Based on the given dataset and our analysis, bike sharing is a good option for any city, including Des Moines. The number of rides indicate it is a popular mode of transport in cities such as NYC, throughout the week. 
- Our overall analysis suggests that Male users and office goers are the key target users, especially during the work week(Monday-Friday) and work commute hours. Weekend bike usage is popular as well, suggesting tourist usage.
Suggestions -
- Two other visualizations could be to understand more about the user base.
1. Bike Usage by users based on birth year - Are younger or older users more likely to use the bike sharing feature?
2. Type of customer based on birth year - Are younger or older users more likely to become a subscriber?

