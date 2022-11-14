# Data Analytics Project - 201902 FORD-GO-BIKE DATASET EXPLORATION
## by Ighoruemuse, Omojevwe Rachael


## Dataset

> This dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in 2019. This was the third project in Data Analyst Nanodegree program from Udacity. The dataset is taken from  https://www.google.com/url?q=https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv&sa=D&source=editors&ust=1667826703295531&usg=AOvVaw0ovuezs5TVb52yy_0-kTFL


## Summary of Findings

The following were figured out in the three different analysis given
> Univariate Analysis

* The users used the biking system for a wide range of trip duration, and after cleaning the trip duration data and removing the outliers, we have found that the major trips had a trip duration on average of 7-12 mins.

* The duration_min data were not showing a proper distribution while plotting them on a linear scale, hence the logarithmic scale in order to show proper distribution.

* The work days were the most days that the users use the bike share system especially Thursdays for this study.

* The peak hours for the users were from 7-9am and from 4-6pm and the hours are closely matching with the regular start and end working hours. This might be related to the time when employees and students go to and leave work and school. This is was also consistent with the distribution of trips over weekdays, where work days have the most demand for trips.

* The males were almost 3 times the female users, the most age range is 20-40 which belonged to the most active population either at work or studying. the subscribers are more than 9 times the customers. Customers represent 9.35% of users, whereas subscribers represents 90.65%. Males represent 74.62% of users, whereas Females represents 23.30%, the remainder is others with 2.07%

> Bivariate Analysis
* For the duration_min vs the member age, from age 20 to 40, the duration of major trips was ranging between 2 mins to 30 mins and the trip duration range is narrowing as the age increased, this is obviously described with the duration_min vs age on the log scale as it looks like a horizontal cone which tends to narrow as the age of the member increased.

* For the rush hour of the of the day vs the user type, the rush hours for both user types are 5 P.M and 8 A.M and those two rush hours are matching with the rush hours of whole dataset which was investigated at the univariate visualization earlier but obviously the number of trips for subscriber users at those two hours are larger than same two hours for the customer users.

* There are way more subscribers than customers. Subscribers usage seem to be very consistent and standard, their usage is intended for daily routine such as work or study. Therfore subscribers usage reaches its highest levels during rush hours and work days. Customers on the other hand tend to use bikes for fun, their usage is concentrated during weekends at midnights and middays

> Multivariate Analysis
* The subscribers have been using the bikeshare system for longer duration and also covering higher age range which is an indication of long relationship between the clients and the bikeshare company.


## Key Insights for Presentation

> This project has two parts that demonstrates the importance and value of data visualization techniques in the data analysis process. In the first part, Python visualization libraries were used to systematically explore the selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, a short presentation was produced that illustrates interesting properties, trends, and relationships that were discovered in the selected dataset. The primary method of conveying the findings was through transforming the exploratory visualizations from the first part into polished, explanatory visualizations.