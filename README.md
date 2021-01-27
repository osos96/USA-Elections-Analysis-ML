# Introduction to US Elections and Electoral Vote
<hr>
United States of America holds Presidential elections every four years on the 1st of November, this event is regarded as one of the most important political events all over the globe, due to the gravity of the US Political influence.

The United States of America holds Presidential elections in a unique system called "The United States Electoral College".

## Introduction to The United States Electoral College.
<hr>

The United States Electoral College is the group of presidential electors required by the Constitution to form every four years for the sole purpose of electing the president and vice president. Each state appoints electors according to its legislature, equal in number to its congressional delegation (senators and representatives). Federal office holders cannot be electors. Of the current 538 electors, an absolute majority of 270 or more electoral votes is required to elect the president and vice president. If no candidate achieves an absolute majority there, a contingent election is held by the United States House of Representatives to elect the president, and by the United States Senate to elect the vice president.

Currently, the states and the District of Columbia hold a statewide or districtwide popular vote on Election Day in November to choose electors based upon how they have pledged to vote for president and vice president, with some state laws against faithless electors. All jurisdictions use a winner-take-all method to choose their electors, except for Maine and Nebraska, which choose one elector per congressional district and two electors for the ticket with the highest statewide vote. The electors meet and vote in December and the inauguration of the president and vice president takes place in January.

The appropriateness of the Electoral College system is a matter of ongoing debate. Supporters argue that it is a fundamental component of American federalism by preserving the constitutional role of the states in presidential elections. Its implementation by the states may leave it open to criticism; winner-take-all systems, especially in populous states, may not align with the principle of "one person, one vote". Almost 10% of presidential elections under the system have not elected the winners of the nationwide popular vote.



### Sources
* [Wikipedia](https://en.wikipedia.org/wiki/United_States_Electoral_College)
* [Census](https://data.census.gov/cedsci/)
* [CNN](https://edition.cnn.com/election/2020/results/president)
* [Kaggle](https://www.kaggle.com/etsc9287/2020-general-election-polls)


### Datasets
- Election, COVID, and Demographic Data by County [Kaggle](https://www.kaggle.com/etsc9287/2020-general-election-polls) by Ethan Schacht
    
- US Census Data [US Census](https://data.census.gov/cedsci/) by US Census Data

- This dataset is updated on annual basis by US Census Data

- US Census Demographic Data [Kaggle](https://www.kaggle.com/muonneutrino/us-census-demographic-data) by MuonNeutrino
<hr>



# Table of Content :

<hr>

* Introduction to US Elections and Electoral Vote
    - Introduction to The United States Electoral College.
    - Sourses
    - Datasets
* Enabling Widget Extensions in NB
* Importing Libraries
* Defining Functions Used
* Importing Datasets from Local files
* Exploring Imported Datasets
* Preprocessing of Datasets
    - Cleaning, Feature Engineering and Merging Datasets
        - Filtering and simplifing Datasets
        - Defining columns aggregates
        - Fixing aggregating columns formating
        - Pivoting and grouping statistics by state for further analysis
        - Defining Mean and Median columns
        - Joining temp dataframes
        - Merging states with their corresponding electoral collage votes
        - Feature engineering election results column (answer)
        - Pivoting polling data to states
        - Feature engineering calculating sample size
        - Fixing column names
        - Merging both main dataframes and geo locations
        - Creating color column to visualize candidates parties
        - Saving Dataframe for easier recall
    - Exploring Cleaned Datasets
* Statistical Analysis of US Elections
    - Correlation analysis of cleaned data
        - Elimnating Location data columns
        - Setting Graph Style
        - Calculating Correlation
        - Formating Graphical Output 
    - Ploting CDF for confirmed cases counts
        - Income
        - Poverty
        - Unemployment
        - Employment
        - Men
        - Women
* General Data Analysis 
    - Exploratory Data Analysis
    - Total Votes Per State
    - Total Electoral Votes
    - Election total votes & Total Electoral Votes Per US State
    - Election total votes & Total COVID-19 Cases Per US State
    - Election total votes & Total Unemployment Per US State
    - Election total votes & Poverty Per US State
    - Election total votes & Income Per US State
* 3D Geospacial Maps
    - Parsing data to JSON
    - Executing Maps from json file
    - US Elections 2020 VS Income and Total population
    - US Elections 2020 VS Unemployment and Poverty
* Machine Learning Process
    - Subsetting ML Dataset
    - Redefining Categorical Data
    - Cleaning Data and setting Target column
    - Feature selection
    - Splitting Data into Training and Testing Data
    - Defining Pipeline used
        - Average CV score on the training set was: 0.975
        - Using GradientBoostClassifier
    - Fitting Data to the pipeline
    - Appending Results to variable
* Testing ML Model
    - Defining list of results
    - Testing Model nth times
    - Predicting Data
    - Grouping Results
    - Formating Data Output
    - Printing Percentage Result
* Conclusion
* Final Thoughts
