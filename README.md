# Surfs_Up

## Overview of the Analysis
The purpose of this analysis was to determine the temperature statitics for the month of June and December in the region of Oahu, Hawaii in order to predict if purchasing a surf shop is sustainable as a year-round business. 

## Results
![Screen Shot 2022-10-25 at 10 40 03 AM](https://user-images.githubusercontent.com/111692952/197804423-893bd235-46e1-4d60-b9f9-92e0656e7082.png)
![Screen Shot 2022-10-25 at 10 39 43 AM](https://user-images.githubusercontent.com/111692952/197804438-da4a03f1-1ae2-440c-9486-ee9db4e4c157.png)
- The average temperature for June is about 75 F while the average temperature for December is about 71 F
- The minimum temperature for June is 64 F while the minimum temperature for December is 56 F
- The maximum temperature for June is 85 F while the maximum temperature for December is 83 F

## Summary
- The temperature profile is a good starting indicator for determining whether an outdoor surf shop is sustainable year round. 
From the temperature statistics, it can be concluded that the range in the avergae temperature is small showing a healthy sign of a year round businest. The minimum and maximum temperature are also in a good range which allows customers to choose whether they prefer warmer or cooler conditions for optimal surfing. 
- Another indicator is a precipitation profile, for the high demand months of June and Decmeber, it would good to write queries and determine the amount of rainfall in those months. From those results, we can get a better understanding of the weather conditions in the area. 
- session.query(Measurement.date, Measurement.prcp).filter(extract('month',Measurement.date)==6).all()
- session.query(Measurement.date, Measurement.prcp).filter(extract('month',Measurement.date)==12).all()
