# Surfs Up Analysis
## Overview of the analysis: Purpose of This Analysis

While on vacation in Hawaii last year I discovered a new found passion for surfing. Since then I had been trying to come up with a plan that will let me not just return to Hawaii, but live there permanently. I finally came up with an idea that I thought was foolsproof, a surf and shake shop serving surf boards and ice cream to local and tourists. 

I had some savings I was willing to invest, but I needed some real investor backing to get the project off the ground. So I put together a strong business plan and I reached out to an investornamed W. Avy, who is famous for his love of surfing. The first meeting went well with W. Avy, but he did have one concern, the weather. He was extremely interested, and even had invested in a surf shop earlier in his career. Unfortunately, he didn't ask for any weather analysis and his early venture was rained out of existance. 

W. Avy knows I have been learning how to properly analyze data and asked me if I could run some analytics on a weather dataset he has on the very island where I want to open my shop.


## Results: 

W. Avy liked my analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

A summary of statistics for those months are below. June on the left and december on the right.

<img width="162" alt="june_stats" src="https://user-images.githubusercontent.com/102890151/171055643-b92034c8-5bb9-46a0-8503-e1c21b5c5124.png"> <img width="160" alt="dec_stats" src="https://user-images.githubusercontent.com/102890151/171055652-78c74b8e-f900-47c3-9685-cc8aff243e00.png">

### Four Major Points from the Two Analysis Deliverables

* It should be noted that the number of datapoints in December (1517) is less than that of June (1700)
* There is a 4 temperature difference for both months in their 25th percentile and 50th percentiles. For the 25th percentile June was 73 and December was 69. For the 50th percentile, June was 75 and the month of December was 71
* Minimum temperature was one of the bigget gaps between the two months. Minimum temprature in June was 64 while min. temperature for December dipped to 56.
* The maximum temperature for both months was only a 2 degree difference (85 for June and 83 for December).

## Summary: 
### Ice Cream in December?

With temperatures greater than 74 degrees 75% of the time in December and 50% of the time greater than 71 degrees starting a ice cream and surf shop would seem like good business. Only 25% of the time it dips below 69 in December. It would be good to see what the temperature statistics for January look like.

### Two Additional Queries That You Would Perform to Gather More Weather Data for June and December

* Temperature is only one key factor when looking at weather for analysis of the viability of a surf and shake shop. Temperature may have a correlation to how much ice cream may be bought, but there are other factors that should be looked at, especially bringing out the surfers. It would be good to look at sunny days vs cloudy in those months. Wind speed would be good to look at, particularily offshore wind speed. Wave heights, and precipitation would also be good to analyaze. 

* It would be good to go beyond June and December for the analysis. As I mentioned above it would be intersting to see temperature stats for January and then compar then to December.

January stats with query (below)

<img width="450" alt="jan_stats" src="https://user-images.githubusercontent.com/102890151/171063531-fdc31f27-ab64-4198-bd15-cdbe8238fd97.png">

* Another additional query would be to look at precipitation for the same two months as the analysis was done on (June/December). 

Code and query results for stats (June Rain)

<img width="450" alt="june_rain" src="https://user-images.githubusercontent.com/102890151/171068837-d4d512a5-f60f-4a79-9be1-a529a0f0c1b1.png">

Code and query results for stats (Dec Rain)

<img width="450" alt="dec_rain" src="https://user-images.githubusercontent.com/102890151/171068839-2622bd92-0b32-48fc-bcb8-136063c177ac.png">


