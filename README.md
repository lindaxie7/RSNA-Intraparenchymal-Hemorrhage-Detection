# RSNA-Intraparenchymal-Hemorrhage-Detection

[Data Preprocessing Code](https://github.com/lindaxie7/NYC-CitiBike-Analysis/blob/main/NYC_CitiBike_Challenge_starter_code.ipynb)

## Overview of Project
Create a rapid, cloud-based, deployable ML method to detect ICH potentially across the hospital enterprise to help patients and clinical teams, create scientific and intellectual independence from 3rd party vendors!


### The data we are working with:
https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection



## Results
- Checkout Times for Users, we can see that most people check out the bikes for less than 20 minutes, and the peak duration is about 10 minutes. Visualization:
https://public.tableau.com/app/profile/linda6647/viz/CreatetheCheckoutTimesforUsersViz/Sheet1?publish=yes

- Checkout Times by Gender, we can see that the bikes checked out by male are more often, and more than by female, the check out duration by male is usually less than an hour, there are more bikes checked out by female are more than 1 hour. Visualization:
https://public.tableau.com/app/profile/linda6647/viz/CreatetheCheckoutTimesbyGenderViz/Sheet1?publish=yes


- Trips by Weekday for Each Hour, we can see that Thursday 8:00AM, Thursday 5:00PM, Thursday 6:00PM are the bikes checked out peak hours. And Wednesday is the least popular day for checking out the citi bikes. Visualization:
https://public.tableau.com/app/profile/linda6647/viz/CreatetheTripsbyWeekdayforEachHourViz/Sheet1?publish=yes


- Trips by Gender (Weekday per Hour), we can see that female user check out citi bikes are more often on Thursdays, male user check out citi bikes are more often on Monday, Tuesday afternoon between 5:00 to 6:00 PM, and also Thursday morning 8:00AM, Thursday afternoon 5:00PM to 6:00PM. Visualization:
https://public.tableau.com/app/profile/linda6647/viz/CreatetheTripsbyGenderWeekdayperHourViz/Sheet1?publish=yes


- Trips by Gender by Weekday, we can see that the bikes checked out are mostly by subscribers. Visualization:
https://public.tableau.com/app/profile/linda6647/viz/CreatetheUserTripsbyGenderbyWeekdayViz/Sheet1?publish=yes


- Top biking start locations,Visualization:
https://public.tableau.com/app/profile/linda6647/viz/TopBikeStationsintheCityforStartingaJourney/Story1?publish=yes

- Most popular end stations,Visualization:
https://public.tableau.com/app/profile/linda6647/viz/TheTopBikeStationsforEndingaJourney/Sheet1?publish=yes



## Summary
Is the ride on a weekday or weekend? 
Weekday, is rush-hour commute for the most part and probably from home to work. Weekend could be a longer, more casual ride and have higher variability.

Is the ride in the morning, afternoon, evening, or night?
Most likely in the evening 5:00PM to 6:00PM. The exact timing will be based on the difference in trip duration based on time of day. 

Is the user a customer or a subscribes?
Most likely a subscribe. 

Two additional visualizations suggestion for future analysis:
- We could include average duration for each trip based on: Trip and User Type. 

- We could also inclue What season is the most popular season for using citi bikes?
December — Feb. = Winter
March — May = Spring
June — Aug. = Summer
Sept. — Nov. = Fall
