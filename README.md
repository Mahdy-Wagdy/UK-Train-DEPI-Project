# UK National Railway DEPI Project

## Overview
This project is an interactive Power BI dashboard designed to analyze the performance of the UK National Railway from January to April 2024. It provides insights into passenger usage, sales performance, route analysis, and cancellation/delay trends. The dashboard offers a user-friendly interface to explore journey patterns, revenue metrics, and service reliability for National Rail.

## Features
- **Passenger Usage Analysis:** Tracks journey trends, peak travel times, and passenger demographics.
- **Sales Performance:** Analyzes net revenue (£703K), refunds (£39K), and ticket type distribution.
- **Route Analysis:** Identifies top-performing and underperforming routes by revenue and journey volume.
- **Cancellation & Delay Insights:** Examines cancellation rates (4%), delay reasons, and their financial impact.
- **Data Visualizations:** Includes line graphs, bar charts, pie charts, and tables for interactive analysis.
- **Filters:** Allows filtering by AM/PM periods and weekdays/weekends for deeper insights.

## Screenshots
### Dashboard Pages
- **Passenger Usage:** Visualizes journey trends and peak travel times. ![Passenger Usage](https://github.com/Mahdy-Wagdy/UK-Train-DEPI-Project/blob/main/SCREENSHOT/Passenger%20Usage.png)
- **Sales Performance:** Displays revenue trends and ticket type breakdown. ![Sales Performance](https://github.com/Mahdy-Wagdy/UK-Train-DEPI-Project/blob/main/SCREENSHOT/Preformance%20Analysis.png)
- **Route Analysis:** Highlights top and bottom routes by revenue. ![Route Analysis](https://github.com/Mahdy-Wagdy/UK-Train-DEPI-Project/blob/main/SCREENSHOT/Rout%20Analysis.png)
- **Cancelled & Delayed:** Shows cancellation/delay trends and reasons. ![Cancelled & Delayed](https://github.com/Mahdy-Wagdy/UK-Train-DEPI-Project/blob/main/SCREENSHOT/Cancelled%26%20Delayed.png)

## Tools Used
- **Power BI:** For data visualization and dashboard creation.
- **Power Query:** data cleaning and transformation. 
- **DAX(Data Analysis Expressions):** For creating calculated measures. 
- **Data Sources:** Excel/CSV (`railway.csv`).



## Insights
- **Journey Trends:** Total journeys were 31,653, with a 4.36% decrease from January (7,636) to February (7,212). April saw 7,712 journeys.
- **Peak Travel Times:** Busiest periods are 6 AM to 9 AM and 4 PM to 7 PM, with peaks at 6:30 AM (1,337 journeys) and 6:45 PM (2,300 journeys).
- **Passenger Demographics:** 66% of passengers do not use a rail card; among holders, the Adult rail card is most popular (16%).
- **Ticket Sales:** Standard class tickets dominate (90%), with Advance tickets being the most common.
- **Revenue Performance:** Net revenue peaked at £188K in January, dropped 20% to £151K in February, and recovered to £185K in March (total £703K). Advance ticket revenue increased by 40% in February to £294K.
- **Service Reliability:** Of 19,871 planned services, 18,019 were on-time (81% revenue, £570K), 1,062 delayed (£101K), and 790 cancelled (£33K). Cancellation rate: 4%.
- **Delays and Refunds:** Weather caused the most delays (927) with 0% refunds; technical issues (268 delays) had a 67% refund rate. Shorter delays (≤1 minute) had a 76% refund rate, while delays >60 minutes had 0%.

## Recommendations
Based on the analysis, the following recommendations are proposed to improve service reliability and customer satisfaction:

### Refund Policy Adjustments
To address inefficiencies in the current refund system:
- No refunds for delays less than 15 minutes.
- 25% refund for delays between 15-30 minutes.
- 50% refund for delays between 30-60 minutes.
- 100% refund for delays over 60 minutes.

### Reduce Cancellations and Delays
To tackle the primary causes of service disruptions:
- Invest in signal system upgrades and preventive maintenance to reduce failures, the top cause of cancellations.
- Improve staff scheduling and training to address staffing-related disruptions.
- Implement weather-resilient infrastructure (e.g., track heating, drainage systems) to handle seasonal disruptions.




