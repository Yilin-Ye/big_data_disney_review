# Big Data Disney Review

Team member: Yilin Ye, Tianying Zhao, Xin Li


## Goal

This project explores all possible relationships in the Disneyland review dataset from various aspects of exploratory data analysis and data visualization, text classification, and sentiment analysis. In this project, we performed preliminary data cleaning and visualization via Pandas and other regular python packages; in addition to that, we built a pipeline via Pyspark and implemented TF-IDF on tokenized reviews to find the association between reviewers' rating scores and their reviews via logistic regression. Finally, we use sentiment analysis to extract their review attitudes from the reviews and explore the relationship between the reviewers' ratings and the true attitudes behind their reviews, which adds a touch of humanity beyond the regression model. 


## Directory
Here you can find a directory to all the files within our repo that were used in performing our analysis.

### [Dataset](https://github.com/Yilin-Ye/big_data_disney_review/tree/main/dataset)
This Folder have the raw data and cleaned data for modeling and sentiment analysis. 

### [EDA](https://github.com/Yilin-Ye/big_data_disney_review/tree/main/EDA)
This folder contains the code for exploratory data analysis on disney reviews and ratings. It explore all kinds of relationships between review, rating, branch. It gives us a rough idea about our future modeling and sentiment analysis.

### [Logistic Modeling](https://github.com/Yilin-Ye/big_data_disney_review/tree/main/logistic_modeling)
This Folder contains notebook for text classification and logistic modeling.

### [Sentiment Analysis](https://github.com/Yilin-Ye/big_data_disney_review/tree/main/Sentiment_Analysis)
This folder contains the code for sentiment analysis on the reviews, it explored the relationship between rating and the sentiment behind the reviews. It give us a more accurate result than logistic modeling on TF-IDF.

### [Slides](https://github.com/Yilin-Ye/big_data_disney_review/tree/main/Slide)
This folder contains the slides for this project.

### [Report]()
This folder contains the report for this project.



## Data Description

The dataset includes 42,000 reviews of 3 Disneyland branches - Paris, California and Hong Kong, posted by visitors on Trip Advisor.

Column Description:

 **Review_ID**: unique id given to each review\
 **Rating**: ranging from 1 (unsatisfied) to 5 (satisfied)\
 **Year_Month**: when the reviewer visited the theme park\
 **Reviewer_Location**: country of origin of visitor\
 **Review_Text**: comments made by visitor\
 **Disneyland_Branch**: location of Disneyland Park



## Dataset Link
https://www.kaggle.com/datasets/arushchillar/disneyland-reviews
