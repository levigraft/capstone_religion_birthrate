# capstone_religion_birthrate

## PowerBI Dashboard

## Table of Contents
* [Tableau Dashboard](#PowerBI-dashboard)
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
1) Does religious observance affect world fertility and birth rate?
2) Do regions follow a similar pattern?
3) Does the formal relationship between religion and state reveal any influence?
4) Is there a correlation between birth rate and government legislation of religous precepts?

## Normalizing the Data
The dataset on religious population I chose consists of years from 1910 through 2050. I selected the years 1970 - 2020 to correspond with birth rate data. I then created multiple dataframes according to layers of the UN Geoscheme and eliminated values not required for the analysis.

## Problems and Hurdles
My first substanial challenge was recreating the UN Geoscheme map for the presentation dashboard. This required downloading a blank map in .svg(Scalable Vector Graphics) format and loading it into Inkscape. From there, I assigned Group ID's to continents and regions. I lastly imported the file into PowerBI using Synoptic Panel by OKViz. Another hurdle was navigating and slicing the RAS Project data set, due to its immense size of ovre 5000 columns. 


## Technologies Used
1) Python / Pandas - for exploration, normalizing and aggregation of the dataset
2) PowerBI - for interactice dashboard
3) Git - for version control

## Data Sources
To answer the above questions I used the following sources to collect datasets for my analysis:

1) 2024 Revision of World Population Prospects
https://population.un.org/wpp/

2) The World’s Religions in Figures: An Introduction to International Religious Demography
https://catalogimages.wiley.com/images/db/pdf/9780470674543.excerpt.pdf

3) Projecting Global Religious Populations, 2020–50
https://brill.com/view/journals/jrd/8/1-2/article-p124_4.xml

4) The Religion and State Project
https://ras.thearda.com/

## Conclusion
In conclusion, Africa and Latin America have the highest birth/fertility rates and religious population. Asia's rates are dropping the fastest and has the largest population of non-religious. Regions are also moving in a smiliar fashion, with the highest rates corresponding to the most religious adherents for the continent. Government's relationship to an official religion reveals a similar correlation, as does specific laws tied to traditional religious values. 
