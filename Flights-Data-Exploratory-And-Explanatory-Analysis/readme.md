# Project: Flights Data Analysis 
## by Andrea Claudia Villanca Rosales 


## Dataset
> 
The investigation explored the U.S.DOT dataset of 2007 flights in the United States. This dataset provides information about airline on-time performance and flight delays. It covers nonstop scheduled-service flights between points within the United States (including territories) reported by 21 carriers. The dataset can be found in the
 Harvard repository [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7), 
with feature documentation available [here](https://www.transtats.bts.gov). The original data was assessed and cleaned to solve 8 quality issues. Also, 4 features were engineered to deepen the analysis.  There are 7,275,259 flights in the cleaned dataset with 13 features.


## Summary of Findings
> 
- The "delayed" variable is a Boolean, with an unbalance towards the negative (not delayed). This was not a surprise because most airlines report time-related KPIs to the aviation authorities and airports in order to keep their operations. 
- The amount of delayed flights is always lower than the amount of not delayed flights throughout the months. This pattern mostly remains even when analyzing it on a multivariate level by scheduled arrival hour, day of month, day of week or weekday/weekend.
- There is a spike in the percent of delays per hour between 9 PM and 0 AM (inclusive), and a notable reduction in the percent of delays at 7 AM. This annual pattern also remains on a multivariate level through most of the months.
- The percent of delayed flights per day of week hits its lowest on Saturday. This annual pattern also remains on a multivariate level through most of the months.
- The percent of delayed flights per is similar for both weekdays and weekends, however, the percentage of delayed flights is slightly higher on weekdays. This annual pattern also remains on a multivariate level through most of the months.


## Key Insights for Presentation
> 
- For the presentation, we decided to focus on the time-related factors, like Month, Day of Month, Day of Week, Weekday/Weekend and Scheduled Arrival Hour, and their relationship with Flight Delays. First, we plotted the Distribution of Delayed Flights in a bar chart with absolute counts, but with a percent tag above each bar to showcase relative frequency, as well. Then, we plotted a stacked bar chart of the Delayed Flights through the months for a bivariate level, and for a multivariate level by scheduled arrival hour, day of month, day of week or weekday/weekend, we used facetted unstacked bar charts.  Afterwards, we plotted the Annual Percentage of Flights per hour (showcasing the lowest and highest values), day of week and weekday/weekend. We kept the same colors blue for delayed flights and gray for not delayed flights through the  bivariate and multivariate plots to ease the understanding. Also, ticks and axes were renamed or removed to ease the understanding of the graphs.


## Resources
>
The resources used for the exploratory and explanatory analysis are detailed in each of the Jupyter Notebooks.
