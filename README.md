# Data-analysis-of-Corona-Virus-using-Python
This is a simple data analysis project of ongoing pandmeic diseases COVID-19(Coronoa Virus) which is performed using the different technique in python and machine learning procedure of forcasting . 

# Python Packages Included
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn 

# Machine Learning Package 
1. FBProphet(Time series Forecasting)


# Data Extraction 
For this analysis, data has been taken from the John Hopkins whiting school of engineering repositories(https://github.com/CSSEGISandData). It contains the 3 different sets i.e. Confirmed, Death and Recovered. 

# Data Preprocessing
Python function is created to extract the specific column from the various dataset and later merged using the join function of python. This process is specifically done because there are various column which doesn't have much significance in this analysis. 

# Data Exploration
This is the intial process of datqa analysis where we dive to explore the large datset in an unstructured way to figure out the patterns, characteristics and different interest of the data. Also, data visualzation is done in this part utilizing the different packages of python to determine the feature and characteristics. 

# Time Series Analysis 
Main aim of the project is to analyse the past data to predict the future data. This analysis is utilized because all the data collected are the equal timeframe. For performing this analysis, FBprophet model is utilized. FBProphet is known as Facebook Prophet developed by a facebook using Stan programming lanagauge. This model has been utilized to perform the time series analysis of the covid19
