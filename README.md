# housingdata,diabetes-

# housingdata-
In this project, we will develop and evaluate the performance and the predictive power of a model trained and tested on data collected from houses
A model like this would be very valuable for a real state agent who could make use of the information provided in a dayly basis.
The dataset used in this project comes from the UCI Machine Learning Repository. This data was collected in 1978 and 
each of the 506 entries represents aggregate information about 14 features of homes from various suburb
The features can be summarized as follows:
CRIM: This is the per capita crime rate by town
ZN: This is the proportion of residential land zoned for lots larger than 25,000 sq.ft.
INDUS: This is the proportion of non-retail business acres per town.
CHAS: This is the Charles River dummy variable (this is equal to 1 if tract bounds river; 0 otherwise)
NOX: This is the nitric oxides concentration (parts per 10 million)
RM: This is the average number of rooms per dwelling
AGE: This is the proportion of owner-occupied units built prior to 1940
DIS: This is the weighted distances to five Boston employment centers
RAD: This is the index of accessibility to radial highways
TAX: This is the full-value property-tax rate per $10,000
PTRATIO: This is the pupil-teacher ratio by town
B: This is calculated as 1000(Bk — 0.63)², where Bk is the proportion of people of African American descent by town
LSTAT: This is the percentage lower status of the population
MEDV: This is the median value of owner-occupied homes in $1000s
The essential features for the project are: ‘RM’, ‘LSTAT’, ‘PTRATIO’ and ‘MEDV’. The remaining features have been excluded.
As our goal is to develop a model that has the capacity of predicting the value of houses,
we will split the dataset into features and the target variable. And store them in features and prices variables, respectively.
Houses with more rooms (higher ‘RM’ value) will worth more. Usually houses with more rooms are bigger and can fit more people, 
so it is reasonable that they cost more money. They are directly proportional variables.
Neighborhoods with more lower class workers (higher ‘LSTAT’ value) will worth less.
If the percentage of lower working class people is higher, 
it is likely that they have low purchasing power and therefore, they houses will cost less. They are inversely proportional variables.
Neighborhoods with more students to teachers ratio (higher ‘PTRATIO’ value) will be worth less.
If the percentage of students to teachers ratio people is higher, it is likely that in the neighborhood there are less schools,
this could be because there is less tax income which could be because in that neighborhood people earn less money.
If people earn less money it is likely that their houses are worth less. They are inversely proportional variables.

# diabetes-

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage. The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age. We’ll be using Python and some of its popular data science related packages. First of all, we will import pandas to read our data from a CSV file and manipulate it for further use. We will also use numpy to convert out data into a format suitable to feed our classification model. We’ll use seaborn and matplotlib for visualizations. We will then import classifier algorithm from keras. This algorithm will help us build our classification model.we will get the predection of outcome,and get the confusion matri
