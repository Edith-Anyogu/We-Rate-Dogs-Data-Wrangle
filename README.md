# We-Rate-Dogs-Data-Wrangle
The data wrangling process follows the following 3 steps:

1. Data Gathering
- The WeRateDogs Twitter archive
- The tweet image predictions
- Additional data from the Twitter API
2. Assessing Data
3. Cleaning Data

1. Gathering Data; this involves getting the data needed. For this Udacity project, I worked with We Rate Dogs Twitter Archive data. The data is split into three parts. one is the csv file at hand, the second part of the data is a tsv file in a html format I downloaded the tsv file using request library in python, third part of the data I used python to extract the data I needed from the tweet-json file provided in the classroom. I used the json file provided in the classroom beacause I have not gotten approval for my twitter developer account.

2. Assessing Data; this the second stage of the data wrangling process. I visually assessed each of the dataset in Microsoft Excel and documented all the issues I detected while scrolling and randomly checking the data, these issues includes columns with predominantely missing values, dog stages split into four columns, source column contains url, non-descriptive column headers and inconsistency in column entries. I also assessed each of the dataset programmatically using python inbuilt functions  and documented the issues detected which includes, incorrect datatypes, missing values in some columns, duplicated image url and inconsistency in column entries.

3. Cleaning Data; for this stage I used the Define, Code and Test strategy to address the issues documented during the assessment stage. The solution for each issue raised was defined,for example the column that has duplicated entries was defined as " Drop duplicate entries", code was written that addressed this issue and it was finally tested using code to ensure that the issue was resolved. One of the important cleaning done was to merge the three dataset to have one master dataset.

## Questions analyzed
1. What is the most frequently used device used for posting tweet?
2. What month are most tweet posted?
3. How many image predictions are not dogs if all three breed predictions are False and how many are dogs if all three breed predictions are true?
4. What is the most popular dog stage?
