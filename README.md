# Surfs_up
We'll be using Jupyter Notebook and VS Code as well as flask functionality

## Overview of Project

W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

### Purpose
1. Determine the Summary Statistics for June
2. Determine the Summary Statistics for December
3. A written report for the statistical analysis

## Resources

* Python 3.7.6, Visual Studio Code 1.50.1, Jupyter Notebook, Flask, SQLalchemy dependency

## Summary
* I created an SQLite database for my weather API using Pandas & SQLAlchemy and the CSV files provided to create my SQLite database.
* Next step was to create my weather API to do a climate analysis on data stored in the SQLite database previously created. Data was analyzed using SQLAlchemy to perform queries of data. Second to lastly, I used Pandas Dataframes to create graphs using Matplotlib.
* The very last and most interesting step was to create a Flask app to power the weather API. 
My climate analysis Jupyter Notebook was exported as a Python file and then added the required Flask routes to make the app world run properly.

## Challenge Overview
I enjoyed the challenge of using Flask and sql alchemy.  Found SQLite to be very useful tool to stage a Postgres or Mysql deployment/
