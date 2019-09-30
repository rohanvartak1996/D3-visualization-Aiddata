# D3 visualizations for Aidata

## The following visualizations are developed in D3.js to answer various questions on Aidata.


## Project 1: Geographical Data


### Question 1 
### How do the countries compare in terms of how much they receive and donate from other countries? Are there countries that donate much more than they receive or receive much more than they donate?

![Visualization 1](https://user-images.githubusercontent.com/40985431/65843741-4692a980-e301-11e9-8d03-e783479d55be.png)

Explanation: In this visualization I have considered the top 30 countires that donated and top 30 countires that receive. We see that developing countries like India, Brazil, Indonesia, China, etc. receive the maximum amount of aid. Whereas developed nations like United States, Germany, Japan, France, etc. give more donations. The comparison between countries that donate more and that receive more is easy in this graph as there are 2 axis, one for donated amount and one for received amount. This allows us to compare large number of countries in a single chart. The diverging bars, along with different color for donated amount and received amount help to easily distinguish between the countries and answer the
question. I have not considered all the countries as the amount scale is in billions and some of the countries have received or donated in millions which would not have a visible bar on the chart. So to maintain relevance and answer the question effectively, I have only considered the top 30 donating and receiving countries. So counntries like India, Brazil, Indonesia, Mexico, China, Turkey receive much more than they donate and USA, Japan France, Germany, United Kingdom donate much more than they receive.



### Question 2
### Do the countries that receive and donate the most tend to cluster around specific geographical areas of the world? Are there neighboring countries that have radically different patterns in terms of how much they receive vs. how much they donate?

![Visualization 2](https://user-images.githubusercontent.com/40985431/65848380-da6d7100-e313-11e9-9dc0-abca87d5872e.png)

Explanation: In the above chart I used the color scheme as, when the donated amount is greater than the recevied amount then the color is red, and when the
received amount is more then the color is blue. The size encodes the absolute difference between the amount donated and the amount received in $ Billion. So we see that the countries that donate more are United States, European Nations like Germany, France, Netherlans, UK, Spain. In Asia we see Japan having significant donations. Australia and New Zealand also have more donated aid in south pacific region. Developing Countries in Asia and South America like, India, China, Indonesia, Bangladesh, Brazil, Argentina recieve most of the aid. None of the countries in Africa give major donations and mostly received the aid. We see contrast in North America where US donates the maximum aid and Mexico recevies a considerable amount of aid. Similarly we see that western european nations donate more while the eastern europen nations receive more. In Aisa Japan gives a high amount of donations, while its neighbours like China, Phillipine or Russia receive the aid. We also see that middle eastern countries like Saudi Arabia, UAE, Kuwait give more donations.

### Question 3
### Are there any major differences in how the top 5 most frequent purposes of disbursements distribute geographically in terms of countries that receive donations? Are there countries that tend to receive more of certain type of donations than others?

![Visualization 3](https://user-images.githubusercontent.com/40985431/65848551-9464dd00-e314-11e9-97b7-17f20e3cd5ae.png)

Explanation: Here I have faceted the map 5 times for the top 5 purposes of disbursement. I have considered the all countries for each purpose of disbursement. The color encodes the purpose and the size encodes the amount donated. We see that there are no major differences in the geographical distribution of the aid for the top 5 purposes. The overall pattern is the same for all the 5 purposes. In the size encoding we do see that some countries get more aid than others, but on a general trend we see that countries like India, China, Brazil, Argentia, Indonesia, Columbia, Egypt, Turkey, Pakistan, Thailand, Russia, get most of the aid and the aid is almost evenly distributed, with developing nations getting the majority of the aid and small nations getting smaller protions.

## Project 2: Temporal Data

### Question 1
### a) How does the amount donated vs. amount received change over time across all countries?; b) Are there countries that mostly send or mostly receive and countries that have a similar amount of donations they receive and send?; c) Are there countries that change their role over time? That is, they used to mostly send donations and turn into mostly receiving donations and vice-versa?; d) Are there countries in which you can find a sudden increase ("peak") or a sudden decrease ("valley")?

![Visualization 1](https://user-images.githubusercontent.com/40985431/65848834-db9f9d80-e315-11e9-9472-d00ba4f75b91.png)

Explanation: I have used a heat map with a diverging color scale to show how the donated and received amount varies by time across all the countries. For the graph I have encoded the difference between the donated amount and received amount into the color of the heatmap. I have plotted years from 1947 to 2013. I have filtered some countries for this graph. I have only included those countries where I could see a significant variation in the difference. Some countries had same color for almost all the years so did not show much variation, so I have filtered them out. The reason for choosing heatmap is that I can show the information for a lot of countries, through all the years in a single graph. I don't have to draw a separate graph for each country. I have choose a color scale which allows us to easily distinguish between countries which are donating more and which are receiving more. All the questions can be answered by this graph. I have order the countries such that the countries which have more donations are at the
top while the countries which receive more are at the bottom. We see countries like Japan, United States, France, Germany mostly donate while China, Mexico, Indonesia, Brazil and India mostly receive. We also see countries like Japan, Spain, Korea, Australia, Norway, Italy which used to receive donations in the earlier years like 1940s and 1950s but have now started giving more donations in 2000s. A lot of examples can be seen of the peaks and valleys in the graph. Consider example of Saudi Arabia, it has a peak in amount donated in 1977 and also a valley in 1999 where it donated very less and received aid of $2373 M. We see a valley for Kuwait in 1992. We see that Spain's donations peak around 2006 - 2010. We see a valey for Iran in 1994. So many such examples can be provided of peaks and valleys.

### Question 2
### Focusing on the purpose of the transaction. a) What are the top 10 purposes of disbursements (in terms of total amount of disbursement) and how does their amount compare over time?; b) Are there purposes that have a much higher/lower total amount among the top 10?; c) Are there purposes that show an increasing or decreasing trend (in terms of amount of disbursements) over time or that have sudden peaks or valleys?

![Visualization 2](https://user-images.githubusercontent.com/40985431/65848907-1dc8df00-e316-11e9-9cc4-d25eb383422d.png)

Explanation: Here I have used a small multples of area chart to show how the top 10 purposes of disburements vary over time. Each graph has its separate scale for the amount. This graph provides easy way to see the variations in each of the purposes as well as compare them amongst each other. All the top 10 purposes of disbursement are displayed. We see that general budget support has higher amount than other purposes. We see an increasing trend in purposes Multisector aid, Rail Transport, Road Transport and Water Supply and Sanitation. These purposes have have more amount in the 2000s. We see that Agricultural Development and Industrial Development have increasing trend during the 80s but starts decreasing during 90s and 2000s. We also see sudden peaks and valleys. Sectors not specified and Debt Forgiveness have peaks during 2010 and 2008 respectively. We also see sudden peaks and valleys in the graphs of General Budget Support and Power Generation/Renewable Sources.

### Question 3
### Focusing on a country that has a history of sending donations to many other countries (pick one): a) how does the set of countries it sends donations to change over time?; b) Are there countries that receive higher amounts in specific time periods?

![Visualization 3](https://user-images.githubusercontent.com/40985431/65848933-3e913480-e316-11e9-95f9-96ffd2e782c8.png)

Explanation: I have considered the donations made by United States as it has a good history of making donations. In this heat map we can see how United States has donated aid to different countries over time. The ordering of the countries is by the number of records for each country. So countries which have all records from 1973 to 2013 are at the top and other countries with fewer records are at the bottom. The scale is only from 0 to 500 million inorder to showcase sufficient colors and good variation so that we can find out the patterns in the data. I have filtered some countries which had only a few donations and mostly consisted of empty records. We see a lot of countries that receive higher amounts in specfic periods. We see Turkey and Phillipines receiving higher donation in 80s and 90s and less in 2000s. We see Tanzania receiving high amount of aid from 2009
onwards. We see Afganistan receiving very high amount of aid from 2002 to 2013. We see countries like China, Brazil, Argentina geting higher amount of donation in the 90s. Many such patterns can be uncovered from the graph.

## Project 3: Network Data

### Question 1
### Create an overview of the relationships between countries so that it is possible to see who donates to whom and how much. Questions one should be able to answer are: 1) Who are the major donors and to which countries do they donate the most? And conversely, who are the major receivers and which countries do they receive from the most?

![Visualization 1 Arc Diagram](https://user-images.githubusercontent.com/40985431/65848995-8617c080-e316-11e9-91e9-d64ab26fb384.png)

![Vsualization 1 Heat Map](https://user-images.githubusercontent.com/40985431/65849006-90d25580-e316-11e9-9c91-936af6962220.png)

Arc Diagram
Explanation: I have made an Arc diagram to show the relationship between countries in terms of donated and received amounts. The countries are considered are top 10 donor countries and the rest are the major receiving countries. The top 10 donors are colored in red and the other countries which receive more are colored in blue. The top 10 donors are to the left and the top receivers are from the right, rightmost being the highest receiver. When a country donates to a country the link is highlighted in red and when a country receives from another country the link in highlighted in blue. The width of the link encodes the amount. We see a lot of patterns in the chart. By hovering over a country we can see which country it donates to and which country it receives from.
Heat Map
Here I have made a heat map to show the relationship between the countries. The countries have been ordered such that the countries that donate more are to the top and lesser donating countries are at the bottom of Y axis. For the X axis the countries which are receiving more are to the left and the countries that receive less are to the right. We see that countries like United States, Japan, Germany, France, United Knigdom, Canada, etc. are the major donors while countries like Indonesia, India, China, Egypt, Pakistan, Philippines are the major receivers.

### Question 3
### Considering only the top 5 purposes of donation, how does the relationship between countries look like in terms of purposes? What purposes do countries donate for to other countries? Are there countries that donate to a given country using multiple purposes? Or do counties always donate using one single purpose when donating to another country?

![Visualization 3](https://user-images.githubusercontent.com/40985431/65849035-b3fd0500-e316-11e9-8990-2c305737b4e6.png)

Explanation: I have used a Sankey Diagram to show the relationship between countries in terms of top 5 purposes of donation. For this chart I have considered only the top 10 countries which are donating and the top 10 countries which are receiving to simplify the chart. We see how the major donors make their donations among the different purposes. We see that United States makes major donations for Industrial Development, General Budget Support and Multisector Aid. Likewise Japan donates a major portion to Road Transport. We see Sweden, Norway and Canada donating in small portions to all the top 5 purposes. On the other hand we see Argentina and Brazil receiving a higher portion of General Budget Support. Road Transport aid goes mainly to Brazil, China, India, and Indonesia. Mexico receives a lot of aid for Sectors not Specified. Multisector Aid and aid for Industrial Development seems to be evenly distributed among the top 10 countries.
