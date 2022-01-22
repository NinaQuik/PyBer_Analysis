# PyBer_Analysis
Module 5 - Pandas and Matplotlib using Jupyter Notebook

## Overview of Project
A fictional company called "PyBer" is exploring the relationship between type of city (Urban, Suburban, Rural) and ride sharing data such as number of rides, drivers and amount of fares.  Using Pandas and Matplotlib libraries, this project visualizes the ride share data across the three city types.  This analysis purportedly will be used to address disparities among the city types so that management can make improvements to ridesharing in underserved neighborhoods.

## Analysis 
### Results
Combining two .csv files containing ride data and city information, a DataFrame is created to summarize the differences in ride-sharing data among Urban, Suburban, and Rural city types.
![Summary Overview](/analysis/PyBer_summary_df.png)
From the sampled data, one can see that:
- There were 2375 total rides.  Urban (1625) account for 68.4% of rides, Suburban rides (625) make up 26.3%, and Rural rides (125) are 5.3% of all rides.

  ![Rides By Type](/analysis/Fig6.png)
  
- There were 2973 total drivers.  Urban drivers (2405) make up 80.9% of all drivers, Suburban (490) account for 16.5% of drivers, and rural drivers make up the remaining 2.6%

  ![Drivers By Type](/analysis/Fig7.png)
- The total amount of fares for this sample is $63,538.64. Urban fares ($39,854.38) account for 62.7% of all fares, Suburban ($19,356.33) are 30.5%, Rural ($4327.93) the remaining 6.8%.

  ![Fares By Type](/analysis/Fig5.png)

The following chart shows Total Fare by City Type from Jan. 1 2019 to April 27, 2019

  ![Fares By City_Time](/analysis/PyBer_fare_summary.png)
  
- The Average Fare per Ride is highest for Rural ride shares at $34.62.  Suburban fares average $30.97 and Urban fares are generally around $24.53.
- Similarly, Average Fare per Driver is highest for Rural Drivers at $55.49.  Suburban drivers average $39.50, while urban drivers earn on average $16.57.

 ![Bubble Chart Fares vs Size](/analysis/Fig1.png)

