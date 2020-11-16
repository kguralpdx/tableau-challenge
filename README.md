#### tableau-challenge

## How Did COVID-19 Impact Citi Bike Ridership?

Citi Bike is the largest bike sharing system in the US and services Manhattan, Brooklyn and Queens in New York City as well as Jersey City, New Jersey. Not only do they provide a healthy and affordable way to get around the city, they've also been collecting the data since they started in 2013 and saving it in monthly files to be explored. This was the task at hand; explore this data with any timeline and find two phenomena--something unexpected or surprising.

### Discovery and Analysis

When I first started to download a couple files, the thought was to get the initial file from 2013 and compare those results from the latest file from October 2020. A lot must have changed including ridership and number of stations. But after some thought, I realized that maybe the 2013 data wasn't really all that relevant to today. With COVID-19 being such a part of everyday life, it dawned on me that we're looking at data from NYC which was the main hotspot for COVID last spring. The Citi Bike sharing system must've felt the effects of that with all the lockdowns and closures and it would be reflected in the data. Since a lot of businesses and industries are still either working from home or just closed like the theater district, I expected ridership to be down as well. So I started looking into that data, comparing October 2019 to October 2020 (the most recent file). Much to my great surprise, ridership was actually higher in October of this year than last year.

## Phenomenon #1 - Citi Bike Has Increesed Its Ridership Amidst the Pandemic

I downloaded the CSV files for both October 2019 and October 2020 and loaded them into *Tableau* creating a union to merge the two datasets. Had to do some column renaming and dataype changes but for the most part the data source was in pretty good shape. I started with the October Totals page. I wanted to show the total ridership this year versus last year and show how much of an increase was gained, especially since that's what surprised me. 

Next I wanted to see who these riders were -- were they Consumers buying a short-term pass or Subscribers purchasing annual memberships. Both types ended up showing increases. The Consumers did have a bigger growth, however, possibly