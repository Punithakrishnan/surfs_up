# surfs_up
Performing data analysis and data exploration on a weather dataset,

Using SQLalchemy to query and create engine of connecting SQLite and python pandas.

Designing a Flask application to showcase a dynamic data analysis.

### Summary
Seasonal weather analysis for Oahu island based on a comparison of precipitation and temperature between June and December from 2010 to 2017 across all observation stations.

---

### Project Process:
Determine key statistical data about the month of June. 

<img width="275" alt="Screen Shot 2022-05-10 at 2 14 36 PM" src="https://user-images.githubusercontent.com/98849217/167695209-b1974cc3-a583-4814-895d-fb2b3c7fbb1e.png">

Determine key statistical data about the month of Dec.

<img width="299" alt="Screen Shot 2022-05-10 at 2 15 19 PM" src="https://user-images.githubusercontent.com/98849217/167695328-4e2b4e15-2193-4086-8a6e-9afd04ad4594.png">


---

### Compare your findings between the month of July and December.


Based on a comparison of precipitation and temperature between June and December from 2010 to 2017 across all observation stations, it’s possible to notice the following statistical information:

Over 7 years, there are 1574 precipitations occurred and 1700 temperatures observed in June, higher than 1405 precipitations and 1517 temperatures observed in December. The different (1700-1517 = 183) between two observations counts that indicate the data of Dec, 2017 not included in database.

Comparing of precipitation, the mean (0.217) and median (0.03) of December are higher than June’s mean (0.136) and median (0.02), respectively.

For precipitation derivative indicators, December also had higher Standard Deviations and Maximum precipitation. In December, standard deviation (0.541) is higher than June’s standard deviation (0.336). The minimum of both December and June are zero, and December maximum (6.42) is higher than June (4.43).

Comparing of temperatures, it apparently shows that June’s temperature indicators are higher than December.

Make variable recommendations for further analysis.
The lack of data in December, 2017 may cause less reliable of data. The database should generate more recently winter data to compare summer and winter precipitation.

In addition of statistical summery, various features and plots may help us better analyze the seasonal weather. For example, line plots would be able to provide quick and easy way to show time-varying. Histogram plots would tell us frequency of precipitation as well as temperature for both December and Jane.

For seasonal analysis, we need filter more detail precipitation and temperatures for Spring and Autumn.
