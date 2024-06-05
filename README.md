![hospitality-trends](https://github.com/PoojaShylaja/Hospitality_Domain/assets/101803358/285ed87e-41f2-452a-8b36-603f6ad35a3c)
 ### Domain:  Hospitality       ### Function: Revenue

 ## AtliQ Grands

 ### Scenario

 AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. 
 Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its 
 market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands 
 wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an 
 in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from 
their historical data.

### Task

Toanalyzed AtliQ Grands’ performance over the past 3 months, identifying revenue trends and key factors. 
The goal is to provide actionable insights for revenue management decisions so that it can regain its market share and revenue.

### Data 

The dataset, from codebasics.io, consists of five CSV files.
CSV files:
1. dim_date
2. dim_hotels
3. dim_rooms
4. fact_aggregated_bookings
5. fact_bookings

### Data Model

![DMHD](https://github.com/PoojaShylaja/Hospitality_Domain/assets/101803358/ccbf534b-2885-40af-992f-afbd35e37ddb)

### Key Measures 

**ADR** : Average Daily rate
It is the ratio of revenue to the total rooms booked/sold. 
It is the measure of the average paid for rooms sold in a given time period

Realisation % : It is nothing but the succesful "checked out" percentage over all bookings happened.

RevPAR : Revenue Per Available Room
RevPAR represents the revenue generated per available room, whether or not they are occupied. RevPAR
helps hotels measure their revenue generating performance to accurately price rooms. RevPAR can help hotels 
measure themselves against other properties or brands.

DBRN : Daily Booked Room Nights
This metrics tells on average how many rooms are booked for a day considering a time period

DSRN  : Daily Sellable Room Nights
This metrics tells on average how many rooms are ready to sell for a day considering a time period

DURN : Daily Utilized Room Nights
This metric tells on average how many rooms are succesfully utilized by customers for a day considering a time period

Week-on-Week (WoW) is a type of business metric that measures changes in a specific variable over a period of 
one week compared to the previous week. It is a common way of tracking business performance over time and is 
particularly useful for analyzing trends and identifying areas where improvements can be made.

Here are the metrics for which, the WoW change% is created:

1. Revenue WoW change %: To get the revenue change percentage week over week.
2. Occupancy WoW change %: To get the occupancy change percentage week over week.
3. ADR WoW change %: To get the ADR (Average Daily rate) change percentage week over week.
4. RevPAR WoW change %: To get the RevPAR (Revenue Per Available Room) change percentage week over week.
5. Realisation WoW change %: To get the Realisation change percentage week over week.
6. DSRN WoW change %: To get the DSRN (Daily Sellable Room Nights) change percentage week over week.

### Dashboard

![db](https://github.com/PoojaShylaja/Hospitality_Domain/assets/101803358/b8d9c781-d3c2-4630-8075-a642ef16ddc7)

Dashboard consists of KPIS :Revenue,RevPAR,Avg Ratings,Occupancy,ADR,Realization.

Charts :

1. Donut chart for different categories and roomtypes using field parameters
2. Key Matrix by week no: Line and column chart has been used to show the changes over the week for RevPAR,ADR and occupancy %.


 
