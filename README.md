# Trends in Anti-Captivity Sentiment
cs105-prj-phase3-turtle created by GitHub Classroom

# cs105-prj-phase1-turtle

# Getting Datasets 
We are scraping animal data from https://www.montereybayaquarium.org/animals-and-exhibits, which lists all of the animals the 
aquarium holds. 


We have also downloaded the open yelp dataset from https://www.yelp.com/dataset
We will be using this dataset to read the reviews for the Monterey Bay Aquarium and making an analysis with the data we scraped. 

   # Webcrawler
We used Beautiful Soup to scrape our data from https://www.montereybayaquarium.org/animals-and-exhibits, to give us links to the pages of the individual animals. In total, we scraped data from 203 pages. 

Initiailly we would scrape the links to each of the individual animals pages and store that in an array. Then we would loop over that array to scrape the data for each individual animal such as the animal name, scientific name for that animal, and what category the aquarium has the animal in.

   # How to run the code
The code stores all of the data as a pandas dataframe then converts that dataframe into a CSV file within Jupyter Notebook.

In order to run the code, first of all the code must be open on Jupter Notebook since it is saved as a ipynb file.

At the very bottom of the code, you can see the code to convert the dataframe into a CSV file.

You need to have an empty csv file to have our dataframe saved into so,

1.) Create an empty CSV file on your computer such as 'file_name.csv'.

2.) Get the directory name for that file you have just made.

3.) Paste that dictory in quotes into where we have our file path inside of our code. 

Now you can just run all of the code and the webscaper should scrape all of the data, save the data into a dataframe, 
and then save that dataframe into the CSV file you have just made. 


# cs105-prj-phase2-turtle
cs105-prj-phase2-turtle created by GitHub Classroom

   # New Datasets 

We combined the data from Monterey and also scrapped through Yelp at the Monterey Bay reviews site. 
We also aquired Data from google trends, which will be used to compare timelines.

   # Exploratory Data Analysis 

For the EDA our goal is to discover a correlation between key terms found within the yelp reviews to review scores. 

To do this we create 4 groups of itesms which were defined from key words. We looked at the avergae rating per group. 

    Group1: Related to words representing Positive sentiment 
    Group2: Related to words representing Negative sentiment
    Group3: Words related to anti - captivity
    Group4: Overall Average

This does not reveal much as the average reviews stayed mostly consistant between the groups. 

The last thing we looked at was a google trend data set that showed the interest in "Black Fish" over time.

The comparison between the two graphs did not show a correlation to anti-captivity sentiment and average reviews.


   # How to run the code

Make sure the csv files are with in the correct directory (the same directory as the python)

In order to run the code, code must be open on Jupter Notebook since it is saved as a ipynb file.

Run the code, you can change key words to change what words you want to correlate the certain groups.


