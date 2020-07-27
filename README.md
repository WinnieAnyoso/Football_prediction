# Football_prediction

# 1. a)Defining the question
You have been recruited as a football analyst in a company - Mchezopesa Ltd and tasked to accomplish the task below.

A prediction result of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly (include rank in your training).

You have two possible approaches (as  shown below) given the datasets that will be provided

Input: Home team, Away team, Tournament type (World cup, Friendly, Other)

## Approach 1: Polynomial approach

What to train given:

Rank of home team
Rank of away team
Tournament type
Model 1: Predict how many goals the home team scores.

Model 2: Predict how many goals the away team scores.

## Approach 2: Logistic approach

Feature Engineering: Figure out from the home team’s perspective if the game is a Win, Lose or Draw (W, L, D)

# 2. Metrics for success

The analyses requires us to come up with an accurate prediction model for the home and away scores based on their previous scores and previous rankings. 
We have to identify the key mettrics that can be used to determine this. 

We will then implement the solution by performing polynomial and logistic regression and make predictions
 
# 3. Context

A more detailed explanation and history of the rankings is available here: [Link (https://en.wikipedia.org/wiki/FIFA_World_Rankings)] 

An explanation of the ranking procedure is available here: [Link (https://www.fifa.com/fifa-world-ranking/procedure/men)]

Dataset Columns

Some features are available on the FIFA ranking page [Link (https://www.fifa.com/fifa-world-ranking/ranking-table/men/)].


# 4. Experimental Design 

1) Business Understanding: This should give a clear understanding of the data and business in question in order to make conclusive summaries and approaches in tackling the research problem at hand.

2) Reading the data: Reading our data with and aim to understand the variables and observations. 

3) Checking our data: This to get details about the dataset, the number of records, the statistal summary,the datatypes in our dataset among others.

4) Tidying up the data (Data cleaning): This was to drop unnecesaary columns, delete duplicate records, get rid of any null values, merge dataframes if need be etc.

5) EDA, the data was analysed, visualized and conclusions were then drawn.

6) Implementing the solution using Logistic and polynomial regression.

* Check of multicollinearity

* Start building the model

* Cross-validate the model

* Compute RMSE

* Create residual plots for your models, and assess their heteroscedasticity 

* using Bartlett’s test

* Perform appropriate regressions on the data including your justification

7) Challenge your solution by providing insights on how you can make improvements.
Dataset

# 5.Appropriatenes of the data

The data source is from fifa world rankings from 1993 and results of the matches are way back from the 19th century. The data is updated year up until late last year(2019) when the most recent rankings were made hence the data is up to date and relevant in making conclusive analyses.

