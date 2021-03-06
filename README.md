# Disney-Movie-Analysis
End to End analytics project for top disney movies

## Data Collection  
* Scraped Disney Movie data from Wikipedia [here](https://en.wikipedia.org/wiki/List_of_Walt_Disney_Pictures_films)
* Collected additionaldata from OMDB API for every title and attached to the data.   

## Data Cleaning  
* Cleaned data using Python and Regex
* Dropped around 20 columns as they all had almost 99% Null values
* Parsed out the main monetary values of different formats from Budget and Box-Office columns using several regexes together.
* Cleaned other columns like Running time and Imdb-rating and then converted their data-types to numeric.   

## Exploratory Data Analysis  
* Analyzed Trends, distributions in the data.  
* Performed some Descriptive and Basic inferential statistic on data (like building 95% CI's).  
* One important find was that mean running time of Disney movies lies between 95.37 minutes to 99.07 minutes 95% of the time.  
* Visuals from python were reproduced in Tableau to show in a Business setting with story, a few visuals are -- 
    
    ![BudVsBo](https://github.com/Dvboi/Disney-Movie-Analysis/blob/master/Tab_viz/Screenshot%20(45).png)   
        
        ![IMDB](https://github.com/Dvboi/Disney-Movie-Analysis/blob/master/Tab_viz/Screenshot%20(46).png)
        
         
           
           ![TRENDS](https://github.com/Dvboi/Disney-Movie-Analysis/blob/master/Tab_viz/Screenshot%20(47).png)   
              
              
