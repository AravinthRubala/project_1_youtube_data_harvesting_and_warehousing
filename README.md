# DS_YouTube Data Harvesting and Warehouse
YouTube Data Harvesting and Warehousing using SQL, MongoDB and Streamlit
Introduction
YouTube data harvesting involves the systematic collection of data from this sprawling video-sharing platform. We're not just talking about videos, but also user interactions, comments, and more. This rich repository of structured (metadata, metrics) and unstructured (comments, content) data presents us with a goldmine of information waiting to be explored.

Tools Installed
1. Virtual Studio code
2. Jupyter notebook
3. Python 3.11.3 or higher
4. MySQL
5. MongoDB
    
6. Required Libraries    
 pip install google-api-python-client, pymongo, mysql-connector-python, sqlalchemy, mysql workbench, pymysql, pymysql, 
 pandas, numpy, plotly-express, streamlit.

 ( pip install google-api-python-client pymongo mysql-connector-python sqlalchemy pymysql pandas numpy plotly-express 
 streamlit )

7. Import Libraries 
Youtube API libraries

from googleapiclient.discovery import build

File handling libraries

import json

import re

MongoDB

import pymongo

SQL libraries

import mysql.connector

import sqlalchemy

from sqlalchemy import create_engine

import pymysql

pandas, numpy

import pandas as pd

Dashboard libraries

import streamlit as st

from streamlit_option_menu import option_menu

8. ETL Process

a) Extracting the data
Extract the particular youtube channel data by using the youtube channel id, with the help of the youtube API developer console.

b) Transforming the data
After the extraction process, take the required data from the extraction and transform it into JSON format.

c) Loading the data
After the transformation process, the JSON format data is stored in the MongoDB database, also it has the option to migrate the data to MySQL database from the MongoDB database.

9. EDA Process and Framework

EDA, or Exploratory Data Analysis, is a crucial step in the data analysis process that involves summarizing, visualizing, and understanding the main characteristics of a dataset.

a) Access MySQL DB
Create a connection to the MySQL server and access the specified MySQL DataBase by using pymysql library and access tables.

b) Filter the data
Filter and process the collected data from the tables depending on the given requirements by using SQL queries and transform the processed data into a DataFrame format.

c) Data Visualization
Finally, create a Dashboard by using Streamlit and give dropdown options on the Dashboard to the user and select a question from that menu to analyse the data and show the output in Dataframe Table.
User Guide

Step 1. click on Channel list tab.

I have provided 10 channel ids in a table format for my convenience. 

Step 2. Click on channel details tab.

Select any YouTube channel in this dropdown.

Click on channel detail check box - user see the details of the channel with image.

Click on video detail check box - user can able to select one by one radio button and will see the video details with
images.

Step 3. Click on Store data in mongoDB tab.

Select any one of the youtube channel in the dropdown - User can see the channel name.

Click on the store data in mongoDB button - Data has stored in mongoDB

The JSON format data will appear.

Step 4. Click on migrate data to mysql tab.

Select any one of the youtube channel in the dropdown - User can see the channel name.

Click on the migrate data to mysql button - Data migrate from json to mysql.

Step 5. Click on Data Analysis Tab

Select a Question from the dropdown menu and you can get the results and charts in Dataframe format.

YouTube video link:

Linked in link: 
https://www.linkedin.com/posts/syspro-aranvin-41909664_activity-7117568969217085441-gYCgutm_source=share&utm_medium=member_desktop

