# Foundations-of-Computer-Science
Develop a python toolkit for data mining using pandas, numpy, matplolib.pyplot, libraries. 
The workflow is composed by the following steps:

Convert the app sizes to a number/
Convert the number of installs to a number/
Transform “Varies with device” into a missing value
Convert Current Ver and Android Ver into a dotted number (e.g. 4.0.3 or 4.2)
Remove the duplicates
For each category, compute the number of apps
For each category, compute the average rating
Create two dataframes: one for the genres and one bridging apps and genres. So that, for instance, the app Pixel Draw - Number Art Coloring Book appears twice in the bridging table, once for Art & Design, once for Creativity
For each genre, create a new column of the original dataframe. The new columns must have boolean values (True if the app has a given genre)
For each genre, compute the average rating. What is the genre with highest average?
For each app, compute the approximate income, obtain as a product of number of installs and price.
For each app, compute its minimum and maximum Sentiment_polarity
The following part of the exercise must be done only by groups with two or three people
For each app, compute the average number of words in its reviews
For each app, compute its longest review
For each app, compute the ratio between the number of installs and the number of reviews
Cluster the apps according to the major android version (the first two digits — e.g. for 4.0.3 the major version is 4.0)
For each cluster, compute the average date and the last date of an update.
Excluding the free apps, what is the content rating with highest average price?
The following part of the exercise must be done only by groups with three people
What is the genre with the highest total income?
What is the genre with the highest fraction of free apps (over the number of all apps)?
For each rating, compute the average income
For each (Content Rating, Genre) pair, compute the number of reviews and the average rating.
