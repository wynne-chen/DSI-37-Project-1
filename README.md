---
meta:
    author: Wynne Chen
    topic: Pandas, Folium, Singapore, Climate, Food Delivery
---

# DSI Project 1

This is Project 1 for General Assembly DSI 37, by Wynne Chen

## Problem Statement

A cheap venture capitalist firm is interested in trying to disrupt the food delivery market in Singapore. However, they're concerned about global warming, changing weather, and the possible implications on consumer habits. Since they aren't willing to pay for data sets until they get some proof of concept, I've been forced to work with the free datasets available. The main topics of study are whether the food delivery market is still growing, and whether the weather affects online food delivery.

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|total_rainfall|float|rainfall-monthly-total|Total monthly rainfall in mm| 
|no_of_rainy_days|int|rainfall-number|Total number of days with rainfall amount of 0.2mm or more per month| 
|mean_sunshine_hrs|float|sunshine|Mean number of hours of sunshine per month| 
|mean_temp|float|surface-air-temp|Mean monthly surface air temperature in celsius| 
|online_fnb_expenditure|float|food-online & food-total*|Value of online food & beverage sales in million dollars| 
|offline_fnb_expenditure|float|food-online & food-total*|Value of offline food & beverage sales in million dollars| 

*\*Values were calculated based on the two datasets named. The calculations are shown in Part 2 section C.*

## Summary of Analysis

In total, 6 main data sets were cleaned, merged, and studied: total rainfall in mm per month, total number of rainfall days per month, mean sunshine hours per month, mean surface air temperature per month, online food and beverage expenditure, and offline food and beverage expenditure. 

On top of that, additional qualitative research was done on the size and market share breakdown of the food delivery market in singapore.

Lastly, the coordinates of Grab Delivery partners and some shopping malls in the Changi region were mapped onto Singapore for visualisation purposes.

## Conclusions and Recommendations

There seems to be a trend showing that Singaporeans are more likely to order food in when it is raining. However, the trend is not as strong as intuition might suggest, which is probably due to the fact that the weather data sets all pertain to just one region of Singapore (Changi). It is recommended that more weather sets be analysed in future studies.

On first glance, Grab has very comprehensive coverage of Changi, so a different neighbourhood might be a better target. Alternatively, the Grab Food partners shown might be persuaded to change vendors if you can provide sufficient incentives. 
Further studies should expand the data sets studied, and could consider other factors such as demographic, type of housing, income, number of working adults per household, availability of public transport, etc.)The Grab eateries data could also be analysed further to study whether there are any other gaps in the market, for e.g. in terms of cost or delivery radii. 

Ultimately, while the food delivery market appears to be robust and thriving, much more work must be done if a new contender wants to break into it, considering that even highly established players like Foodpanda and Deliveroo are lagging behind Grab so significantly.

## Sources

Background Research
https://www.statista.com/outlook/dmo/online-food-delivery/singapore#revenue
https://www.channelnewsasia.com/singapore/food-delivery-grab-deliveroo-foodpanda-industry-analysts-consolidation-3412766

Data Sets
https://data.gov.sg/dataset/rainfall-monthly-number-of-rain-days
https://data.gov.sg/dataset/rainfall-monthly-total
https://data.gov.sg/dataset/surface-air-temperature-mean-daily-minimum
https://data.gov.sg/dataset/sunshine-duration-monthly-mean-daily-duration
https://www.kaggle.com/datasets/polartech/16000-grab-restaurants-in-singapore
https://tablebuilder.singstat.gov.sg/table/TS/M601751
https://tablebuilder.singstat.gov.sg/table/TS/M602001
