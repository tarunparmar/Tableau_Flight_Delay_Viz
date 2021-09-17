# Flight Delay Visualization with Tableau
### Dataset:
> The Data has been downloaded from https://www.transtats.bts.gov/ for the last 5 years- 2013 to 2017. Then I performed a union on the individual year's data. Since the complete dataset is over 725 MB, I uploaded zipped csv files for individual years: 2013_1.csv.zip, 2014_1.csv.zip, 2015_1.csv.zip, 2016_1.csv.zip and 2017_1.csv.zip.

### Summary:
> In this project, I have included visualizations to explore various flight delays over last five years. I created a story for delays related to airline, weather, diverted flights, security and operational delays to draw some conclusions related to airports and airlines that have correlations to delayed or cancelled flights.
Atlanta and Chicago Ohare airport and Delta, express jet airlines stood out.

>  Final version has been created based on the feedback from viewers, I have changed the design choices and color schemes. For example, I changed the bar chart to line chart on the second card for delays by year chart. I have also formatted the text for the story so it is easier to read the text. I updated the legends on axis for few of the charts to make them more meaningful. I replaced the bar chart on second card by line chart as it is more appropriate for time trends. I also added more heat maps to include cancelled flights and security delays. I also picked a colorblind friendly pallette for the charts based on review suggestions and also changed colors on airline and delay trends to remove ambiguity. Based on all the changes, The story has better readability and charts are easier to understand. By including heat maps, the story now paints accurate and complete picture for the viewer. By avoiding red and green colors, the charts are now colorblind friendly and can be understood by everyone now.


> Final version of the story is https://public.tableau.com/views/flights_final_16318943529840/Story1?:language=en-US&:display_count=n&:origin=viz_share_link

### Design:
> I included 4 dashboards consisting of bar and line charts in the story. The first card has line charts to show delays and time relationship. I picked a line chart because for a time trend, line chart is the most suitable to show the comparison of the delays over time. I have kept the layout simple, with line charts with less periods smaller(25% each on the right for day of the week and year charts) than the chart with more periods(50% on the left for Day of the month chart). I wanted to highlight day of the month chart as it showed intersting insight and hence made it bigger than the other two charts.

>The second card in the story shows bar charts connecting Origin airports, delay and time line. I used bar charts for this card because I wanted to show top 5 airports with the various delays. Since it is categorical data, bar chart conveys that best. I included the timeline chart on this card because I wanted to enhance user interactivity and provide flexibility to see the change in trend by changing different origin airports. I have 5 charts on this card and hence I did not want to make it too busy so I picked top 4 kinds of delays only and only top 5 origin airports.

> The third card explores the airline, and origin and destination airports relationship using line charts again. As these charts are also time trends, Line charts represent that releationship the best. By filtering on legends of airline or origin, the change in the trends can be viewed effectively. All the charts are distributed evenly for this card

> The fourth card shows a heat map of delays by origin and destination distributed evenly. A heat map or heat chart represents data values through color coding and shading. They are useful for identifying patterns, areas of concentration, and/or data variance. Since we are exploring delay values and numeric data(high and low delay) can be represented by hue/saturation using heat map effectively.

> All the charts on a card are interactive and filters in one affects the other and I have used color blind pallette post feedback

### Feedback:
> One of the feedback I received was to format the text in the story better. So, I added spaces and tabs in the text to improve user readability.

> I was also advised to change the colors of airline trend so they are different from the origin/dest trends.

>Also, the bar chart on second card conveys the same information that was showed by the line chart on the first card. So I replaced it with trend chart.

>I also received feedback to include cancelled flights in my heat map which i did in my final revision.

> I was given feedback to create a colorblind friendly story, and avoid the combination of red and green colors, so I switched to a colorblind pallete of colors available in Tableau.

### Resources:
> https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236&DB_Short_Name=On-Time
> https://www.tableau.com/learn
> http://fortune.com/2015/04/15/delays-at-americas-busiest-airports/
