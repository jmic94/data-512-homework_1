# data-512-homework_1
DATA512 Human Centered Data Science

# Homework 1: Professionalism & Reproducibility

## Goal
Pull page views of film articles using the Pageviews API. Create three data sets and three visualizations using the pulled data.

## Data Source
Wikimedia
Terms of use: https://www.mediawiki.org/wiki/API:REST_API#Terms_and_conditions

## API Documentation
Python requests module: https://pypi.org/project/requests/
Pageviews API: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews

## Input/output

Input: thank_the_academy.AUG.2023.csv.xlsx
This contains the full list of films which the project pulls page view data for.

Outputs:
- academy_monthly_mobile_201501-202310.json
    - monthly mobile page views per article (2015 to Sep 2023).
- academy_monthly_desktop_201501-202310.json
    - monthly desktop page views per article (2015 to Sep 2023).
- academy_monthly_cumulative_201501-202310.json
    - cumulative monthly page views per article for desktop and mobile (2015 to Sep 2023).
- max_min_avg.png
    - graph showing the monthly page views of the most and least viewed articles on mobile and desktop.
- top_10_peaks
    - graph showing the monthly page views of top 10 articles by peak monthly views.
- top_10_few.png
    - graph showing the monthly page views of top 10 articles by fewest months of data available.

## Notes
- The mobile page views come from mobile-app and mobile-app views, which the code pulls separately.
- The raw data from the Pageviews API are in the /intermediate folder as csv files.