# DATA512Assignment1

Describe the goal of the project.
List the license of the source data and a link to the Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions
Link to all relevant API documentation
Clearly name any intermediary data files and any final output files that your code creates. And for any files that your code creates you should describe the values of all fields.
List any known issues or special considerations with the data that would be useful for another researcher to know. 

The aim of this project is to collect and analyze page view data of multiple academy award winning movies on English Wikipedia between the months of July 2015 and October 2023

## Files:
- Assignment 1.ipynb: Jupyter notebook with code pertaining to acquisition of the data, using the PageViews API to collect data for the movies of interest.
- Assignment 1 Visualization.ipynb: Jupyter notebook with code pertaining to preprocessing, visualization and analysis of the data collected.
- Fewest Months of Data.png: Graph visualizing the top 10 movies with fewest months of data.
- Maximum Average and Minimum Average.png: Graph visualizing the top and bottom 10 movies with minimum and maximum average monthly views.
- Top 10 Peak Views.png: Graph visualizing the time series data of the top 10 movies with highest page views.

- academy_monthly_cumulative_201507-202310.json: Intermediate data with cumulative counts of desktop and mobile pageview data between July 2015 and October 2023.
- academy_monthly_desktop_201507-202310.json: Intermediate data with counts of desktop pageview data between July 2015 and October 2023.
- academy_monthly_mobile_201507-202310.json: Intermediate data with counts of mobile pageview data between July 2015 and October 2023.
- thank_the_academy.AUG.2023.csv.xlsx: Initial dataset with names and URLs of academy award winning movies of interest

## Data source:
[PageViews API](https://wikimedia.org/api/rest_v1/#/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end)