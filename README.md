# PyBer_Analysis


## PyBer Analysis Overview
This project seeks to understand the differences between fares, frequency of rides, and driver population based on city type (rural, suburban, urban).  The resulting charts, found in the analysis folder, display the distinct differences between city types and the potentially cascading effect on business practices and profitability within different areas.
![PyBer_fare_summary](https://user-images.githubusercontent.com/71152576/97137542-71ca1100-172c-11eb-8e8e-be69c9266f5e.png)

Final Analysis Delivers:
1. Chart of weekly fare totals by city type
2. Charts displaying statistical variation per city type for fares, drivers and number of rides
3. Scatter plot displaying avg fares versus number of riders per city type with size of data points graduated based on a given city's driver count. 
4. Pie charts displaying percentages by city type for total rides, total fares and total drivers


## Resources
- Data Sources: ride_data.csv, city_data.csv
- Software: Python 3.9.0, Jupyter Notebook
- Dependencies: matplotlib, pandas
- Assistance and detailed walk through: Columbia Data Analysis Bootcamp

## Findings
The number of drivers, rides and overall profit decreases as we move from urban to suburban and finally to rural areas in our analysis.
![Fig1](https://user-images.githubusercontent.com/71152576/97137219-ae493d00-172b-11eb-875f-0606466d03d0.png)

While smaller markets see fewer rides per week they have the highest overall fares: this may be the result of landscape differences between rural and urban areas or potentially higher rates are necessary and acceptable when there are fewer drivers. 
![Fig2](https://user-images.githubusercontent.com/71152576/97137388-1435c480-172c-11eb-8475-ff55c9b347d2.png)

![Fig6](https://user-images.githubusercontent.com/71152576/97137465-3d565500-172c-11eb-8640-f11b5a0b85f8.png)

Overall, fewer drivers in a given market directly impacts affordability.
![Fig5](https://user-images.githubusercontent.com/71152576/97137490-4f37f800-172c-11eb-8bd1-df73ac39c1b8.png)



## Recommendations
1. Growing market share beyond urban areas: begin in-market (per city type) research to understand whether a given population's lack of interest or the lack of availability (based on driver counts) is blocking growth
2. Lack of affordability: investigate length of routes and our business' supply-demand model in rural areas to gain a deeper understanding of higher fare rates being incurred outside of urban areas.
3. Encourage drivers: a large pool of drivers is the key to a given market's success for PyBer. Encouraging people to become drivers will directly impact affordability, ride frequency and overall profitability for both individual drivers and PyBer.


