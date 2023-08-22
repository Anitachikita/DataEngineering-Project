# DISNEY+ PROJECT
#### Video Demo:  <URL HERE>
#### Description:

[Disney+](https://logowik.com/content/uploads/images/disney5456.jpg)
## Overview

The Disney+ Project is a data engineering and analysis project that involves extracting, transforming, loading, analyzing and visualizing data from a CSV file containing information about Disney+ database (https://www.kaggle.com/). In this project I perform data analysis and visualize the findings using Python, pandas, SQLite, and Matplotlib. It focuses on exploring the content available on the Disney+ streaming platform and gaining insights into factors such as ratings, genres and more.

For this project I had to get famiar with libraries such as "Pandas" and "Matplotlib". These libraries are very hepful in Data ralated projects.

During the project, I used Jupyter Notebook for its interactive capabilities. Jupyter Notebook helped with step-by-step coding and visualization.

# Contains

- **Visualization** folder with the graphs
- **cleaned_disney_plus_data** transformed and cleaned data
- **disney_plus_titles** original data
- **disney_plus_db.sqlite** sqlite database
- **project.ipynb** mail file, was written in Jupyter Notebook. 

## Technologies used in the project

- Python 3.x
- Pandas library
- Matplotlib library
- SQLite3 (for loading data)
- Jupyter Notebook 

I have installed these dependencies using command:
**pip install pandas matplotlib**

## Extraction
The extraction phase involves reading the input CSV file (disney_plus_titles.csv) using the Pandas library. The **extract_data** function returns the data as a Pandas DataFrame.

## Transformation
The transformation phase involves preparing the extracted data for analysis. The **modify** function converts the date_added column to datetime, calculates the release_year, extracts the numeric part of the duration, and prepares the data for analysis.

## Loading
The loading phase involves loading the transformed data into an SQLite database named disney_plus_db.sqlite. The **into_sqlite** function connects to the database and uses the Pandas to_sql method to load the data.

## Analysis
The analysis phase focuses on extracting insights from the modified data. The **analysis** function calculates the top-rated content and the content with the longest duration.

## Visualization
The visualization phase creates visual representations of the analyzed data. The **visualization** function uses Matplotlib to generate bar plots providing insights into content popularity, ratings and classification of types. 


![Duration](Project/visualization/duration.jpg)

![Types](Project/visualization/types.jpg)

![Views](Project/visualization/views.jpg)


## Conclusion 

By completing this project, I've gained hands-on experience in data engineering process including data manipulation, SQL integration, data analysis, and data visualization. These skills are not only essential for junior data engineering roles but are highly transferable across various data-driven domains.

## Documentation

[Pandas](https://pandas.pydata.org/docs/)

[Matplotlib](https://matplotlib.org/2.0.2/contents.html)

[SQLite](https://www.sqlite.org/docs.html)

[Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/)

