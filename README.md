# Premier_League_Match_Data_Analytics_Pipeline

The following is based on a coding task assigned by a very popular Online Gambling and Sports Match Insights platform.

The overall data pipeline system focuses on the key aspects of extracting, transforming and loading the premier league match data into Snowflake using Python-Snowflake Connector.

The code has been modified since in order to make the data pipeline more efficient and will continue support as required.

# REQUIREMENTS

Python Version:
python==3.9.13
jupyter-notebook==6.4.12

Packages Versions Used:
anaconda==2022.10
conda==22.11.1
pandas==1.44
snowflake-connector-python==2.7.12


Libraries Used:
import pandas as pd
import snowflake.connector
from snowflake.connector.pandas_tools import write_pandas


Location of ‘Fixtures.csv’ file used (In Windows):
C:/Users/username/OneDrive/Desktop/Data_Engineering/Projects/Premier_League_Match_Data_Analytics_Pipeline/Source/Fixtures.csv

Location of generated ‘Standings.csv’ file from standings report dataframe (In Windows):
C:/Users/username/OneDrive/Desktop/Data_Engineering/Projects/Premier_League_Match_Data_Analytics_Pipeline/Output/Standings.csv

Location of context file:
C:/Users/prono/OneDrive/Desktop/Data_Engineering/Projects/Premier_League_Match_Data_Analytics_Pipeline/Source/ATT82825.env

Number of input parameters needed from user: 3

1) year (YYYY): e.g. ‘2022’
2) month: e.g. ‘12’
3) day: e.g. ‘25’


1) Use Jupyter Notebooks to open Scores.ipynb file and execute line by line.

Or

2) Can import function myfunc in Scores.py:

Example:

import scores

a = scores.myfunc(dataframe)
.
.
from scores import myfunc

print(myfunc(dataframe).to_string())

