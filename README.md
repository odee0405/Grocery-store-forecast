# Corporacion Favorita Grocery Chain Sales Analysis and Forecasting 

## Project Description

In this project, the aim is to analyze and forecast sales from a large grocery retail chain in Ecuador called Favorita. The scale of such chain stores requires that their operations are run with great efficiency; efficiency with regard to stocking fast-moving goods. Stock too little of a particular product and demand won't be met, stock too much and shelves will not be emptied quickly enough. Consider that demand for different products fluctuates in different periods and one can grasp how tight their operations need to be. The forecasts from this project can be used to improve the retail chain's performance by aiding in restocking products based on their predicted demand in different periods such as promotions and holidays seasons.  In all, the purpose of this project is to create a compelling analysis and forecast that will enable stakeholders to make data-driven decisions that will lead to success 


| Project  | Project Article | BI Dashboard|
|-----------------|-----------------|-----------------|
|[Jupyter Notebook](https://github.com/odee0405/Grocery-store-forecast/blob/main/Notebooks/Time%20Series%20Project101.ipynb)|[Article](https://www.linkedin.com/pulse/time-series-regression-forecasting-sales-analysis-kwame-asenso-okyere) | [Dashboard](https://app.powerbi.com/groups/me/reports/6fd097ad-85c3-4c34-9c22-09761491d6a7?ctid=4487b52f-f118-4830-b49d-3c298cb71075&pbi_source=linkSharehttps://app.powerbi.com/groups/me/reports/6fd097ad-85c3-4c34-9c22-09761491d6a7?ctid=4487b52f-f118-4830-b49d-3c298cb71075&pbi_source=linkShare) |

## Data Used
#### [Train Dataset](https://github.com/odee0405/Grocery-store-forecast/blob/main/Notebooks/database_Codes_LP3.ipynb)
- Large data retrieved from a SQL database. The training data comprises various components such as dates, store information, product details, promotion data, and sales figures.
#### [Test Dataset](https://github.com/odee0405/Grocery-store-forecast/blob/main/Datasets/test.xlsx)
- The test data set shares the same features as the train data set, except for the "sales" feature, which is omitted.
#### [Transactions Dataset](https://github.com/odee0405/Grocery-store-forecast/blob/main/Datasets/transactions.csv)
- The transactions data set contains information on transactions for each day.
#### [Stores Dataset](https://github.com/odee0405/Grocery-store-forecast/blob/main/Datasets/stores.csv)
- This data set contains information on the stores where sales are happening. It has features such as cluster, city and state.
#### [Oil Dataset](https://github.com/odee0405/Grocery-store-forecast/blob/main/Datasets/oil.csv)
- This data set contains dates and their corresponding oil prices under a feature name 'dcoilwtico'.
#### [Holiday Dataset](https://github.com/odee0405/Grocery-store-forecast/blob/main/Datasets/holiday.csv)
Holiday events with metadata.

### Technologies Used 

#### Analysis and Visualization
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn

#### Stationarity, Modeling, Evaluation & Model Improvement 
- Scikit-Learn
- Statsmodels 

#### Saving models 
- Pickle

## Table of Contents 
- Business Understanding
- Data Understanding
  - Hypotheses
- Data Preparation
  - Data Cleaning
  - Exploratory Data Analysis
  - Hypothesis testing
  - Feature Engineering 
- Modeling
  - Traditional Machine Learning models 
  - Stationarity test
  - Differencing
  - Statistical models
- Evaluation
  - Backtesting

