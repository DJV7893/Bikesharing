# Bikesharing
---
## Overview:
---

We have been tasked with creating a proposal in Tableau to convince investors that a bike-sharing program in Des Moines is a solid business proposal. The proposal will focus on our analysis of New York City's bike-sharing program, CitiBike, through a set of visualizations that:
  
  * Show the length of time that bikes are checked out for all riders and genders.
  * Show the number of bike trips for all riders and genders for each hour of each day of the week.
  * Show the number of bike trips for each type of user and gender for each day of the week.

After creating these visualizations we will add them to a final presentation in the format of a Story in Tableau. Through the Story format we wil be able to effectively communicate step by step how our analysis correlates to the implementation of a sucessful bike-sharing program in Des Moines.

---
## Results:
---

Tableau Public Link: [link to dashboard](https://public.tableau.com/views/NYCCitibikeChallenge_16535798172630/NYC-DesMoinesStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) 

Visualization 1: Checkout Times for Users

<img width="1272" alt="Checkout Times for Users" src="https://user-images.githubusercontent.com/99817571/170549732-868a6779-ad16-42f0-99b2-3affa69984d6.png">

Peak checkout time for bikes last around 10 minutes and most rides end before 30 minutes.

Visualization 2: Checkout Times by Gender

<img width="1274" alt="Checkout Times by Gender" src="https://user-images.githubusercontent.com/99817571/170549813-e575a142-cad9-4f90-a6a0-1669a981d42f.png">

Male checkout of bikes is substantially larger than for females with around 110k checkouts at its peak for males and around 35k for females. Both follow the same pattern with bike checkouts peaking at 10 minutes and most rides ending before 30 minutes.

Visualization 3: Trips by Weekday per Hour

<img width="1273" alt="Trips by Weekday per Hour" src="https://user-images.githubusercontent.com/99817571/170549840-452242d2-da9c-4936-ac29-4e9497844e4d.png">

There are peak hours of bike trips in the morning (7-9 a.m.) and in the afternoon (4-7 p.m.) during the week except for Wednesday. This trend is most likely correlated to the daily commute of NYC residents to work.

Visualization 4: Trips by Gender (Weekday per Hour)

<img width="1273" alt="Trips by Gender (Weekday per Hour)" src="https://user-images.githubusercontent.com/99817571/170549879-ec0fe405-405b-45b1-81ee-1c9f1f5038ab.png">

As we can see our previous pattern of higher male bike usage is substantiated.  However, regardless of gender the pattern of peak trip hours during the Weekday remains almost enitrely the same.

Visualization 5: User Trips by Gender by Weekday

<img width="1273" alt="User Trips by Gender by Weekday" src="https://user-images.githubusercontent.com/99817571/170550002-55338406-7442-4542-b8ad-4399159b3285.png">

Among subscribers, ridership is much higher with men whereas with Customers there is no clear distinction. Subscriber bike usage is higher overall during the week than for customers.

---
## Summary:
---
Our CitiBike data analysis has provided an effective insight into the functionality of a bike-sharing program within the boundaries of a major urban setting. We were able to effectively parse out patterns of bike usage in relation to time and gender which allowed us to determine utilization rates based on time of day and location. The peak of hours for Weekday trips are correlated to commuting hours in the morning and afternoon whereas Weekend usage is evenly spread out, lacking a signifcant peak. 

In order to get a better grasp of bike utilization for Des Moines bike-sharing program we should develop further visualizations. We only have small snapshot of bike utilization in NYC with the August Data we analyzed. We need to take data from an entire year and create a visualization that shows the average peak hours over a larger period of time. Furthermore, we can create a second visualization that is subdivided by seasons of the year in order to see what are the peak hours for the summmer when there are more people outside and more tourists vs the winter months when its colder out. This will allow us to better grasp how large our bike-sharing program should be in Des Moines and how to best draw members of the community to participate in the program.

---
## Resources:
---

Data Source: 201908-citibike-tripdata.csv

Software: Jupyter Notebook, Tableau Public
