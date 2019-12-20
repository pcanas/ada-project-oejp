# Link to our data story
https://pcanas.github.io/chicago-oejp/

# Title

Chicago: is your food safe?

# Abstract

USA is a country who puts a large importance on food and has a very diverse food culture. We also have that Chicago is one of the most influential cities in the North American country. We want to combine these two insights in order to build an analysis on the food industry as it pertains to Chicago, but with a very specific viewpoint: we will look at how safe is to eat or buy food in Chicago.

We will use Chicago Department of Public Health’s corpus, containing data from inspections made in food establishments, in order to create a meaningful study on food security in the city. We would like to focus on understanding the reasons behind violations on the Public Health’s laws, and see if we can draw relations on the area environment, such as average income, geographical location or social status.

We believe that conclusions extracted from such study will help to better understand this outstanding city.

# Research questions
After considering the opportunities and limitations of the corpus, together with the feedback provided from Milestone 1, we have updated our research questions. We propose the following:

- What connections can be found between economic prosperity and the frequency of the inspections in an area, i.e. is there some bias? Is there also a connection between economic prosperity and food safety and types of violations?
- Are there differences in food safety between big companies and franchises and small businesses?

Although we think that addressing these topics has the potential for a good data story, we are still open to change the focus or pivot to a different topic in case we encounter with unexpected results that are considered to be more interesting.

# Dataset
The main dataset that we will use is the [Chicago Food Inspections](https://www.kaggle.com/chicago/chicago-food-inspections) dataset, which contains information regarding inspections of food establishments in Chicago. The earliest entries are from January 1, 2010 and the newest ones are from October 23, 2019. This is a dataset provided by the City of Chicago, and inspections are performed the Chicago Department of Public Health’s Food Protection Program, so we can assume the veracity of the data.

The corpus includes data of nearly 200.000 inspections. It is formatted in one CSV file, which makes a first visual inspection on all the corpus easier. Inspection features include the name of the establishment, its type (grocery store, restaurant, daycare, etc), its address and zip code, its risk of adversely affecting the public’s health, the result of the inspection together with detailed comments, and the date the inspection was done.

Although some characteristics may need formatting, a first look at the dataset indicates that the data is well structured and consistent throughout the corpus, which is good news for us. However, according to Kaggle's description: _"attempts have been made to minimize any and all duplicate inspection reports. However, the dataset may still contain such duplicates and the appropriate precautions should be exercised when viewing or analyzing these data"_. For this reason, we will need to do a further analysis in order to pre-process the provided dataset towards our goals. Also, the Violations column contains detailed but uncategorized information of the inspections, which could be transformed into a more digestible format through pre-processing.

Additionally, we will try to support our findings with auxiliary information regarding the City of Chicago. We have checked on several possible resources, such as income statistics provided by the [United States Census Bureau](https://www.census.gov/data.html) . The data from the Census Bureau is provided by Data USA in a more easily accessible form. For the city of [Chicago](https://datausa.io/profile/geo/chicago-il/) they provide several datasets. The Census Bureau also provides [geographical data](https://www.census.gov/programs-surveys/geography.html) about states, cites, zip codes, and survey tracts. Besides, as the City of Chicago has plenty of open source datasets, research will be conducted to find useful information.

# Contributions
- Oskar: Problem formulation, preprocessing of data, leading part 2 of our analysis, writing data story.
- Jeffrey: Problem formulation, preprocessing of data, leading part 1 of our analysis, writing data story.
- Eric: Problem formulation, preprocessing of data, contributing to data analysis, leading data story text.
- Pablo: Problem formulation, preprocessing of data, writing data story, preparing the final presentation.
