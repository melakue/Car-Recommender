## Car-Recommender

#### Jupyter Notebook and Google API are used to analyze used car sales data from Kaggle and answer the following questions

* What are the top car sales?
* How many luxury car sales versus non luxury car sales by state?
* What state is it more expensive to purchase a car?
* Are cars cheaper in metropolitan areas as there are more options for public transportation and parking costs are higher?
* If I want to buy a used luxury car how much would it cost me?
* Are there more convertibles in California and Florida?
* Are there more SUVs in the mountain states?

### Data Sources

Kaggle - data of Used Car Sales 
* Data from September 24 2017
* Columns of data include:
  * ID – Car identification
  * Price – Car Price
  * Year - Car Year
  * Mileage – Car Mileage
  * City 
  * State
  * Make – Car Manufacturer
  * Model – Car Model

### Tools used for the project

Jupyter Notebook and Google API

### Functions applied

* Str.strip() – used to strip characters from the beginning and end of the string
* error_bad_lines – used to drop bad lines in our data
* Str.upper() – used to make all our values for State uppercase
* Dropna() – used to drop null values
* str.title() – used to convert the first character of each word to uppercase and the remaining to lowercase
 
### Visualizations

![Image description](https://github.com/melakue/Car-Recommender/blob/master/Pie%20chart%20for%20lexury.png)
![Image description](https://github.com/melakue/Car-Recommender/blob/master/No%20of%20luxury%20cars%20sold%20by%20state.png)
![Image description](https://github.com/melakue/Car-Recommender/blob/master/No%20of%20non%20luxury%20%20cars%20sold%20by%20state.png)
![Image description](https://github.com/melakue/Car-Recommender/blob/master/Pie%20chart%20for%20lexury.png)
![Image description](https://github.com/melakue/Car-Recommender/blob/master/lux%20vs%20non%20lux%20pie.png)
![Image description](https://github.com/melakue/Car-Recommender/blob/master/Average%20Price%20per%20make.png)
![Image description](https://github.com/melakue/Car-Recommender/blob/master/Car%20sales%20heatmap.JPG)






















