# PyBer_Analysis

## Overview of the analysis:
The goal is to perform an analysis where we will create several types of charts using Python, Pandas, Jupyter notebook, and Matplotlib to showcase different relationships. Ultimately the goal is to improve access to ride-sharing services and determine affordability for underserved neighborhoods. Toward the end of the project V. Isualize ask that Python and Pandas be used to create a summary Data Frame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. 

## Results:
![alt text](https://github.com/kwporras/PyBer_Analysis/blob/6fcdc66395276434e91e8e08afbb87790e0f89da/analysis/summary_dataframe.PNG)
![alt text](https://github.com/kwporras/PyBer_Analysis/blob/6fcdc66395276434e91e8e08afbb87790e0f89da/analysis/PyBer_fare_summary.png)

### Ride-sharing data differences 
  - Rural and Suburban cities have more rides than drivers as opposed to Urban cities where drivers outnumber the rides.
  - Total fares have a negative correlation with average fare per ride, and average fare per driver.
 
## Summary:
Consider increasing the number of drivers available in rural and suburban city types. In general, it seems that the more drivers that are available the more total riders or volume base of customers are realized. Though there will surely be a limit to how staff should be increase based on population, there is concern that since there are more total rides than drivers in rural and suburban areas, some people may be choosing to drive simply because there are no drivers available. Additionally, the average fare per ride is highest in rural and suburban areas. This could mean that customers are taking longer trips on average. Not only does compound the unavailable driver issue, but it also suggestion potential higher charges creating an economic barrier causing customers to reconsider taking a trip with Pyber. With increase in drivers and perhaps special discounted trip hours, the number of total riders per month may increase. Consider doing more researching into the mount of distance traveled per ride. Lastly, a belter approach may be to focus on specific cities by population and type not only general city. Further analysis on population sizes would help clarify the amount of ride and driver potential per city type.


##### Resources
- Data Source: clean_students_complete.csv, missing_grades.csv, schools_complete.csv, students_complete.csv
- Software: Python 3.7.10, Conda 4.10.3, Jupyter-notebook 6.3.0
