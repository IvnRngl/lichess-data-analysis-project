# Lichess Data Analysis Project

## Description

This a data analysis project where I gather simple statistics from the Lichess November, 2023 database.

I use csv's, SQL and Python. All the relevant code as well as step-by-step descriptions are in the notebook.ipynb file.

Finally, the main.pdf file (made with LaTeX) shows visualizations of key insights.

## Process

Lichess makes their database of games available [here](https://database.lichess.org/).

First I downloaded the pgn file for November of 2023.

I used pyhton's chess library to parse through the pgn, extract individual games and save only the useful metadata in a MySQL table.

With SQL code and VScode plugins I created useful csv files.

Finally, with python and pandas dataframes, I answered simple questions regarding the games played on November First.

## Clarifications

Due to size limitations on GitHub, I can't upload the entire csv file for all games played on November First. Instead I uploaded a compressed version of a pickle file without the last couple of hours. However, the notebook.ipynb file still shows the method to get the same data I used.
