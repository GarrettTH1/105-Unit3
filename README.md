# 105-Unit3
This repository contains datasets, a visualization and a Jupyter Notebook used for an english project.

## The Data

Within the [Data](https://github.com/GarrettTH1/105-Unit3/tree/main/Data) folder there are two datasets and a visualization of the data.

The [2014-2015 County Public Health dataset](https://github.com/GarrettTH1/105-Unit3/blob/main/Data/CountyHealthData_2014-2015.csv) was provided for the assignment and contains a wealth of data about a number of public health factors from counties all across the country.

The [second dataset](https://github.com/GarrettTH1/105-Unit3/blob/main/Data/county_health_data_2014-2015_condensed.csv) with condensed at the end is a subset of the original dataset created using two major processes

1. The dataset was cut to include only data from North Carolina
2. The around 60 columns of data were reduced to around 15 columns. Mostly related to measures of mental and physical health, insurance, income, and exercise.

The [.ipynb Jupyter Notebook](https://github.com/GarrettTH1/105-Unit3/blob/main/Compiling.ipynb) contains the code used to create the subset from the original dataset and instructions to carry out the same or similar subsetting. The notebook can be previewed here or downloaded and opened in Jupyter Lab through Anaconda. [Anaconda Install](https://www.anaconda.com/products/distribution)


## The Subset

This data subset was created in order to analyze a number of factors to see how they impact or correlate with health in North Carolina. The instructions in the Python Notebook should also enable anyone to create a subset with any states, counties, and factors of their choosing.

This particular subset includes mostly data about a counties socioeconomic factors and things like access to exercise, quality of food, insurance information, and health outcomes that might be impacted by those factors. Below is an example of a potential conclusion that can be drawn from this dataset.



# Data Visualization
This scatterplot shows the correlation between average income in a county and the number of premature deaths in the county. This was created using the compiled version of the 2014-2015 health data.

![Scatterplot](/Data/Scatterplot.png)
