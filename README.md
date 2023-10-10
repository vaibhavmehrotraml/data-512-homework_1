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
[PageViews API](https://wikimedia.org/api/rest_v1/#/Pageviews_data/ get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end), a public API developed and maintained by the Wikimedia Foundation.

This data is gathered under Wikipedia’s Creative Commons Attribution Share-Alike license.

## License

MIT License

Copyright (c) 2023 Vaibhav Mehrotra

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.