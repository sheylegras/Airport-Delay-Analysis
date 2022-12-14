# **Airport Delay Analysis**
A Python based project of arrival flight delay reasons as part of CareerFoundry Data Analysis immersion course.
## **Objective**
In 2021, The United States saw over 600 million travelers through the air. When traveling by air, preflight anxiety is something that many travelers face In this analysis we will explore airline on time statistics and delay data to provide travelers with insights of their expected travel experience. 
## **Data**
The dataset for this project consist of 2020-2021 open source data on airline on time statistics and delay causes. The original data can be found [here.](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?20=E) Json of US states was provided by CareerFoundry and can be found [here.](https://coach-courses-us.s3.amazonaws.com/public/courses/data-immersion/A6/6.3/us-states.json) Time-series data used in the anlysis can be found [here.](https://data.nasdaq.com/data/EIA/STEO_ACTKFUS_M-airline-ticket-price-index-monthly) Supplemental data used to look at the historical view of % of total minutes delayed can be found [here.](https://www.bts.gov/content/delay-cause-year-percent-total-delay-minutes) Delay cause explanations can be found below. 
- Carrier: The cause of the cancellation or delay was due to circumstances within the airline's control (e.g. maintenance or crew problems, aircraft cleaning, baggage loading, fueling, etc.)
- Weather: Significant meteorological conditions (actual or forecasted) that, in the judgment of the carrier, delays or prevents the operation of a flight such as tornado, blizzard or hurricane.
- National Aviation System (NAS): Delays and cancellations attributable to the national aviation system that refer to a broad set of conditions, such as non-extreme weather conditions, airport operations, heavy traffic volume, and air traffic control.
- Late Aircraft: A previous flight with same aircraft arrived late, causing the present flight to depart late.
- Security: Delays or cancellations caused by evacuation of a terminal or concourse, re-boarding of aircraft because of security breach, inoperative screening equipment and/or long lines in excess of 29 minutes at screening areas.
## **Scripts Folder**
- 6.1 Sourcing and Cleaning Open Data
- 6.2 Exploring Relationship and Correlations
- 6.3 Geospatial Analysis
- 6.4 Supervised Machine Learning/Autoregression
- 6.5 Usupervised Machine Learnig/Kmeans clustering
- 6.6 Sourcing and Analyzing Time-series Data
- 6.7 Merging Historical Data
## **Tools**
For this project Excel, the following Python tools and libraries, and Tableau were used:
- Anaconda 3
- Jupyter Notebooks
- Pandas was used for data analysis
- Seaborn was used for visualizations
- Folium for geospatial analysis
- Sklearn for machine learning
## **Resources**
The final presentation of key findings was completed in [Tableau](https://public.tableau.com/app/profile/shey.legras/viz/AirlineDelayAnalysis_16637842402390/AirlineDelayAnalysis)
