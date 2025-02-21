# HW 3 - CS 625, Spring 2025

Bhargav Iyer  
Due: February 23, 2025

## Data

I have chosen to work with the Suicide data.csv dataset.  This dataset contains data on several features such as Age of the victim, the country of the incident, the year the incident occurred, the generation the victim was born into (Gen Z, Baby Boomers, etc.), Sex, GDP Per Capita, GDP for the year, Population, Number of Suicides, and Suicides per 100,000 population.

## Visualization Idioms & visual encoding choices

A bar chart was used here to show a comparison between each countries own Suicide rates.  Since the population of each country will be different, I used the Suicides per 100,000 population to allow a comparison between the countries.  I filtered the data so that the visualization does not show suicides per 100,000 below 5,000.  This would only show the countries with truly high suicide rates.

Idiom: Bar Chart
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| Country | key, categorical | horizontal spatial region (x-axis) |
| Suicides per 100,000 | value, quantitative | vertical position on a common scale (y-axis) |

A multiple line chart was used to show the trend of suicides per year by sex.  I wanted to see whether the general number of suicides world wide were increasing or decreasing or stagnant.  I found that the number of suicides generally increased from 1985 to 2000 for number of suicides for men.  Where from 2000 to 2016 there was a gradual decrease, again for number of suicides for men.  For women, the suicide rates were generally stagnant around 50k.  However, there was a sharp decrease of number of suicides from 2015 to 2016 for both men and women.  Is there a special reason why? Maybe, not enough data for 2016?  I could not find any special reason for why there was a steep decline in suicides in 2016.

Idiom: Multiple Line Chart
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| Year | value, quantitative | horizontal positional on a common scale (x-axis) |
| Number of Suicides | value, quantitative | vertical position on a common scale (y-axis) |


