# Project Proposal



**Question/need:**

* What is the framing question of your analysis, or the purpose of the model/system you plan to build?

What are the crowded stations in the borough with the highest crime level as the surveillance level should be increased?


* Who benefits from exploring this question or building this model/system?

The police department as they can increase the number of security
gurads in these stations. Therefore, they can increase the level of
control over these stations and the crime rate will be lower.




**Data Description:**

* What dataset(s) do you plan to use, and how will you obtain the data?

The first dataset is to analyze the rate of crimes in each borough and find the borough with the highest number of crimes, and hours when crimes are likely to occur. It is obtained from NYC open data website.

It is available at https://www.kaggle.com/brunacmendes/nypd-complaint-data-historic-20062019

The second dataset is about NYC Turnstiles Station List. To find the stations located in the borough with the highest crime rate. It is obtained from GitHub.

It is available at http://web.mta.info/developers/data/nyct/subway/Stations.csv

The third dataset is about MTA Turnstile Data.

It is obtained from  http://web.mta.info/developers/turnstile.html




**Tools:**
* How do you intend to meet the tools requirement of the project?

I will ingest the raw data of the datasets into a database and will query the database into pandas dataframe. Exploring and cleaning the data will be done in pandas. After that, I will use python visualization libraries to draw some plots and derive final insights.

* Are you planning in advance to need or use additional tools beyond those required?

I will use the data and tools described above as the ides does not need any additional tools.
