# World Happiness Report 2017
## Aim
The aim of this visualization is to draw insights on the survey data gathered for the year 2017 by listing the
top 5 countries based on six factors. These six factors are healthy years of life expectancy, GDP, social
support, trust, perceived absence of corruption in government, freedom to make life choices and generosity.
The questions that I am trying to answer through this project are:
- How different aspects of the social context affect the levels and distribution of life evaluations among
individuals within and among countries.
- Whether top ten countries rank highly on all six factors?
- My story focuses on finding what is the combined effect of bottom to average improvements in both
GDP per capita and health life expectancy of an individual in the top 5 countries.

## Dataset
The data for this field of study was openly available on www.worldhappiness.report dataset. The data
consisted of 40 different factors. There are about 2000 rows containing country scores spread across 40
different attributes. Most of these attributes are updated by Gallup World Poll and is updated on World
Happiness Report website. The Gallup World Poll(GWP) addresses the most important issues worldwide
related to the performance and well-being of an individual.

## Data Exploration, Processing, Cleaning
Steps taken to prepare dataset for plotting the graphs:
- The unwanted columns were removed from the raw data having maximum null values and
inconsistencies.
- There were null values in all six factor level attributes which was another issue and it was replaced
by processing the data in python using Pandas and NumPy libraries and were also filtered in
tableau[3].
- A filter was applied for filtering out the countries having the highest happiness score count spread
across the years from 2000 till 2016.
- Tableau maps were plotted for all 150 countries mapped with their pre-processed happiness scores
for a proper plot.
- Means were calculated on the data attributes which was further used for creating the graphs.
- Interpolation rule was applied across the dataset to fill the null values in the dataset.

## Visualization
![alt text](https://github.com/PrateekSakaray/Tableau-Dashboard)
