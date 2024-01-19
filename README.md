# CS210-PROJECT

In this project I analyzed my step count, distance, basal and active energy data that I got from Apple Health.

First of all, I have created dataframes to observe the relations between months and step count, distance, basal energy and active energy data by scraping .xml file that consists of various data. Then I merged step count and distance dataframes as well as basal energy and active energy dataframes to examine the relations between data more clearly. 

Then, I set an interval on "Date" data not to observe all time data but only to observe yearly data. The interval is from 01.10.2022 to 01.10-2023. Then I masked dataframes accordingly.

After that, I checked if there are any missing values or not. Then, I printed the statistics of the dataframes.

Moreover, I visualized the relations between the data and months by using matplotlib. 

After the visualization, I started to train a model that predicts my average step count in a month. In order to achive that, I first prepared dataframes to train and test the model. In addition to that, I also tuned parameters to make the model predict accurately. Then, I created a decision tree. The trained model has about 85% accuracy rate. 

