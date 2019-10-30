## Car-Recommender

### This project is to answer the following questions

* What are the top car sales?
* How many luxury car sales versus non luxury car sales by state?
* What state is it more expensive to purchase a car?
* Are cars cheaper in metropolitan areas as there are more options for public transportation and parking costs are higher?
If I want to buy a used luxury car how much would it cost me?
Are there more convertibles in California and Florida?
Are there more SUVs in the mountain states?

### Data Sources

Kaggle - data of Used Car Sales 
* Each row represents one used car sale
* Data from September 24 2017
* Columns of data include:
* ID – Car identification
* Price – Car Price
* Year - Car Year
* Mileage – Car Mileage
* City 
* State
* VIN Number
* Make – Car Manufacturer
* Model – Car Model

### Tools used for ETL

Jupyter Notebook

### Functions applied

* Str.strip() – used to strip characters from the beginning and end of the string
* error_bad_lines – used to drop bad lines in our data
* Str.upper() – used to make all our values for State uppercase
* Dropna() – used to drop null values
* str.title() – used to convert the first character of each word to uppercase and the remaining to lowercase










