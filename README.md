# Webscraping-Instagram
It webscrapes data from instagram.

This is python program that automates data collection by web-scraping from Instagram by logging in and generating csv files and making plots by analysing data.

1. Basic work flow of program
2. searches a keyword in instagram(example - "gaming")
3. extract username from search result
4. visits each username
5. extracts number of followers, last 10 post, their captions, likes and date of upload
6. prepare csv and generates plot.

It generates the following results:
1. Generate first csv with following columns : [username, number of followers, likes on first 10 posts, captions on each of the post, number of post done in 3 days, avg likes on last 10 post, avg likes to followers ratio].
2. Generate 2nd csv with frequency of words used in all captions(stopwords have been removed).
3. Generate 3rd csv with hashtags used in all captions from all usernames.
4. Generates plots for 
    1. Top 5 usernames by number of followers
    2. Number of post done in last 3 days
    3. Avg likes on last 10 post
    4. Avg likes to followers Ratio
    5. Pie chart 5 most used hashtags

Libraries used
1. pandas
2. numpy
3. matplotlib
4. seaborn
5. nltk
6. selenium
7. datetime
8. re
9. time 
10.operator
11.collections

