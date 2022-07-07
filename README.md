# surfs_up

# Project Overview

This project is to review the weather data stored in Sqlite in order to make a decision whether or not opening up a Surf n' Shake shop in Oahu, that the shop will sell surf boards and ice cream throughout the year. 

For this project, we will use sqlachemy to connect, make queries to the sqlite database and pull the information we need to do the weather analysis.

# Resources

- Data: Hawaii.sqlite

- Software: Jupyter notebook, sqlachemy, pandas

# Results

Firstly we explore the preciptation data by viewing weather data of one year from the last date, which is from 20160823-20170823. The stat table shows that the average was 17.6% based on 2021 observations, which means Oahu was mostly sunny throughout the year and the preciptation level is acceptable.

![prec stats](https://github.com/ivorfanning/surfs_up/blob/main/pic/20160823-20170823%20prec%20stats.png)

![prec bar chart](https://github.com/ivorfanning/surfs_up/blob/main/pic/20160823-20170823%20prec.png)

Secondly, we pulled all the weather stations and use a station of USC 00519281 that has the most observations to review the temperature for the same above time period. Then we calculated the average temperature of the last year was 72F, the lowest temperature is 54F and the highest is 85F.

![stations](https://github.com/ivorfanning/surfs_up/blob/main/pic/20160823-20170823%20stations.png)

![temps](https://github.com/ivorfanning/surfs_up/blob/main/pic/20160823-20170823%20temps.png)

As per the investors request, we pulled all the June and December temperatures recored in the dataset regardless of year, the stat shows: 
1. The average temperatures are around 70F
2. Similar min or max temperature in June and December.
3. The standard deviation is 3.xx, meaning the temperature did not fluctuated dramaticly throughout the year.

![june temps](https://github.com/ivorfanning/surfs_up/blob/main/pic/june%20stats.png)

![december temps](https://github.com/ivorfanning/surfs_up/blob/main/pic/december%20stats.png)

# Summary

The temperature in Oahu is relatively stable throughout the year and the chance of preciptation is low. Therefore, investing in Surf n' Shake shop is a good idea at Oahu.
