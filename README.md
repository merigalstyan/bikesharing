# Citi Bike Cruising

## Overview of the analysis

This analysis was conducted to understand the bike sharing market and its users. The analysis and its visualizations can be used for a bike sharing app proposal in Des Moines. The main data used for this purpose is **Citi Bike** data that has been released to the public. 

***This analysis is based on New York City only. The outcomes should help us understand which data will and will not apply to Des Moines.***

## Results

### Trip Duration

The first visualization shows how many hours were bikes checked out by all riders. From this graph we can conclude that most of the bikes have trip duration of no more than five minutes, even though there are bikes that are checked out for several hours. 

<img width="957" alt="Screen Shot 2022-12-07 at 12 49 38 AM" src="https://user-images.githubusercontent.com/111609994/206132626-2d903571-24e5-4166-ba91-ce812f89776a.png">

Almost 50,0000 bikes had a checkout time of 5 minutes. 


### Trip Duration by Gender

Another interesting finding was the checkout times of bikes by gender. This graph not only shows that again, most bikes had approximately 5 minutes of checkout times, but we can see from this graph that the male riders outnumber female riders. Although there is some data of **unknown** gender, it's not too significant to impact the difference between male and female riders:

<img width="1198" alt="Screen Shot 2022-12-07 at 12 53 12 AM" src="https://user-images.githubusercontent.com/111609994/206133505-3c390138-013d-4201-a6e5-abf13cd0918d.png">

### Trips by Weekday (By Hour)

Using the **Stoptime** and **Starttime** data another graph shows the relationship between bike rides and weekdays by hour. As predicted, a significant amount of rides occur by the end of the week. Thursday, Friday and Saturday rides are spread out during the day. However, throughout the week more rides occur starting 6:00 AM to 9:00 AM in the morning and from 5:00 PM to 7:00 PM in the evening. Interestingly enough, the hottest hours for bike riding occurs on Thursdays between 5:00 and 6:00 PM. 

<img width="564" alt="Screen Shot 2022-12-07 at 12 56 29 AM" src="https://user-images.githubusercontent.com/111609994/206134797-33300c90-7855-4fd0-ade7-67d81e691f9c.png">

### Trips By Weekday amoung Genders (By Hour)

As observed above, male riders outnumber female riders. If we combine both graphs from above, we can see that not only the most active times of riding in NYC are from Thursday to Saturday, but we can also observe the significant difference between genders. 

<img width="893" alt="Screen Shot 2022-12-07 at 1 01 55 AM" src="https://user-images.githubusercontent.com/111609994/206135411-32061f1b-33dd-4279-9c00-ab0009f722f3.png">

Clealry, most riders during the busiest hours are male. While there is some unknown data, the graph doesn't show a significant number of them. 

### Usertypes, Gender and Trips

Filtering by usertype and gender, another visualization shows rides within different types of users and genders. This heatmap again shows the rides by each weekday. 

<img width="893" alt="Screen Shot 2022-12-07 at 1 05 40 AM" src="https://user-images.githubusercontent.com/111609994/206136875-069f387c-09dd-481d-871d-4ddfc10b83d3.png">

We can assume from the map that:

* Thursday, Friday and Saturday are the most active times for riding
* More males than females are shown to ride a bike in NYC
* In addition, most riders are subscribers.

The difference between customer rides and subscriber rides are significant.




