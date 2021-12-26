# EDA Project Proposal


## Backstory

New York has the highest population density of any major city in the United States. Recently, the crime figures are threatening to undermine the sense of safety according to police statistics. 

## Question/need:

**What is the framing question of your analysis, or the purpose of the model/system you plan to build?**

This project helps the police department to find the most dangerous stations in NYC so they can increase the level of surveillance over these stations and the areas nearby so that the crime rate will be lower.

**Who benefits from exploring this question or building this model/system?**

The police department as they can increase the number of security
gurads in these stations.



## Data Description:

**What dataset(s) do you plan to use, and how will you obtain the data?**

The [first dataset](https://www.kaggle.com/brunacmendes/nypd-complaint-data-historic-20062019]) is to analyze the rate of crimes in each borough and find the borough with the highest number of crimes, and hours during which crimes are likely to occur. It is obtained from NYC open data website.

The [second dataset](http://web.mta.info/developers/data/nyct/subway/Stations.csv) is about NYC Turnstiles Station List. To find the stations located in the borough with the highest crime rate. It is obtained from GitHub.

The [third dataset](http://web.mta.info/developers/turnstile.html) is about MTA Turnstile Data. 




## Tools:
**How do you intend to meet the tools requirement of the project?**

The following libraries will be used in order to successfully complete the project.
* Numpy and pandas to perfom data manipulations.
* Matplotlib to plot visulalizations
* Sqlite3 to create a local database
* SqlAlchemy to query the database.
