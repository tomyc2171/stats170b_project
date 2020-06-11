# stats170b_project
Data Science Project examining Twitter sentiments and how they correlate with national polls
Made by Sanjith Venkatesh and Tom Young Choi for UCI STATS 170B

project.ipynb -> the main notebook that does the following:
1. Creates a classifier using a training set with supervised labels
2. Classifies tweets made about a candidate (in this case Joe Biden) as 1 (positive), 0 (neutral), or -1 (negative)
3. Calculates weekly averages and changes in sentiments using classified tweets
4. Using 538 polling data, calculates weekly averages and changes in polls
5. Calculates the correlation values between the two changes

data/labels/biden_labels -> contains three csv files containing training data for the classifier. Has 40 Tweets for each class:
1  - positive (sentiment)
0  - neutral
-1 - negative

tweets_full/biden_full.csv -> all Tweets made about Joe Biden from 2015 to March 2020, ready to be classified. 
Queried using full name "joe biden"

president_primary_polls.csv -> FiveThirtyEight polling data for the presidential primaries
