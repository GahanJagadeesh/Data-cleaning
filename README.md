# Data-cleaning
Manipulating data using Pandas to make it easier to analyze.

## Project notebook

You can find the project along with detailed description of each step in this notebook -- [Data cleaning notebook](https://github.com/GahanJagadeesh/Data-cleaning-/blob/master/Data%2Bcleaning%20.ipynb)

## Dataset used

I have used a dataset which is a csv file containing the information of books in a british library. 
The link to this dataset is here -- [Dataset](https://github.com/GahanJagadeesh/Data-cleaning/blob/master/BL-Flickr-Images-Book.csv)

## Libraries

Python's pandas and NumPy was used to perform the cleaning. Pandas is a very powerful library useful for dealing with large data in python. Pandas has a lot of inbuilt methods which are useful for cleaning the dataset.

##  Cleaning messy data
Data cleaning mainly deals with missing data as most real world datasets have tons of missing entries which could cause problems for analysis. The missing entries are usually depicted as NaN values which are simple to detect. But sometimes the data may contain values such as 'n/a' , 'na' , 'Nil' etc. So, the first step would be to convert these values to NaN values and then deal with it.

Some unnecessary columns are better to be dropped as there is no significant information present in those columns. The general norm when we deal with missing data is to include the mean or median as that particular entry. But sometimes, when the entiries are of the form Year, Name etc, It does not make sense to include the mean or median. So, the rows are dropped ( Provided that it is not a significant amount of rows)

The main steps to be followed in cleaning data are:

* Importing data
* Joining multiple datasets
* Detecting missing values
* Detecting anomalies
* Inputing for missing values
* Data quality assurance

