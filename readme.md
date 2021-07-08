
# README
This is the capstone project for the udacity machine learning engineer nanodegree course. 


### Introduction
This project was developed as capstone project for the Udacity’s Machine Learning Engineer Nanodegree. It is based on real life data provided by Arvato/Bertelsmann. I analyzed demographics data and compared it to general population demographics in Germany. 
By using supervised and unsupervised machine learning techniques I trained a model to predict, which customers might have a higher probability to respond to a mailing campaign to become customers of the company. 

### Libraries
The following libraries are used within the project and hence have to be installed upfront: 
- Pandas
- Numpy
- Sklearn
- Matplotlib
- Seaborn
- Pickle
- Pylab
- DecisionTreeClassifier
- RandomForestClassifier
- GridSearchCV
- XGBoost
- LightGBM
- roc_auc_score

Most of them are included within the anaconda edition. Single libraries can be installed with pip via ```pip install [packagename]``` in the terminal.

### Data
The data files used in this project are 
* *Udacity_AZDIAS_052018.csv*: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
* *Udacity_CUSTOMERS_052018.csv*: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
* *Udacity_MAILOUT_052018_TRAIN.csv*: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
* *Udacity_MAILOUT_052018_TEST.csv*: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

In addition, there are two metadata files for these datasets:
* *DIAS information levels - attributes2017.xlsx*
* *DIAS Attributes - Values 2017.xlsx*

It is provided by Arvato Bertelsmann and can be accessed by taking part in the Kaggle competition: https://www.kaggle.com/c/udacity-arvato-identify-customers .

### Methodology and Results: 
The project consisted on two steps: 
Indentification of useful clusters for the demographic data and determine those, who would respond positive with a high probability. Please read the *report.pdf* file for details. 