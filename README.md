# Lede Project 1: 10 Years of Plane Crashes

### When I received notifications about the crash on June 12th, 2025 in India that left one survivor, I was horrified. It's 2025, and there are still aviation accidents this deadly? I searched the web for data on aviation accidents, and stumbled upon the Bureau of Aviation Accidents Archives. I began to analyze the data and discovered some trends regarding fatalities, location, and aircraft type.

## Findings

#### I discovered that over the past decade, more than half of the accidents resulted in fatalities, ranging from 1 to 260. I was curious to see if the deadliest crashes happened in the same geographical region or if they shared the same aircraft. As it turns out, the worst crashes happened in relatively the same region – The Middle East and Southeast Asia. Though the 15 worst crashes occurred around the globe, most of them were close in latitude. The most common aircraft type of all crashes, though, is small propeller planes – meaning there is an increase in private planes and flying for personal use.

## Process

#### I found the database of the Bureau of Aviation Accidents Archives, plugged in my date range, and successfully scraped 67 pages of the data. I turned these 67 pages of tables into one large dataframe, to group, sort, and count different values. I decided to clean the data by dropping columns I did not need for my analysis. Once I had done enough analysis, I decided I wanted to create categories for each aircraft type. I took different names of aircrafts and plugged them into a define function. I then converted this into a new table with two columns: Category and Number of Accidents. From there, I turned it into a CSV and took it into Datawrapper to create a bar chart.
