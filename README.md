# PyBer Analysis

## Overview of PyBer Analysis
PyBer executives requested an exploratory analysis of rideshare data to help inform future business practices. Visualizations were requested to showcase the relationship between the type of city (i.e. urban, suburban, and rural), the number of riders, and the number of drivers. Results will guide PyBer in efforts to improve access to ride sharing services and determine affordability for underserved neighborhoods.
## PyBer Analysis Results
- Analysis showed large disparities between city types over the course of the quarterly period (Fig 1).


    <Figcaption><i>Fig 1. PyBer Ride Sharing Data</i></Figcaption>

![Fig 1. PyBer Ride Sharing Data](https://github.com/InRegards2Pluto/PyBer_Analysis/blob/a7592015695a4f36068f74bc70739af195ed18be/analysis/Fig1.png)


- Across the 3 city types, urban types overwhemingly have the highest total number of rides, drivers, and fares.
- Subsequent sections delve deeper into differences in ride-sharing data among the different city types. Ride-sharing analysis results include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.

### Rides by City Type
- PyBer provided 2,375 total rides over the course of the analysis period.
- Urban types made up 68.4% of total rides. Suburban types comprised 26.3% and rural types covered the remaining 5.3% of total rides (Fig 1).


    <Figcaption><i>Fig 2. % Total Rides by City Type</i></Figcaption>

![Fig 2. % Total Rides by City Type](https://github.com/InRegards2Pluto/PyBer_Analysis/blob/a7592015695a4f36068f74bc70739af195ed18be/analysis/Fig6.png)

### Drivers by City Type
- A total of 2,973 PyBer drivers were registered during the analysis period.
- Urban types made up 80.9% of all PyBer drivers. Suburban types comprised 16.5% and rural types covered the remaining 2.6% (Fig 2).


    <Figcaption><i>Fig 3. % Total Drivers by City Type</i></Figcaption>

![Fig 3. % Total Drivers by City Type](https://github.com/InRegards2Pluto/PyBer_Analysis/blob/a7592015695a4f36068f74bc70739af195ed18be/analysis/Fig7.png)

### Fares by City Type
- PyBer collected a total of $63,538.64 in fares during the analysis period.
- Urban types made up 62.7% of total fares. Suburban types comprised 30.5% and rural types covered the remaining 6.8% of total fares (Fig 3).


    <Figcaption><i>Fig 4. % Total Fares by City Type</i></Figcaption>

![Fig 4. % Total Fares by City Type](https://github.com/InRegards2Pluto/PyBer_Analysis/blob/a7592015695a4f36068f74bc70739af195ed18be/analysis/Fig5.png)

### Average Fare per Rider/Driver 
- The average fare per rider/driver by city type listed in Table 1. Script and dataframes used to calculate summary data can be found in the [jupyter notebook for the project](https://github.com/InRegards2Pluto/PyBer_Analysis/blob/a7592015695a4f36068f74bc70739af195ed18be/PyBer_Challenge.ipynb).


    <Tablecaption><i>Table 1. PyBer Data Summary</i></Tablecaption>

| Type  | Total Rides | Total Drivers | Total Fare | Average Fare per Ride | Average Fare per Driver
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Rural | 125 | 78 | $4,327.93 | $34.62 | $55.49 |
| Suburban | 625 | 490 | $19,356.33 | $30.97 | $39.50 |
| Urban | 1,625 | 2,405 | $39,854.38 | $24.53 | $16.57 |

- In a reversal of the trend for other metrics, urban areas ranked the lowest both in terms of average fare per ride and average fair per driver. Suburban areas ranked second and rural areas had the highest average fare per ride and average fair per driver.
  - Rural and suburban areas having higher average fare rates isn't surprising given geographic considerations. Urban areas are highly clustered together, so the time and distance needed to get between locations is much closer. Conversely, rural and suburban residents typically need to travel longer distances to reach amenities such as grocery stores and medical offices. As a result, it's expected that the average cost per trip would be higher.
### Total Weekly Fare by City Type

- Total fare earning were divided into weekly bins using resampling methods. - Comparing city types by total weekly earnings shows that urban environments not only top earning rankings on a quartly basis, but on a weekly basis as well (Fig 4).
- By comparison, weekly total fares for suburban city types were roughly half that of urban. Weekly fare for rural cities tended to be less than a 1/10th of weekly fares for urban cities. 


    <Figcaption><i>Fig 5. Total Weekly Fare by City Type</i></Figcaption>

![Fig 5. Total Weekly Fare by City Type](https://github.com/InRegards2Pluto/PyBer_Analysis/blob/a7592015695a4f36068f74bc70739af195ed18be/analysis/PyBer_fare_summary.png)
## PyBer Analysis Summary
- Based on the analysis results, the CEO should consider the following recommendations to address disparities among cities:
  - 1) <b><i>Offer incentives to drivers in rural and suburban areas.</i></b>
    - Data indicates that urban areas have a surplus of drivers relative to the number of rides requested. There were 2405 PyBer drivers registered in urban environments, but only 1625 ride requested in those areas. Conversely, suburban areas had 490 registered drivers and 625 ride requests. Rural areas had 78 registered drivers and 625 ride requests. Potential incentives could include a reimbursement for mileage or vehicle wear and tear.
  - 2) <b><i>Offer incentives to rural residents to use PyBer.</i></b>
    - While suburban ride requests tended to be half those of urban ride requests, rural ride request were only 1/10th the number of ride requests in urban environments. While the average population of different city types should be considered, data indicates that both accessability and affordability are limited in rural environments. Promotions such as free rides for first time users could aid in increasing accessibility to rural populations. However, it's important that such promotions be sponsered on a corporate level so that rural drivers can still be credited and paid for such rides.
  - 3) <b><i>Offer seasonal incentives to increase drivers during peak periods.</i></b>
    - Analysis of total weekly fares by city type show that ridership peaks at various time points over the course of the quarterly period. Offering promotions to increase available drivers during these periods could help meet ridership demand and accessibility needs. Additionally, further data should be obtained to better understand underlying contributers to peak ridership periods. For example, all 3 city types experienced a spike in ridership in late February. Obtaining data on events that may have happened at the time (e.g. a major sport event or holiday) could help predict when ridership may peak during other quarters.


## Resources
- Data Source: 
  - [city_data.csv](https://github.com/InRegards2Pluto/PyBer_Analysis/blob/a7592015695a4f36068f74bc70739af195ed18be/Resources/city_data.csv)
  - [ride_data.csv](https://github.com/InRegards2Pluto/PyBer_Analysis/blob/a7592015695a4f36068f74bc70739af195ed18be/Resources/ride_data.csv)
- Analysis Script: 
  - [PyBer_Challenge.ipynb](https://github.com/InRegards2Pluto/PyBer_Analysis/blob/a7592015695a4f36068f74bc70739af195ed18be/PyBer_Challenge.ipynb) (Figs 1-4) 
  - [PyBer_Challenge.ipynb](https://github.com/InRegards2Pluto/PyBer_Analysis/blob/a7592015695a4f36068f74bc70739af195ed18be/PyBer.ipynb) (Figs 5 and Table 1)
- Software: Jupyter Notebook
