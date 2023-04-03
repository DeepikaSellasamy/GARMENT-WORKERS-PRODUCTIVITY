# GARMENT-WORKERS-PRODUCTIVITY

#### OBJECTIVE:

This project aims to build a machine learning model to predict the productivity of garment workers based on various factors.The project will use Python, a popular programming language for data analysis and machine learning.

#### DATASET:

The dataset contains more than 1,000 rows and 15 columns.

Attribute Information:

date : Date in MM-DD-YYYY

day : Day of the Week

quarter : A portion of the month. A month was divided into four quarters

department : Associated department with the instance

teamno : Associated team number with the instance

noofworkers : Number of workers in each team

noofstylechange : Number of changes in the style of a particular product

targetedproductivity : Targeted productivity set by the Authority for each team for each day.

smv : Standard Minute Value, it is the allocated time for a task

wip : Work in progress. Includes the number of unfinished items for products

overtime : Represents the amount of overtime by each team in minutes

incentive : Represents the amount of financial incentive (in BDT) that enables or motivates a particular course of action.

idletime : The amount of time when the production was interrupted due to several reasons

idlemen : The number of workers who were idle due to production interruption

actual_productivity : The actual % of productivity that was delivered by the workers. It ranges from 0-1.

#### PROJECT:

The project will use various machine learning algorithms such as linear regression, decision trees, and XGBoost to predict the productivity levels of garment workers based on the available data. The performance of the machine learning models will be evaluated using various metrics such as  root mean squared error, and R-squared.

#### APPROACH:

The Python analysis could involve data cleaning, manipulation, and visualization. The steps involved in analyzing garment workers' productivity using Python could include:

Data collection: The first step would be to collect the data from various sources and prepare it for analysis.

Data cleaning: The data collected might have some errors or missing values. The data would be cleaned by removing the errors and filling in the missing values.

Data manipulation: The data would be manipulated using Python's Pandas library to calculate the productivity metrics and create new features.

Data visualization: The productivity metrics would be visualized using Python's Matplotlib library, creating different types of charts such as bar charts, line charts, pie charts, etc.

Statistical analysis: The productivity data could be subjected to statistical analysis using Python's NumPy library to determine statistical significance and identify trends.

#### CONCLUSION:

The ML algorithm that perform the best wasRandom Forest Regressor Model with better R squared value.




