# capstone_religion_birthrate

## Tableau Dashboard

## Table of Contents
* [Tableau Dashboard](#Tableau-dashboard)
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normaling-the-data)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Sources](#sources)
* [Conclusion](#conclusion)

## Motivation:
As a new parent and also a lifelong Roman Catholic, I wanted to take the opportunity and research the relationship between religious identity and birth rate. 
I am interested to discover any possible correlation between these factors on the world, continent, region, and country level.


## Questions:
1) What are the regions or countries with the fastest growing and fastest shrinking populations?
2) What is the trend for religious identification in that area?
3) Is there a correlation between the two?
4) Are there any other factors that could influence birth rate based on religion, i.e., contraception and abortion.

## Normalizing the Data
The dataset on religious population I chose consists of years from 1910 through 2050. I selected the years 1970 - 2020 to correspond with birth rate data. I then created multiple dataframes according to layers of the UN Geoscheme and eliminated values not required for the analysis.

## Problems and Hurdles
My first substanial challenge was recreating the UN Geoscheme map for the presentation dashboard. This required downloading a blank map in .svg(Scalable Vector Graphics) format and loading it into Inkscape. From there, I grassigned Group ID's to continents and regions. I lastly imported the file into PowerBI using Synoptic Panel by OKViz.


## Technologies Used
1) Python / Pandas - for exploration, normalizing and aggregation of the dataset
2) PowerBI - for interactice dashboard
3) Git - for version control

## Data Sources
To answer the above questions I used the following sources to collect datasets for my analysis

1) 2024 Revision of World Population Prospects
https://population.un.org/wpp/

2) The World’s Religions in Figures: An Introduction to International Religious Demography
https://catalogimages.wiley.com/images/db/pdf/9780470674543.excerpt.pdf

Projecting Global Religious Populations, 2020–50
3) Wikipedia (web-scrapped the Global Peace Index)
https://brill.com/view/journals/jrd/8/1-2/article-p124_4.xml

## Conclusion

