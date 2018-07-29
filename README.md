# discogs-oii
Script for data collection from Discogs


Two types of data collections are described in these scripts. 

- user profile collection: in userProfileCollection, the script describes how to access user names of all users 
who created content on Discogs from discogs.com/contributors. Then, we describe how to make the API to gather data on any given user. 
Finally the data is parsed in DataFrame

- release collection: based on the first data collection, it is possible to create a list of addresses where contributions of all users
can be accessed. Here, all these address are in page_names.csv. Then, in releaseCollection, the script queries the csv file, sends an API call 
to Discogs and parses the results in a Dataframe. 
