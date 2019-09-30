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
