# Analysis-and-Classification-based-on-Upvotes

Problem statement:
With given data set, 
1. perform analysis and data visualization
2. predict the upvotes for the test title.

Input:
Given a dataset with 7 attributes and a target variable. 

Data Analysis:
Target variable is the upvotes and out of 7 attributes, around 3 attributes are trivial because there are no significant values available.
The attributes with details are given below
down_votes = 0, over_18=mostly is False except for a very few True values and category=World news
Data types of the attributes are analysed to check if other attribute requires conversion.
Null values were checked for the attributes and found there are no missing or null values resulting in clean data.

Analysis on Title and Upvotes:
Number of words per title is analyzed and maximum/average words per title is computed.
Also, top ranked titles along with their counts is plotted. 
In addition, titles with its corresponding upvotes is plotted.
Titles is the only significant feature that is considered for analysis and prediction.

Ngram:

Classification:
Different classifiers are tried to verify the accuracy and error values.
Classifiers include



