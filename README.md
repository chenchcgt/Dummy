# Dummy
Dummy


# Machine Learning Models
## Data 
- Kaggle's Medical Cost Personal Datasets
https://archive.ics.uci.edu/ml/datasets/Estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition+
- UCI's Estimation of obesity levels based on eating habits and physical condition Data Set
https://www.kaggle.com/mirichoi0218/insurance
## Background
Obesity is a common, serious, and costly disease. CDC estimates the prevalence of obesity was 42.4% in 2017~2018. The estimated annual medical cost of obesity in the United States was $147 billion in 2008 US dollars; the medical cost for people who have obesity was $1,429 higher than those of normal weight.
Our machine learning models aim to use attributes such as eating habits (e.g. alcohol consumption, number of main meals) and physical condition (e.g. physical activity frequency) to predict if someone is obese as well as the potential annual medical costs. 
## Methodology
- Linear regression and random forest models were used.
- To run the models, categorical predictors were converted to dummy variables, the data was scaled ten split into test and train sets. 
- For the random forest model, the categorical outcome was encoded for the analysis.
### Model 1: Linear Regression
#### Obesity 
- Height and weight variables were removed as predictors because these are used for body mass index (BMI) calculations.
- The model had a training score of 0.50 . When attempting to improve the model by building a simpler model, the training score decreased to 0.40. 
#### Medical Costs
- The model had a training score of 0.75.
### Model 2: Random Forest
#### Obesity
- using the training features and labels, the score was 0.99. 
#### Medical Costs
- using the training features and labels, the score was 0.98. 
Between these two models, randrom forest performed better than linear regression. The random forest model was used for our web application.
## References
Centers for Disease Control and Prevention https://www.cdc.gov/obesity/data/adult.html 

# Data Visualizations
## Data
- Health Data Org (US Data - United States - Life expectancy, obesity, and physical activity)
http://www.healthdata.org/us-health/data-download
##Background
Explain through visualizations, analysis are performed to understand the relationship between Life Expectancy, Obesity, and Physical Activity Levels by gender. 
In addition, a walk through the progression by year for better understanding and comparison between timelines. 
### Life Expectancy - Geomap
- uncover the life expectancy throughout the spam of 25 years if increasing or decreasing, demonstrated geographycally.
### Life Expectancy by State (Ranking) - Line Chart
- understand which are the US States that are top or bottom ranked in terms of Life Expectancy througout the timelines.
### Activity vs. Obesity Trend - Bar Chart
- relationship of physical activity levels against obesity per State.
### Activity vs. Obesity - Scatter Plot
- analysis on the correlation between obesity and level of physical activity when compared to National Level percentage and Target percentages.
