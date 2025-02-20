# HW 3 - CS 625, Spring 2025

Bhargav Iyer  
Due: February 23, 2025

## Data

I have chosen to work with the Suicide data.csv dataset.  This dataset contains data on several features such as Age of the victim, the country of the incident, the year the incident occurred, the generation the victim was born into (Gen Z, Baby Boomers, etc.), Sex, GDP Per Capita, GDP for the year, Population, Number of Suicides, and Suicides per 100,000 population.

## Visualization Idioms & visual encoding choices

A bar chart was used here to show a comparison between each countries own Suicide rates.  Since the population of each country will be different I used the Suicides per 100,000 population to allow a comparison between the countries.

Idiom: Bar Chart
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| country | key, categorical | horizontal spatial region (x-axis) |
| Suicides per 100,000 | value, quantitative | vertical position on a common scale (y-axis) |



Idiom: Line Chart
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| Year | value, quantitative | horizontal positional on a common scale (x-axis) |
| Number of Suicides | value, quantitative | vertical position on a common scale (y-axis) |
