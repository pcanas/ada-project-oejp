
# Title

Analysis of Food Security in Chicago

# Abstract

When working with food keeping a clean work environment is important. Whilst its easy to verify at home that ones kitchen is clean, it is much harder to make sure of it at the local grocery stores or ones favorite restaurant. For this reason such establishments are regularly controlled by state Food Protection Programs. Depending on regulations such results of such inspections have to be displayed. Severe breaking of regulations may even lead to the closing of an establishment. 

In this project we will analyze data from inspections made in food establishments in the city of Chicago, which are recorded in the Chicago Department of Public Health’s corpus. We would like to break this data down for one geographically, and see if we can draw relations to metrics like the median income of the area the food establishment is in. But we would also like to analyses the data on the kind of establishments, are for example chain restaurants safer than independently run restaurants. 


# Research questions
We propose a list of questions that we would like to address during the project:

- Have food establishments with failed inspections improved through the years?
- What connections can be found between economic prosperity and the quality of the inspections in an area? 
- Are there differences in failing rates between big companies and franchises and small businesses? State-owned and private? Different types of establishments? Different types of food they serve?
- Are there areas that have more safe food establishments than others in Chicago?
- Can we find indications of food establishments closing down due to failed inspections?
- What type of violations are the most frequent?
- Can we find a measure of severity by processing the detailed data?

These questions may vary in depth and/or breadth as we proceed analyzing the dataset. Also, new questions may be addressed in case we consider them appropriate for a more interesting outcome, but old questions might be dropped as well if we find no way to give a meaningful answer to them.

# Dataset
The main dataset that we will use is the [Chicago Food Inspections](https://www.kaggle.com/chicago/chicago-food-inspections) dataset, which contains information regarding inspections of food establishments in Chicago. The earliest entries are from January 1, 2010 and the newest ones are from October 23, 2019. This is a dataset provided by the City of Chicago, and inspections are performed the Chicago Department of Public Health’s Food Protection Program, so we can assume the veracity of the data.

The corpus includes data of nearly 200.000 inspections. It is formatted in one CSV file, which makes a first visual inspection on all the corpus easier. Inspection features include the name of the establishment, its type (grocery store, restaurant, daycare, etc), its address and zip code, its risk of adversely affecting the public’s health, the result of the inspection together with detailed comments, and the date the inspection was done.

Although some characteristics may need formatting, a first look at the dataset indicates that the data is well structured and consistent throughout the corpus, which is good news for us. However, according to Kaggle's description: _"attempts have been made to minimize any and all duplicate inspection reports. However, the dataset may still contain such duplicates and the appropriate precautions should be exercised when viewing or analyzing these data"_. For this reason, we will need to do a further analysis in order to pre-process the provided dataset towards our goals. Also, the Violations column contains detailed but uncategorized information of the inspections, which could be transformed into a more digestible format through pre-processing. 

Besides the Chicago Food inspection dataset we will use income statistics provided by [United States Census Bureau](https://www.census.gov/data.html) . The data from the Census Bureau is provided by Data USA in a more easily accessible form. For the city of [Chicago](https://datausa.io/profile/geo/chicago-il/) they provide several datasets. 
The Census Bureau also provides [geographical data](https://www.census.gov/programs-surveys/geography.html) about states, cites, zip codes, and survey tracts. 


# A list of internal milestones up until project milestone 2

- [ ] Extract interesting information from the Violations column. 
- [ ] Find out the differences between different inspection types (Canvass, License, etc.) and different types of establishments.
- [ ] Gather from external sources as much supporting information as possible, in order to enrich the analysis. This includes the average income per zone in Chicago, a more accurate segmentation of the type of business (e.g.: for restaurants, we could divide them in Italian, Japanese, Mexican or state owned versus privately owned, etc.), or locations of main tourist attractions, among others.
- [ ] Find a resource that allows us plot an accurate map of Chicago, including a division per ZIP Code. This is of vital importance in order to succeed in our map plots, which we believe are crucial for the analysis.
- [ ] Plot and analyze different relations between columns to give us an indication of which of the research questions we can take on.

# Questions for TAs

- Is there any popular source to find the map coordinates of regions, such as the per-state USA map used in the tutorials?
- What is a good scope of the project? Are we proposing too many different questions, should we just focus on a particular aspect of the dataset?
- Are we fulfilling the "social good" requirement?
- Are the analysis tools studied until now enough to achieve a relevant analysis, or should we research on more complex methods or concepts not covered during the course?
