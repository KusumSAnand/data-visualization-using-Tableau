
## Project -  Data Visualization using Tableau

## Tableau Story - Flight performance pattern

First version of the Story -

https://public.tableau.com/profile/kusum8304#!/vizhome/UnitedStatesAirlinePerformance2010-2017Ver1_0/FlightPerformancePatterns?publish=yes  

Final version of the Story -

https://public.tableau.com/profile/kusum8304#!/vizhome/UnitedStatesAirlinePerformance2010-2017Ver1_1/FlightPerformancePattern?publish=yes


## Summary

The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics (BTS)tracks the performance of domestic flights operated by large air carriers.Summary information on the number of on-time, delayed, canceled and diverted flights are available for download in raw format from their [site](http://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp).

The dataset used for visualzing the story is for the period Jan 2010 - Dec 2017. 
The Story captures monthly flight performance pattern of carriers in terms of overall delay,cancellations and diversions. The Story starts with the overview of the top airports affected by delay followed by the top affected carriers in terms of delay,cancellation and diversions by year and by month.And finally concluding with focus on the most affected carrier and the corresponding most affected airports.


<a id='introduction'></a>
## Design

The flight performance pattern has been visualized with five story points.The design decisions for each of the story point is below-

   1. The first story point gives an overview of the top ten airports in terms of total delay.This uses a geographical map(average delay) and tree map (%delay) in brown and blue shades respectively.The components of the total delay is shown using bar chart.

   2. The second,third and fourth story points display the top 5 carriers affected 'by month' and 'by year' in terms of the delay,diversions and cancellations. Each of the story points uses combination of tree map and line chart/bar chart in blue and  brown shades respectively.
    
   3. The fifth and final story point brings together the observations from the four story points and more.There are 3 components -top airports affected by the carrier(tree map),overall performance(line chart) across months and maximum delay(bar chart) in each month.


## Feedback

Following are the set of feedbacks from Emma Harvey -

1)    On every page there is the table at the bottom shaded in different greens. I don’t think this table is necessary. Maybe even a much smaller table, listing the data in order, and shaded the same orange colours that correspond to their colours in the graph. But even a simple ordered list would do.  

**The table is a treemap shaded in blue.This is an important component highlighting the factors affecting airports and carriers corresponding to the story point in that year/(all years).Presume that removing the title to the treemap invited the doubt.The title has been restored.**

2)    P1: Map is perfect – easy to follow

3)    P2: Bar chart easy to follow. Maybe put legend beside chart rather than on top of it so can see the names of the airlines better.

**Alignment issue is resolved**

4)    P3: spelling error in story heading – ‘closed’ should be ‘closely’.  Line graph is a little difficult to follow (especially when looking at All Years). Story summary mentions that Express Jet had top cancellations 2010-2017 – maybe a bar chart with average cancellations from 2010-2017 could be added as well or instead?

**Typo rectified.Filters to the line graph modified resolves this.**

5)    P4: same comment as P3 – maybe a bar chart with carrier diversions from 2010-2017 could be added.  if also want to include diversions by month in line chart, could just have top diversions airline (southwest airlines) by month?

**treemaps shows diversions of carriers by year and line chart shows the diversion changes across months.**

6)    P5: Map plot not needed here – not adding to story.  If the line graph is only for Southwest airlines, maybe add ‘Southwest Airlines’ to title of chart.  A lot of data in the line charts -  a little confusing. Maybe could look at % delays, cancellations, diversions (combined) of total flights and separately show graph of ‘Different Delay types’.
**Map plot removed (only because of space constraint,highlights airports affected)and retained the treemap for the airports affected.‘Southwest Airlines’ as the title of chart will not communicate well,‘Southwest Airlines’ is an outcome of the observations from preceding points and want to keep it flexible to use filters.The last point digs in to the details to understand more.**






Feedback link
https://udacitydatascience.slack.com/archives/C72AP9J3Y/p1531312327000375?thread_ts=1531292934.000120&cid=C72AP9J3Y

## Resources

https://www.tableau.com/learn/training

https://www.reddit.com/r/tableau/comments/2rmlmr/changing_a_discrete_number_into_a_month_name/



