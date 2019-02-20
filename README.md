# ETL Project:
Extract AirBnB CSV and scrape Craigslist apartment listings/ combine datasets and load to MongoDB &amp; MySQL


## Extract & Transform:
* View how to leveraged ChromeDriver and scraped Craigslist apt listings [here](Craigslist_Scrape.ipynb)
* [Here](AirBnB_Craigs_Merge.ipynb) is how I cleansed the AirBnB 2018 San Francisco listings CSV and merged it with the Craigslist data 

#### Source of data extracted: 
* CSV and HTML

#### Type of transformation needed for data: 
* Cleaning data by extracting unnecessary characters, converting d-types, renaming neighborhoods & removing rows missing data points
* Merging 2 dataframes, converting to dictionary & creating unique key's


## Load:
* [Here](Load_Data.ipynb) is the code I used to load my final dataframe & dictionary into MySQL and MongoDB + export to Excel!

#### Type of final production database:
* Relational: MySQL
* Non-Relational: MongoDB

Below is the path for my Excel spreadsheets:
* [Craigslist Data](Craigslist_Data.xlsx)
* [AirBnB CSV](AirBnB_SF.csv)
* [AirBnB + Craigslist Data](AirBnB_Craigs_Data.xlsx)

### *Goal:*
* Is there any correlation between AirBnB nightly prices and Craigslists apartment listings monthly rent? 
    * By neighborhood? 
    * By size? 
    



    
