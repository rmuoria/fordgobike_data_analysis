# Ford GoBike System Data Exploration
## byRobert Gitahi


## Dataset

The data consists of information regarding 183,411 rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset contains 18 columns and 183411 records/rows. 9 numerical, 2 string/object, 3 boolean datatypes and 2 datetime. The dataset can be downloaded from https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv

## Summary of Findings

The exploration showed that the average bike trip was around 500 seconds with most trips happening during the week and specifically Thursday and Tuesday had the highest amount of rides. Furthermore, the most popular time for these rides was at 0800hrs and 1700hrs. 

Futher exploration indicated that there was a strong relationship between the duration of the bike trips and age of the user with most users being around the age of 35. I also found out the most popular station for riders to pick up and drop off their bikes were stations 58(Market St at 10th St) and 67(San Francisco Caltrain Station 2  (Townsend St at 4th St).

Also most users of the system are subscibers approximately 90% compared to customers who make up for the rest 10%. I also found out a larger proportion of users are males account for about 75% of all genders. The males also take less time on their trips compared to the other genders. 

Finally, the bike sharing program is only made availabe for subscribers and not customers. 


## Key Insights for Presentation

For the presentation, I focus on the distribution of rides in seconds then per day and per hour. I start by introducing the trip frequency in seconds and then by days of the week, followed by hour of the day. The plots involved are seaborn countplot. 
Afterwards, I introduce the categorical variables one by one. To start, I use the boxplot plots of duration across gender. This is followed by trip distribution by user type making use of the violin plot.