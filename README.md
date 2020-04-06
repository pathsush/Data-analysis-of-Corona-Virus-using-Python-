# Data-analysis-of-Corona-Virus-using-Python
This is a simple data analysis project of ongoing pandemic diseases COVID-19 (coronavirus) which is performed using the different techniques in python and machine learning procedure of forecasting. 

# Python Packages Included
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn 

# Machine Learning Package 
1. FB Prophet (Time-series Forecasting)


# Data Extraction 
For this analysis, data has been taken from the John Hopkins whiting school of engineering repositories(https://github.com/CSSEGISandData). It contains 3 different sets i.e. Confirmed, Death, and Recovery. 

# Data Preprocessing
Python function is created to extract the specific column from the various datasets and later merged using the join function of python. This process is specifically done because there are various columns which don't have much significance in this analysis. 

# Data Exploration
This is the initial process of data analysis where we dive to explore the large datasets in an unstructured way to figure out the patterns, characteristics and different interests of the data. Also, data visualization is done in this part utilizing the different packages of python to determine the feature and characteristics. 

# Time Series Analysis 
The main aim of the project is to analyze past data to predict future data. This analysis is utilized because all the data collected are an equal timeframe. To perform this analysis, the FBprophet model is utilized. FBProphet is known as Facebook Prophet developed by Facebook using Stan programming language. This model has been utilized to perform the time series analysis of the covid19
