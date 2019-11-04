# tableau
## Data
I used the most recent three months of data (July - September 2019) from the Citi Bike website.





## Analysis
### Most Popular Stations
Above is a chart showing the most popular bike stations. The stations are sized and colored by total number of rides. As you can see the majority of the the popular stations are in Mid-Town Manhattan where much of the tourist attactions are. 

### Trend 1:
The first thing that I wanted to look at is if there was a difference between when older and younger people were choosing to go. I created two groups of data based on the reported ages of the users. The first was people aged 16-28, and I called them the "young" group, the other was ages 65-75, which I called the "old" group. The results are visualized below. 


As you can see, although there is certainly more volume for the younger group there doesn't seem to be a huge disparity in where they are actually travelling. The majority of the traffic falls in the NOHO and East Village neighborhoods which trypically have heavy auto traffic and are outfitted with extensive bike lanes.

One things that I did notice while looking at the ages is that when plotted, there are a huge amount of rides taken by people who are age 50. It looked as though it had to be an error, my guess is that when registering for the app or service the default age or birthday was 50 years old and many people just didn't bother changing that. Once all of the 50 year olds were filtered out the distribution looked a lot more like what I was expecting with that majority of users falling in the late 20's to early 30's range and are predominantly male.

### Trend 2:
The other trend I was interested in was actually more of an anti-trend. I noticed that the least popular hours to begin a trip were between 1 and 4 am. Those hours had approximately 5-10% of the volume that the highest traffic hours had. It really wasnt too surprising that those are the lowest volume hours since the majority of people are asleep or alredy home and the others are more likely to take a cab or uber since there is less traffic and it will most likely be faster.

I was however interested in where these people were going so I created a new field that concatenated the start and end points of each trip and then plotted the top 50 most popular routes between 1 and 4 am. Unsurprisingly most of the routes fell in Lower Manhattan and were somewhere between walking and driving range. There were a few longer routes that surprised me, especailly those that crossed either river.
