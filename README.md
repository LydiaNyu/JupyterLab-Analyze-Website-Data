## Introduction
This is a school data homework to analyze data directly from the Web and to combine data, with the help of beautifulsoup and pandas.  

## Goals
1. "Screen scrape" data from a web site.  
2. Using requests and BeautifulSoup to download and parse html.  
3. Use merge to join DataFrames by a key.  
4. Work with JSON / Use an API.  
5. Use the json module with requests.  

## Content
Part 1 `courses.ipynb` - Combine Sp21 Course Info.  
1. Read the 2021 course schedule into a DataFrame  
2. Read the 2021 course catalog into a DataFrame.  
3. Put together both DataFrames.  
4. Conclusion.  

Part 2 `films.ipynb` - Using an API.  
In this part of the assignment, you'll request data from a server in json format, parse it, and load it into a DataFrame. Using this DataFrame you'll use aggregations to produce a report.  
The data set is composed of films from the Japanese animation film studio, Studio Ghibli.  
It is being served from a mirror of the data on linserv1.cims.nyu.edu. Note, however, that the original data is from https://ghibliapi.herokuapp.com/, which is under an MIT License. This is mirrored so that we do not overwhelm the original data source with requests.  
