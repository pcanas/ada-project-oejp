
# Title

A study on Food Security in Chicago

# Abstract
_A 150 word description of the project idea, goals, dataset used. What story you would like to tell and why? What's the motivation behind your project?_

# Research questions
_A list of research questions you would like to address during the project._

- Have food establishments with failed inspections improved through the years?
- What connections can be found between economic prosperity and the quality of the inspections in an area? 
- Are there differences between big companies and franchises and small businesses? State-owned and private? (Can we do this?) Different types of establishments? Different types of food they serve?
- Can we find indications of food establishments closing down due to failed inspections?
- Can we find a measure of severity by processing detailed data?

These questions may vary in depth and/or breadth as we proceed analysing the dataset. Also, new questions may be addressed in case we consider them appropriate for a more interesting outcome.

# Dataset
_List the dataset(s) you want to use, and some ideas on how do you expect to get, manage, process and enrich it/them. Show us you've read the docs and some examples, and you've a clear idea on what to expect. Discuss data size and format if relevant._

The main dataset that we will use is the [Chicago Food Inspections](https://www.kaggle.com/chicago/chicago-food-inspections) dataset, which contains information regarding inspections of restaurants and other food establishments in Chicago from January 1, 2010 to the present. This is a dataset provided by the City of Chicago, and inspections are performed the Chicago Department of Public Health’s Food Protection Program, so we can assume the veracity of the data.

The corpus includes data of nearly 200.000 inspections made. It is formatted in one CSV file, which makes easier a first visual inspection on all the corpus available. Inspection features include the name of the establishment, its type (grocery store, restaurant, daycare, etc), its address and zip code, its risk of adversely affecting the public’s health, the result of the inspection together with detailed comments, and the date in which this inspection was done.

Although some characteristics may need formatting (see next section), a first inspection on the dataset indicates that the data is well structured and consistent throughout the corpus, which is good news for us. However, according to Kaggle's description, _"attempts have been made to minimize any and all duplicate inspection reports. However, the dataset may still contain such duplicates and the appropriate precautions should be exercised when viewing or analyzing these data"_. For this reason, we will need to do a further analysis in order to preprocess the provided dataset towards our goals. Also, the Violations column contains detailed but uncategorized information of the inspections, which could be transformed into a more digestible format through pre-processing.

We will try to support our findings with auxiliary information regarding the City of Chicago, such as gross income in the area where the establishment is set. As the City of Chicago has plenty of open source datasets, research will be conducted to find useful information.

# A list of internal milestones up until project milestone 2
_Add here a sketch of your planning for the next project milestone._

- Find out the differences between different inspection types (Canvass, License, etc.).

- Find a resource that allows us plot an accurate map of Chicago, including a division per ZIP Code. This is of vital importance in order to succeed in our map plots, which we believe are crucial for the analysis.

- Gather from external sources as much supporting information as possible, in order to enrich the analysis. This includes the average income per zone in Chicago, a more accurate segmentation of the type of business (e.g.: for restaurants, we could divide them in Italian, Japanese, Mexican or state owned versus privately owned, etc.), or locations of main tourist attractions, among others.

# Questions for TAa
_Add here some questions you have for us, in general or project-specific._

- Is there any popular source to find the map coordinates of regions, such as the per-state USA map used in the tutorials?
- What is a good scope of the project? Are we proposing too many different questions, should we just focus on a particular aspect of the dataset...?
- Are we fulfilling the "social good" requirement?
- Are the analysis tools studied until now enough to achieve a relevant analysis, or should we research on more complex methods or concepts not covered during the course?
