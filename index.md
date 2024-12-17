## Looking into Marginalized communities in Middlesex

Written by Joanna Freedman in Commandline GIS and taught by Will Payne.

Below is my interactive map of Middlsex counties. The yellow and orange tracts below are showing the percent of people without Cars, where red is the most with 50% of the population, and yellow is 0 to 8%. On top are icons that will guide you to either Pantries in the area (leaf icon) or EBT Hubs (the orange carrot) along with additional details io the spot. The idea behind a map like this is to understand scarcity of food in any area and whether or not its being addressed appropriately.

The map uses data from the census data from 2022, a cultivated list of pantries that I have put together using pantry list websites in Middlesex County and a very recent map of EBT, given to me by Will Payne- as such I have no idea how to find it again or where or hold it is though I assume its very recent. I had create a new dataframe for the EBT, and also return them into points in order to get them into folium. I also at one punt did a spatial join to get data together which was pretty wild. Additionally I had to aggregate and parse through the No drive census data. I didn't kow how to put in the reliable data separate from the reliable one so I just put in altogether. Most of the data isn't super reliable, even on a tract level which I thought was strange. 
<iframe src="NoDrive.html" height="855" width="95%"></iframe>

Below are data for 2 maps, one shows the amount of permits around different incomes and additionally where Rugers is. The The idea behind this map is to compare and contrast between areas near rutgers versus the rest of Middlesex county. I also put in where the permit was above or below the usual housing price in Middlesex to see ptential areas where rutgers is build, around Rutgers, dots that are Purple are likely being built by rutgers because their above the median price for a home in middlesex (500,000 dollars), areas around rutgers whose permits are below the median price is orange. Places where the price is above 500,000 to contruct and not close to Rutgers is orange and everything else is brown. Everything is from the 2022 census, the permits are from a NJ government website/ supplied by Will Payne and is from 2024, and I had to connect it with the tax parcels for the permit lots to show up using Pams Pin. 

The second map is looking at Middlesex county for the percent of white people. The map shows that overall, new development is pretty spread out into both high white and low white. Most the data was reliable. Same deal as the 1st static map concerning pricing of construction.  


<iframe src="Maps (1).png" height="855" width="95%"></iframe>
<iframe src="MedianIncome_Map.png" height="855" width="95%"></iframe>
<iframe src="Percent_White.png" height="855" width="95%"></iframe>


You can explore this map [as its own web page here](NoDrive.html).
