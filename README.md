# Applied Data Science Capstone Project

This repository contains the code and report for the Applied Data Science Capstone Project, as part of the IBM Data Science Professional Certificate on Coursera.\

## Objective

The objective of this project is to use data science techniques to solve a real-world problem. The problem chosen for this project is to predict the severity of accidents based on various features such as location, weather, road conditions, etc.

## Dataset

- Data was collected using Space X API
- Web scraping from Wikipedia

## Data collection Methodology

- The response content was decoded as a JSON using the ".json()" function and then transformed into a Pandas dataframe using ".json_normalize()".
- Data cleaning was done next, which involved checking for missing values and filling them in where necessary.
- Web scraping was also performed from Wikipedia for Falcon 9 launch records using BeautifulSoup.
- The aim was to extract the launch records as an HTML table, parse the table, and convert it to a Pandas dataframe for further analysis.

## Perform data wrangling
One-hot encoding was applied to categorical features

## Perform exploratory data analysis (EDA) using visualization and SQL

## Perform interactive visual analytics using Folium and Plotly Dash

## Perform predictive analysis using classification models
The data that was gathered until this point was processed through a normalization technique to ensure consistency across the data. The dataset was then divided into training and test sets to train and evaluate different classification models. The accuracy of each model was assessed using various combinations of parameters. Overall, four different classification models were evaluated during this process.

## Code

The code for the project is contained in the **'notebooks'** directory. There are several Jupyter notebooks that correspond to the different parts of the project. The notebooks are:

- **01_jupyter_labs_data_collection_api_spacex.ipynb**
- **02_jupyter_labs_data_collection_webscraping_wikipedia.ipynb**
- **03_jupyter_labs_data_wrangling.ipynb** (Perform data wrangling)
- **04_jupyter_labs_eda_sql.ipynb** (Perform exploratory data analysis (EDA) using SQL)
- **05_jupyter_labs_eda_dataviz.ipynb** (Perform exploratory data analysis (EDA) using visualization)
- **06_jupyter_labs_launch_site_location.ipynb** (Perform interactive visual analytics using Folium)
- **07_jupyter_labs_machine_learning_prediction.ipynb** (Perform predictive analysis using classification models)
- **08_dash_app.py** (Perform interactive visual analytics using Plotly Dash)

##Report

The report for the project is contained in the report directory. The **'report'** is in the form of PDF presentation and contains a detailed explanation of the project methodology and results.

##Conclusion

This project demonstrates the application of data science techniques to solve a real-world problem. The trained machine learning models can be used by stakeholders to predict the severity of accidents and take appropriate action to mitigate their effects.
