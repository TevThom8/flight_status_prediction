# Flight Status Prediction Analysis



This analysis focuses on predicting flight delays using historical flight data. The objective is to leverage data science and machine learning techniques to develop predictive models that can assist stakeholders in the aviation industry with managing flight schedules more effectively and enhancing customer satisfaction.

# Project Goals

Understand the Problem: Perform exploratory data analysis (EDA) to identify key factors influencing flight delays.
Data Preprocessing: Clean and prepare the data for machine learning.
Feature Engineering: Develop new features to improve model performance.
Model Training and Evaluation: Train and assess various machine learning models to predict flight delays.
Focused Analysis on ATL: Conduct a detailed analysis using data from Hartsfield-Jackson Atlanta International Airport (ATL) to manage computational constraints.
Dataset Overview

The dataset comprises information on thousands of flights, including:

Departure and arrival delays
Airlines
Airports
Additional flight details
This extensive dataset provides a solid foundation for developing accurate predictive models.


## Exploratory Data Analysis (EDA)


### Data Inspection: <br>
Examining the shape and structure of the dataset.
### Missing Values: <br>
Identifying and addressing missing values.<br>
### Data Visualization: <br>
Utilizing visualizations to understand feature distributions and relationships. 
### Key insights included:<br>
A strong positive correlation between arrival and departure delays.
Significant correlations between scheduled and actual departure and arrival times. <br>
 ## Data Preprocessing:

### Filtering Data: <br> 
Focusing on flights departing from ATL to manage computational load. <br>
### Feature Selection:<br> 
Choosing relevant feature for prediction.<br>
### Handling Missing Values: <br>
Imputing or removing missing data as necessary.<br>
### Normalization: <br>
Scaling numerical features to enhance model performance.

## Feature Engineering

 To improve the predictive power of the models, several new features were engineered:

### Time-based Features: <br>
Extracting features such as departure hour, day of the week, and month.<br>
### Interaction Features: <br>
Creating features representing interactions between different variables (e.g., airline and departure time).<br>
## Model Training and Evaluation

### Multiple machine learning models were trained and evaluated, including:

1)Logistic Regression<br>
2)Decision Trees<br>
3)Random Forests<br>
4)Gradient Boosting<br>
Each model's performance was 
assessed using metrics such as accuracy, precision, recall, and F1-score. <br>Cross-validation was performed to ensure robust results. The Random Forest model emerged as the best-performing model, offering a good balance between precision and recall.<br>

## Results and Conclusions


The analysis demonstrated the feasibility of predicting flight delays with a reasonable degree of accuracy. 


### Best Model: <br>
The Random Forest model achieved the highest performance metrics.<br>
### Important Features: <br>
Departure time, airline, and historical delays were identified as significant predictors of flight delays.<br>
### Focused Analysis on ATL: <br>
Limiting the analysis to ATL facilitated efficient computational resource usage while capturing diverse flight scenarios.<br>
## Future Work



### Expand the Dataset: <br>
Incorporate data from additional airports to create a more generalized model.<br>
### Advanced Techniques: <br>
Explore advanced machine learning methods, such as neural networks.<br>
### Real-time Predictions: <br>
Implement the model in a real-time prediction system to provide actionable insights to stakeholders.
