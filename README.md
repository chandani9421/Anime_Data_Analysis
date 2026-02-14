#Anime Data Analysis Project

This project focuses on analyzing an Anime dataset using Python and Pandas.
The goal of this project is to perform data cleaning, feature engineering, and exploratory data analysis (EDA) to extract meaningful insights from raw text-based data.

This project demonstrates practical data science skills such as:

.Data wrangling
.String manipulation
.Feature engineering
.Date-time processing
.Exploratory analysis

Project Workflow
1 Data Loading & Exploration
Loaded dataset using pandas.read_csv()

Used:
head()
tail()
info()
To understand structure and data types.


2️ Feature Engineering
 Extracting Number of Episodes

Created a custom function to extract episode count from the title string.
Cleaned text (" eps" removed).
Converted the column into integer type.

3️ Exploratory Data Analysis

Performed insights such as:
Anime with highest score
Top 5 highest rated anime
Anime with maximum episodes
Longest running anime (based on months)
