Problem Statement:
To build a methodology to Prediction for Wine Quality.


Data Description:
Input variables (based on physicochemical tests):

1 - fixed acidity

2 - volatile acidity

3 - citric acid

4 - residual sugar

5 - chlorides

6 - free sulfur dioxide

7 - total sulfur dioxide

8 - density

9 - pH

10 - sulphates

11 - alcohol

Output variable (based on sensory data):

12 - quality (score between 0 and 10)
------------------------------------------------------------------------------------------------------------------------------------- 

Data Analysis:
Find EDA
Scaling data.

Model Training 
1.	KNN
2.	Decision tree
(Find best parameter using GridSearchC)
3.	XGBClassifier

Use Class Imbalancement Technique:

Model Training 
1.	DecisionTreeClassifier
2.	RandomForestClassifier
3.	XGBClassifier


Result:
Predict value  ≤  3  →→    Result = 'Bad'
Predict value = 4    →→   Result = 'Below Average'
Predict value  =  5  →→   Result = 'Average'
Predict value =  6   →→   Result = 'Good'
Predict value  =  7  →→   Result = ‘'Very Good'
Predict value ≥  8  →→   Result = 'Excellent'

Deployment
We will be deploying the model to the Heroku Cloud platform. 
Deployment Link: https://wine-quality-prediction-vj.herokuapp.com/

