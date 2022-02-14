# bikesharing

[link to story](https://public.tableau.com/app/profile/connor.cole2565/viz/bikesharing_16447949221360/CitiBikeStory)

## Overview

To visualize citi bike ridesharing data based on available parameters including gender, time/day bikes were rented, and user type.

## Results

![image](https://user-images.githubusercontent.com/92554586/153780299-3f4f5ae9-8ca1-445d-a64c-b3ea701f6918.png)
This line chart displays the trip duration for each bike checked out. Most trips were below 20 minutes long. 

![image](https://user-images.githubusercontent.com/92554586/153780387-01171b23-4920-40aa-b5b7-b2ef5c6cf572.png)
This line chart also displays trip duration for each bike that was checked out, but filtered by gender. The majority of bikes were checked out by males.

![image](https://user-images.githubusercontent.com/92554586/153780460-a1686453-8368-4b99-b44d-fefafb5b9f99.png)
This heatmap plots the start time hour against the stop time hour for bikes that were checked out. The darkest sections are between 5pm and 7pm, so the majority of trips were taken in this timeframe.

![image](https://user-images.githubusercontent.com/92554586/153780648-c5f2a424-1918-4ea4-b282-8b76090c4a09.png)
This heatmat plots the same information as before, only this time filtered by gender. This again shows how males rent the most bikes.

![image](https://user-images.githubusercontent.com/92554586/153780683-8b06fb59-36e0-4ad3-b3ba-5b0442d9434d.png)
This heatmap adds a second filter to the data, user type. The user types are customers (temporary users) and subscribers (those who pay monthly for the service). The majority of rides are taken by subscribers.

![image](https://user-images.githubusercontent.com/92554586/153780798-23bd81cf-3661-47ae-b13c-fc8b7db06f2f.png)
This map shows the top starting locations where bikes are initially checked out in NYC. Overall very spread out, with a cluster near the river.

![image](https://user-images.githubusercontent.com/92554586/153780847-6d4eeece-80c1-448e-93a4-8be152c07c19.png)
This map shows the top ending locations where bikes are returned. The cluster by the river is thicker, meaning most people complete their trips here.

## Summary

The majority of bike rides are taken between 5pm and 7pm by males who subscribe to the citi bike service. Seeing as these riders make up the majorty of rides taken, bike maintenance should be done in the morning so as not to interrupt the peak traffic in the evenings. 

One additional visual that would be useful is plotting the routes taken on the trips - instead of splitting on starting and ending locations, the whole routes being displayed could potentially show where more bike checkout stations could be added. On top of this, you could track the trip duration for each bikeid to see when bikes need repairs, and if the repairs done are effective. If bikes are being brought back to be repaired repeatedly, then whoever is performing the repairs likely needs extra training.
