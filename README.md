# matplotlib-challenge
# Pymaceuticals

An analysis of a pharmaceutical study that compares the results of several different treatment regiments.  Presented within a Jupyter Notebook with data visualizations built using pandas and Matplotlib.

## Description

As a senior data analyst at a hypothetical pharmaceutical company, Pymaceuticals, I've been tasked with analyzing the results of a study that compared the performance of Pymaceuticals’ drug of interest, Capomulin, against other treatment regimens.  In this study, 249 mice with squamous cell carcinoma (SCC) tumors were treated with a range of drug regimens. Over the course of 45 days, tumor development within these mice was observed and measured.

Having been provided the tumor measurements made over the 45-day time period as well attribute information for each of the mice involved in the study, I have aggregated the data to showcase topline summary statistics of the study as well as a variety of data visualizations aimed at comparing and analyzing the impact of the different drug regimens upon tumor development.

Leveraging a Jupyter Notebook, Python, pandas, and Matplotlib, I have analyzed and organized the data so that it highlights the following:

* Summary statistics of each drug regimen tested
* Bar chart of total observations measured by drug regimen
* Pie chart of the gender composition of the studied mice
* Boxplots comparing the average final tumor volume observed in the 4 most promising treatments
* Line plot tracking the tumor volume of one test subject treated with Capomulin over time
* Scatter Plot testing a possible correlation between measured tumor volume and mouse weight (Capomulin regimen only)

### Dependencies

The latest version of Python, pandas, Matplotlib, and Jupyter Notebook must be installed in order to run the files.
The following .csv files are required (stored in 'Resources' folder):
* Mouse_metadata.csv
* Study_results.csv

## Authors

Daniel Pineda

## Acknowledgments
Pymaceuticals was created as an assignment for the University of California, Irvine Data Analytics Bootcamp - June 2024 Cohort under the instruction and guidance of Melissa Engle (Instructor) and Mitchell Stone (TA).
The practical exercises and coding examples demonstrated through the bootcamp helped inform and inspire the code for this project.

In addition, the following resources were used for further reference:
* Xpert Learning Assistant - UCI's AI-powered learning assistant - referenced for how to effectively use the duplicate() method in pandas
* [Introduction to Pandas - Pythia Foundation](https://foundations.projectpythia.org/core/pandas/pandas.html) - referenced when debugging 'InvalidIndexError'
* [How to get a single value as a string from pandas dataframe - Stack Overflow](https://stackoverflow.com/questions/53255796/how-to-get-a-single-value-as-a-string-from-pandas-dataframe) - referenced for how to use the values() method in pandas when working with a DataFrame