# Frederic Petit's Data Analysis Portfolio
Google Data Analysis Professional Certificate

Ask, Prepare, Process, Analyze, and Share are the 5 phases of the data analysis process

[Bio on LinkedIn](https://www.linkedin.com/in/fredericpetitusa/)

[Content of my portfolio on GitHub](https://github.com/Fredo68usa/portfolio/blob/main/index.md)

# Capstone project #1 : Divvy Bike

## Description 
The Capstone project is the hands-on project to be completed at the end of the Google course for Data Analysis Professional Certificate.

You can bring this project as far as you want to.

In this case, we have used some the tools presented in the course,<b> Google Sheets and R </b>, We have left aside SQL and Tableau. We have also limited the data to 1 month (April 2020). It's always better to start small to build the process and if satisfying to exapnd it to larger amount of data. We think we were able to come up with a pertinent approach. To expand it to larger volumes requires a different set of tools capable of hosting laerge volume. We think  the best tool is either ELK or SQL + Tableau on GCP BigQuery or R on Spark.

We will present at a later stage such implementations. Our goal is to ultimately offer different types of implementation for Data Analysis projects by our Open Source project turned into our Context22 start-up.
≈
## Divvy Bike Chicago
Divvy is a bike sharing system managed by the City of Chicago.

## Data Set 
Provided by Divvy Bike

## Approach
Despite the project providing an high level requirement document, we prefer the approach to get the data without direction and get all insights we can. We avoid setting a direction and limiting the meaning the data have. At the very end of the project, we can have a look at the requirement but our analysis should cover them or it is incomplete and has missed a major point.

We followed the Google-designed approach : Ask, Prepare, Process, Analyze, Share.
- <b>Ask</b> : We asked ourself all along as we were discovering. In particular it showed us what additional data would be needed.
- <b>Prepare</b> : The data had a lot of redundancy and it's why the data were so large, making them more difficult to manipulate. We fixed this by implementing a data model. We used Speredsheets, Tableau and R but Kibana as well that was easier to use. Kibana is still our tool of choice, followed by R.
- <b>Process</b> : The data were pretty clean already and didn't have much cleaning work to do
- <b>Analyze</b> : 
- <b>Share</b> : We split the presentation in 2: The Findings and Recommendations vs. The Making of the Analysis.

  
## Presentation of Findings
[Presentation](https://github.com/Fredo68usa/portfolio/blob/511f4cc1f2289cec6ab30819e2f8c8321208ed63/DIVVY%20Chicago.pdf)
[Tableau](https://public.tableau.com/views/DivvyStationGeoLocation/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link) 

Note: the version I have for Tableau doesn't (Tableau Public Web) does not allow for nice Dashboard features. When I'll have a chance to get a better version I'll put a better Dashboard

## Presentation of the Making of this Analysis
In this [presentation](https://github.com/Fredo68usa/portfolio/blob/main/The%20Making%20of%20Divvy%20Bike%20Data%20Analysis.pptx), we describe the technical aspects of the project

## R notebook 
- on [Kaggle] (https://www.kaggle.com/code/fredolino68/capstone-project)

- on [GitHub] (https://github.com/Fredo68usa/portfolio/blob/main/DivvyNB.Rmd)


# Capstone project #2 : London Housing
## Description 
In this project, there is no requirement provided, only the data set. This is the case I prefer because you need to find out whatever may be there. 

## Data Set
[Housing in London](https://www.kaggle.com/datasets/justinas/housing-in-london)

## Approach
We followed the Google-designed approach : Ask, Prepare, Process, Analyze, Share.
- <b>Ask</b> : London is experiencing an housing crisis. Can we see how it manifests in London and maybe see options
- <b>Prepare</b> : We downloaded the 2 data sets and uploaded them into Elastic Search and R-Studio
- <b>Process</b> : we cleaned up the data (na replacement, removed irrealistic data for years 1999, 2000 & 2019. Also a announced variable (number of houses sold) was missing
- <b>Analyze</b> : in Kibana we created vizs showing changes in differentiation by borough and in R we tried to figure out correlations od interest
- <b>Share</b> : see our pdf presentation

## Presentation of Findings
[Presentation](https://github.com/Fredo68usa/portfolio/blob/511f4cc1f2289cec6ab30819e2f8c8321208ed63/DIVVY%20Chicago.pdf)

## Presentation of the Making of this Analysis
In this presentation, we describe the technical aspects of the project (in progress)

## R notebook 
(in progress)

# Dell Twitter Sentiments
[Data set : ](https://www.kaggle.com/datasets/ankitkumar2635/sentiment-and-emotions-of-tweets)
See the computation in the [Spreadsheet](https://github.com/Fredo68usa/portfolio/blob/main/DellEmojiTwitter.xlsx)
# 
