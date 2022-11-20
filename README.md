# (Ford GoBike System Dataset Exploration )
## by (Paul Wainaina)


## Dataset

    This dataset consists of information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

    There are 183412 Ford GoBike ride records. The original dataset consists of 16 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip).

    I did data cleaning to change the data types to the correct ones

    Some columns (member_birth_year, member_gender) had missing values so I dropped records with missing values. Using the 'member_birth_year' feature I generated a new feature for age of the users in 2019. The maximum age was 141 which is likely to be an incorrect entry because at most people live up to 120 years. Also, it's less likely that somebody above 90 years can ride a bike, therefore I excluded records with age above 90.

    After the data wrangling I remained with 174875 records which I used to to do the data analysis.

## Summary of Findings

1. My findings are as below and I intend to show them in the presentation:

2. Customer user type trip durations are longer compared to subscriber user type.
3. The average trip duration is 704.002744 seconds.
4. Most of the users are of ages between 20 - 40 years.
5. The younger people between the ages of 20 - 50 years have more long duration bike rides than those above 60.
6. The mean age of those who bike share across the different genders is lower than those who don't bike share.
7. There are more subscribers with ages below 70 and with low bike durations compared to customers.


## Key Insights for Presentation

1. Most users ride the bikes for about 250 - 750 seconds. The average trip duration is 704.002744 seconds.
2. The younger people between the ages of 20 - 50 years have more long duration bike rides than those above 60.
3. The mean age of those who bike share across the different genders is lower than those who don't bike share.
4. There are more subscribers with ages below 70 and with low bike durations compared to customers.


```python

```
