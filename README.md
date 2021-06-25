# Historic Redlining in the City of Seattle
## *What Lasting Effects Can We Observe Today?*

# Abstract

The goal of this project is to demonstrate some of the negative effects that the redlining that occurred in the 20th century had. Through the use of an original redlining map of the city of Seattle, I was able to combine modern day data with current census tracts that now exist in the same areas as the originally redlined zones. The intention is to observe modern data, in comparison to old zoning, looking to evidence that certain areas a still disadvantaged due to the harmful effects that redlining had on local populations and how we should continue to support these areas as they are clearly still hurting from the effects of this process.

# Introduction

 Below is an original map of redlined zones in the city of Seattle. Redlining was a practice put into place by the federal government to partially help banks recover after the great depression. By outlining and ranking areas in which mortgages would be the safest to make, the government was able to systematically exclude certain areas from important services, as they would be deemed too risky to invest in. The areas were ranked based on the condition and age of the housing in the area as well as the income of its residents. However, most damagingly, they were also ranked based on the race of the individuals who occupied those areas. For example, in the city of Seattle, areas that allowed non-whites to live in the area were automatically made to be a part of the worst ranking on the map, systematically excluding people of any race that was not white from important local and federal services.

<img src = "img\old_redlining.png"/>

# Methodology

This projects initial step was to take the original redlining map of the city of Seattle and convert it to a modern form for data analysis. The purpose of this was to ensure that we could use this old zoning and compare it to new data from the 21st century. Then, through comparisons by joining features together, I was able to draw observable trends for areas that were originally disadvantaged, and, according to all data, are still disadvantaged to this day. Census data that included current zoning and the income, as well as the race of individuals was compared to show that not much has changed today in terms of where people currently live.

# Results

I started with a dataset that came from King County which details the demographics of all King County census tracks. This data is based on a 2012-2016 survey. What is important to note from this is that the extremely high percentage of people of color that occupy the southern parts of King County. If you are to draw your attention back to the original redlining map, you will see that those areas were all considered either hazardous or definitely declining, the two worst classification meaning that POCs once lived there and continue today.

<img src = "img\poc_census.png"/>

The next dataset that I used was the Racial and Social Equity Index that uses aspects such as race, socioeconomics, and health to draw conclusions about disadvantage in the different census tracts of King County. Again, in this map we can observe that the areas which were redlined the worst are still the most disadvantaged areas in King County today.

<img src = "img\sei.png"/>

Below are graphical representations of the median income for each census tract that lies within the original redlining zone. From this data you can see that the areas with the highest median incomes with the rightest skew are the top two redlining rankings, with the bottom two rankings having the lowest average incomes with the leftist skew.

<img src = "img\income.png"/>

# Conclusions

Below is the final version of the updated redlining map, excluding business and industrial zones, joined with current King County census tracts. When comparing this two the other two maps, it becomes clear that the areas that were redlined as being the worst in the 20th century to this day still have the highest POC occupation, the lowest incomes, and the most disadvantage. It becomes clear that redlining still has a great lasting impact, with many of the original areas expanding to even greater areas where the richest, non POC areas lay within the city and the poorest POC areas expanded over the surrounding area.

<img src = "img\converted_redlining.png"/>

# Citations

Brooks, K. (2020, June 12). Redlining's legacy: Maps are gone, but the problem hasn't disappeared. Retrieved December 06, 2020, from https://www.cbsnews.com/news/redlining-what-is-history-mike-bloomberg-comments/

Consolidated Demographics Index for King County Census Tracts / demographic index area. (2019, January 31). Retrieved December 6, 2020, from https://gis-kingcounty.opendata.arcgis.com/datasets/consolidated-demographics-index-for-king-county-census-tracts-demographic-index-area?geometry=-122.480%2C47.474%2C-122.047%2C47.555&selectedAttribute=PercentPOC.

Racial and Social Equity Composite Index. (2020, January 15). Retrieved December 6, 2020, from https://data-seattlecitygis.opendata.arcgis.com/datasets/225a4c2c50e94f2cb548a046217f49f7_0?geometry=-123.202%2C47.452%2C-121.471%2C47.776.

Segregated Seattle. (n.d.). Retrieved December 06, 2020, from https://depts.washington.edu/civilr/segregated.htm
