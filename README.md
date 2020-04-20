# udacity-data-analysis-project2
Udacity - Data Analysis Nanodegree - Project 2: Explore a dataset

## About this Project

This project is part of Udacity's Data Analyst Nanodegree. In this project, a dataset was provided by Gapminder World and displays information regarding how people live their lives in different countries.

## Getting Started

There are several indicators available, and in this analysis, three were selected: Life Expectancy in years, Child mortality per 1000 born and income per person in dollars. The following questions will be addressed after the Assessing and Cleaning data processes.

  - What is the correlation between Life Expectancy and Child Mortality?
  - How did Child Mortality evolve in the six continents?
  - Which continent has the lowest percentage change in Child Mortality?
  - What is the correlation between Life Expectancy and Income Per Person?
  - How Income Per Person evolve in Europe in comparison to the Americas?
  - By how much did Child Mortality reduce in the Americas.

### Files

In the project directory, there are some files. One is the Jupyter notebook where the code is written. The other files are the countries' data related to the analysis. 

### Running the code

To run this project you should have a local server running with Jupyter Notebook installed (you can use [Anaconda](https://www.anaconda.com/distribution/))

The Jupyter notebook is filled with two types of cells, markdown and, code. To run the cells press shift + return and then check the results if there is any to be shown.

#### Adding more countries'

If you want to add more countries, update the following variables and function adding new country/countries' names:
```
countries = ['angola', 'argentina', 'australia', 'brazil', 'cameroon', 'china', 'egypt', 'france', 'finland', 'germany', 'italy', 'japan', 'mexico', 'south_africa', 'spain', 'usa']
```
Also add the new countries' names to the frames variable:
```
frames = [angola, argentina, australia, brazil, cameroon, china, egypt, france, finland, germany, italy, japan, mexico, south_africa, spain, usa]
```
The analysis is also performed by the continent. Remember to add the country/countries' to the correct continent:
```
def cont(c):
    if c['country'] in ['Japan', 'China']:
        return '1'
```

### Built With 

[Python Pandas](https://pandas.pydata.org/) - To manage csv files 

[Numpy](https://numpy.org/)

[Matplotlib](https://matplotlib.org/)

## Authors
Eduardo Domingues - [Git](https://github.com/eduardopd)
