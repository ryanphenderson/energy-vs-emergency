## Energy vs. Emergency
## Table of Contents
* [Motivation](#motivation)
* [Questions](#questions)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Sources](#sources)
* [Conclusion](#conclusion)

# Motivation
I come from a power generation background in the Navy, and during my career I had the uncommon experience of being stuck on an island for the majority of the COVID-19 outbreak. Due to my isolated isolation, I had little to no clue how things were in the other parts of the world. During our Tableau project, I came across a Kaggle dataset that covered power generation per resource per country, and in every developed country I looked at, all resources dipped significantly in 2020, and took a while to get back to relative normal. The cause of this seemed obvious, but I wanted to compare other countries and see if I could determine which factors affected the power grids the most.

## Questions:
1) What changes occured to countries' power consumption in the first year of the COVID pandemic?
2) How did the affected countries respond, comparatively?
3) Is there a correlation between the strictness of lockdown restrictions and the change in fuel consumption?


## Problems and Hurdles
Here were a few obstacles I found as I was working through this project:
•	How do you compare power consumption between two countries with wildly different population sizes? Looking at the change in power consumption as a percentage change instead of the raw kWh difference accounted for most of that difference.
•	Dates and dates. While the power consumption database is annual, the COVID tracker is daily. Determining how to transform that data into something I could average over a year tested my knowledge of python/pandas greatly.
•	Cleaning country names is a persistent and inescapable hurdle for any data analysis.


## Technologies Used
1) Python / Pandas - for exploration, normalizing and aggregation of the dataset
2) Power BI - for creating interactive   dashboard and presentation
4) Git- for data storage
5) Excel - Data exploration



## Data Sources
1) Hannah Ritchie, Pablo Rosado and Max Roser (2023) - “Energy” Published online at OurWorldinData.org. Retrieved from: 'https://ourworldindata.org/energy' 
2) Energy Institute (2024), Statistical Review of World Energy 2024, Energy Institute, London. Available online at: https://www.energyinst.org/statistical-review/home
3) Thomas Hale, Noam Angrist, Rafael Goldszmidt, Beatriz Kira, Anna Petherick, Toby Phillips, Samuel Webster, Emily Cameron-Blake, Laura Hallas, Saptarshi Majumdar, and Helen Tatlow. (2021). “A global panel database of pandemic policies (Oxford COVID-19 Government Response Tracker).” Nature Human Behaviour. https://doi.org/10.1038/s41562-021-01079-8


## Conclusion
1) Changes during the first year of COVID-19

-Of the 65 countries examined, 4 had a positive deviation from their anticipated change in primary fuel consumption.
-Most heavily affected was the consumption of oil, with again all but 4 countries having a negative deviation.
-More stable sources such as Hydro and Nuclear appeared to be the least affected.
-Due to the nature of percentages, countries with less consumption were more prone to larger changes.


2) Response of the countries affected

-More densely populated countries such as China and India had the strictest COVID response.
-Less dense populations had more relaxed restrictions, perhaps attributed to tighter-knit social circles.
-While workplace closures and restrictions on gatherings were mostly common throughout, less strict countries had fewer restrictions on -movement and public transport.


3) Determining if there is a possible correlation

-Based off of the scatter plot, there does not appear to be a solid correlation between COVID response and the change in primary fuel consumption.
-The COVID-19 Epidemic was an extremely disruptive event, leading to price fluctuations across a wide range of exports and imports.
-Despite the apparent connection, even though affected citizens were stuck indoors or otherwise restricted, they were still consuming electricity and interior heating, and industry kept on moving.