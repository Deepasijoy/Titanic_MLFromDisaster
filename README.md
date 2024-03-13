# Titanic_MLFromDisaster
This is the legendary Titanic ML competition. I have created a machine learning model that predicts which passengers survived the Titanic shipwreck.

Data Set Description:-
The data has been split into two groups:

training set (train.csv)
test set (test.csv)
The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

Data Variables:
pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower
age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5
sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)
parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

Procedure:Data Exploration:-
Having uploaded the data and exploring the data.Checked for the Statistical summary for both categorical and numerical variables.Visualised the data by checking relationship of various features effect on survived variable. 
Data Cleaning and Visualisation:-
Checked for correlations. Dealt with missing values,unnecessary columns dropped and missing values imputed with the mean and mode for 'age' and 'embarked' respectively.Visualised the data using seaborn and matplotlib libraries.
Data PreProcessing
Manually encoded the categorical variables,split the train data to X_train,y_train and used Standard scaler to scale the data to avoid biases.
Uploaded the test and gender_Submission data concatanated .Split it to X_test and y_test.
Data Modelling:-Chose Ensemble methods like Random Forest Regressor and Hist Gradient Boosting Regressor and chose mean squared error metrics to check accuracy of the models.Ensemble methods are methods that combine multiple individual models to improve the models performance.
Model Definition ,Evaluation and HyperParameter tuning:-
First defined a model and metrics after which used paremter grids to carry cross validation and evaluated the performance.Hyper Parameter Tuning is used to select optimal values.Cross validation helps in estimating the models performance on unseen data. All results were then  visualised which gives insight into the each of the models performance.
Based on all findings Hist Gradient Boosting Regressore was used for predictions.

