# Semantic Analysis of Brexit Tweets

# Contributors
## Cant't tame that Python (Hannah Frank, Yvonne Gassner, Manuel Prammer)

## Description
For our Semester Project for the lecture STML we want to train a model to predict the semantic of Tweets. 
The data we have are Tweets from accounts that openly stated their oppinion to the Brexit in their Bio.
We want to get the overall semantic of each camp (Anti-Brexit or Pro-Brexit)


## About the dataset
The dataset consist of over 19.000 datapoints and it was collected as part of a master thesis. Each datapoint represents a Tweet. All of the collected Tweets are sorted into two lists: One for all the Tweets posted by users which stated publicly that they are Anti-Brexit and One list for all the Tweets made by Pro-Brexit users.

Date: The date of the tweet

~~Headline: No info available~~

URL: The URL to the Tweet/Repost

~~Opening Text: No info available~~

Hit Sentence: The main sentence of the tweet.

Source: From which social media it is posted

Influencer: The @ username of the user

Country: Where the tweet was posted

Subregion: The subregion where the tweet was posted

Language: The language of the tweet

Reach: The number of people who see the post of the user

~~Desktop Reach: No info available~~

~~Mobile Reach: No info available~~

Twitter Social Echo: A key number that shows the extent to which a story resonates with the target group on Twitter

Facebook Social Echo: A key number that shows the extent to which a story resonates with the target group on Facebook

Reddit Social Echo: A key number that shows the extent to which a story resonates with the target group on Reddit

National Viewership: 

Engagement: The number of interactions your content received from users

AVE: Advertising Value Equivalent. It attempts to assign a monetary value to the coverage a company or brand receives through various media channels

Sentiment: One of the three sentiments a tweet can have (negative, positive or neutral)

Key Phrases: Short, simple descriptors that people would type into search engines 

Input Name: refer to a field or column where users input or enter specific names, keywords, search criteria, or filters to conduct searches or queries within the system.

Keywords: These are the words used to sort whether the user is pro or anti brexit

Twitter Authority:  It's a measure of how much impact or recognition a user has among their followers, the Twitter community, or within a particular niche or industry

Tweet Id: the id of the tweet

Twitter Id: Each object within Twitter - a Tweet, Direct Message, User, List, and so on - has a unique ID

Twitter Client: Shows which client is used to post on twitter

Twitter Screen Name: The name that is shown as the name of the user

User Profile Url: The link to the profile of the user

Twitter Bio: The Content of the Biography of the user

Twitter Followers: How many followers the user has

Twitter Following:  How many other account the user follows

Alternate Date Format: Month Day, Year

Time: the time of the post

State: State where the user lives

City: City where the user lives

~~Document Tags: No info available~~



We just need the semantic of a Tweet as label and the content of the Tweet itself to train the model.

## Experiment Procedure:
Exploratory analysis
Data preprocessing and feature engineering
Model training and evaluation
Model inspection


## License
CC0: Public Domain

No Copyright

The person who associated a work with this deed has dedicated the work to the public domain by waiving all of his or her rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.
You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission. See Other Information below


## Thanks to:
VISALAKSHI IYER - Creator of the dataset

https://www.kaggle.com/datasets/visalakshiiyer/twitter-data-brexit/data


## For Questions
Contact us:

cc221009@fhstp.ac.at - Hannah Frank

cc221037@fhstp.ac.at - Yvonne Gassner

cc221002@fhstp.ac.at - Manuel Prammer
