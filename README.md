⚡ Electricity Consumption Trend Analysis and Prediction Using Smart Meter Data 
Data Analysis of Electricity Consumption in Saudi Arabia

📖 Abstract

This project presents an analytical study of electricity consumption patterns using a real-world dataset from Saudi Arabia. The work is developed as part of the ARTI506 course and focuses on applying data analysis techniques to understand electricity demand behavior over time. The notebook integrates data preprocessing, statistical analysis, and feature engineering to extract meaningful insights from the dataset.

🎯 Objectives

The main objectives of this assignment are to:

Analyze electricity consumption data using Python
Identify patterns and trends in electricity demand
Perform statistical and exploratory data analysis (EDA)
Engineer meaningful features to better understand load behavior
📊 Dataset

The dataset is sourced from:

Kaggle (Saudi Electricity Data)

It includes information such as:

Time of reading (ReadingTime)
Electricity load values (ReadingValue)
Historical averages and related features
⚙️ Methodology

The notebook follows a structured data analysis pipeline:

1. Data Loading
Importing dataset using Python libraries
Initial inspection of the data
2. Data Understanding
Data shape and structure
Data types and missing values
Statistical summary
3. Exploratory Data Analysis (EDA)
Understanding distribution of electricity consumption
Identifying trends across time
4. Feature Engineering

Several new features are created to enhance analysis, including:

Hour extraction from timestamp
Momentum (change in load compared to previous hour)
Load ratio (relative change in demand)
Volatility (stability of consumption)
Normalized delta (scaled change in load)
5. Data Cleaning
Removing unnecessary columns
Formatting datetime features
🛠️ Tools and Technologies
Python
Jupyter Notebook
Libraries:
Pandas (data manipulation)
NumPy (numerical operations)
Matplotlib & Seaborn (data visualization)
