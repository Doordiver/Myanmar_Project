# Myanmar_Project
## Personal Project looking into the Myanmar Civil war

I begun the project by seeking already cleaned data relating to Myanmar, and started on the [humanitarian data exchange](https://data.humdata.org). There I found 3 clean datasets, looking at the POlitical casualties, Civilian casualties and Refugee locations globally.

I then went searching for some up to data economic data for Myanmar. This proved difficult, as there isn't much reporting coming out of the country. Eventually I was able to find data on Myanmar's exports at [Our world in data](https://ourworldindata.org). After looking through this, I proceeded just with the rare earth metal exports as the most interesting data.

From this initial data, I created a variety of graphs, including:

## Political and Civilian Casualties

![alt text](https://github.com/Doordiver/Myanmar_Project/blob/6802f0500447518ed3b51108b73930cb74aebc1f/Images/Political%20casualties.png)
Line graph showing the political casualties

![alt text](https://github.com/Doordiver/Myanmar_Project/blob/6802f0500447518ed3b51108b73930cb74aebc1f/Images/Civilian%20casualties.png)
Line graph showing the civilian casualties

Both of these graphs were made by plotting casualties against year, and filtering from 2010 onwards.

## Global rare earth mining exports

![alt text](https://github.com/Doordiver/Myanmar_Project/blob/6802f0500447518ed3b51108b73930cb74aebc1f/Images/Mining.png)
Rare Earth Metal bar chart

This bar chart shows the comparison levels between various countries, and has filtered out all countries producing less than 5% of world supply, so that we can focus in on the important countries. There is also a colour filter on Myanmar, so that it is highlighted for a better visual. It has also been filtered to only show data for a single year (2024), rather than an aggregate over the whole dataset.

## Refugee data for the region

![alt text](https://github.com/Doordiver/Myanmar_Project/blob/6802f0500447518ed3b51108b73930cb74aebc1f/Images/Refugee%20pie%20chart.png)
First I looked at the Pie chart camparing the number of refugees originating in Myanmar in other countries, which was filtered down to only show countries with a large number of refugees (otherwise it shows countries with even just 1 refugee, and was very messy)

![alt text](https://github.com/Doordiver/Myanmar_Project/blob/6802f0500447518ed3b51108b73930cb74aebc1f/Images/Refugee%20Map.png)
Next I generated a map to show the refugee data using a colour fill to show the amount. This was to give a good idea as to where they had gone gloablly, rather than just the pie. Interestingly, these countries were all geographically close to Myanmar

![alt text](https://github.com/Doordiver/Myanmar_Project/blob/6802f0500447518ed3b51108b73930cb74aebc1f/Images/Refugee%20Comparison.png)
Finally, I compared the global totals for registered refugees, so as to compare the count of refugees from Myanmar against other countries. This resulted in Myanmar appearing 6th, which surprised me as i didn't believe it would be as high as that. I then added a colour filter, so that Myanmar stood out, as it was the information that I wanted to visually highlight in this section.

## Aid comparison

![alt text](https://github.com/Doordiver/Myanmar_Project/blob/6802f0500447518ed3b51108b73930cb74aebc1f/Images/Aid%20data.png)
For aid, I created a line graph showing the percieved required aid against the actual recieved aid, plotted against time. This involved plotting as a dual axis, so that both could be compared.

# Dashboarding

I then gathered the graphs i had made and combined them into a dashboard visualisation, in order to complete the project, and highlight my data, its analysis and the final conclusions we could take away from my exploration of the data.

For this I simply imported the previously made graphs, and drew out some key KPIs to highlight the main takeaways from each section

This resulted in the completed workbook, which you can find [here](https://public.tableau.com/app/profile/thomas.barkshire/viz/Myanmardraft7/MyanmarCivilWar)
