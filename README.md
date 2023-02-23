# Web-Scraping

## Background
You’re now ready to take on the full web-scraping and data analysis project for the mission to Mars. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

## Instructions

## Deliverable 1: 
Scrape Titles and Preview Text from Mars News 
Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup) 

The titles and preview text of the news articles were scraped and extracted 

The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries 

## Deliverable 2: 
Scrape and Analyze Mars Weather Data 
The HTML table was extracted into a Pandas DataFrame. Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types 

The data was analyzed to answer all five listed questions, with data visualizations provided when specified 

The DataFrame was exported into a CSV file 

## Results 

Data was scraped from https://redplanetscience.com/

Here are some of the graphs that were produced from the data:

### What are the coldest and the warmest months on Mars?
![image](https://user-images.githubusercontent.com/86980650/220933669-1142d8eb-ce1b-44bb-ba15-3ab558d23ab9.png)
On mars the 3rd month is the coldest and the 8th month is the warmest.

### Which months have the lowest and the highest atmospheric pressure on Mars?
![image](https://user-images.githubusercontent.com/86980650/220933822-bba7f223-da12-4ba2-9ace-6a4952ca673f.png)
The 6th month is the lowest and the 9th month is the highest in terms of atmospheric pressure.

### How many terrestrial (earth) days are there in a Martian year?
![image](https://user-images.githubusercontent.com/86980650/220933842-6d22a8d0-08e0-4c5b-9866-b44b58ce85de.png)
Based on the plot above, it appears that the data spans 2021 Earth days which is equivalent to about 2.5 Martian years.
Using this information, I can estimate that a Martian year is approximately 808.4 Earth days long.


