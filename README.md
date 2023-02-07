# finalCapstone
A repository for my final capstone project with HyperionDev

## Project name
US Arrests

## Project description

This project analyses a dataset of arrests per 100,000 residents, for assault, murder and rape, in each of the 50 US states in 1973. Also given is the
percentage of the population living in urban areas.

The project:

+ Conducts exploratory data analysis on the variables
+ Conducts correlation analysis on the variables
  + This shows positive correlation between assault, murder and rape, and negative correlation between urban population and all three crimes
+ Conducts principal component analysis, with the data standardised, to reduce the impact of large variations in assault figures
+ Plots the first two principal components, showing one is dependent on the crimes and one is dependent on the urban population
+ Conducts cluster analysis using the first three principal components.

Overall, this analysis shows that states can be clustered in the following way based on their crime data:

+ **Blue states** (higher crime, lower urban population) are mostly in the Deep South
+ **Dark green states** (higher crime, higher urban population) are mostly those with major cities
+ **Light green states** (lower crime, lower urban population) are mostly in the Midwest and North Eastern parts of the US
+ **Red states** (lower crime, low-to-mid urban population) are mostly in the Midwest and North Western parts of the US.

## Table of contents

+ Exploratory data analysis
+ Correlation analysis
+ Principal component analysis
+ Cluster analysis.

## Installation

1. Download both the UsArrests.ipynb and UsArrests.csv files and save them in the same directory
2. Install Jupyter Notebook
3. Install the following Python libraries: NumPy, Pandas, Matplotlib, Seaborn, scikit-learn and SciPy

## Usage

1. Open UsArrests.ipynb in Jupyter Notebook
2. Choose 'Cell' --> 'Run All' from the menu
3. Read the pseudocode, markdown and plots to understand the data analysis and underlying data.

## Credits

UsArrests.csv is taken from Kaggle ([link](https://www.kaggle.com/datasets/kurohana/usarrets)).
