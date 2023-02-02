# Survival-Rate-on-Titanic using Supervised Learning
### Descsion Tree
This is a python machine Learning Project which predicts the Survival Rate of the Passenger on Titanic using the data from 'titanic.csv'.

## Libararies Used in this Project
1) Pandas : To import the csv file.
2) Numpy : To covert the model data into python array
3) sKlearn : To perform the DecisionTreeClassifier() function from class 'tree'
4) Seaborn : For Plotting the confusion Matrix

#### Steps involved in this project
* We used the Supervised Learning method to train our model.
* On the begining we removed the data which was independent of passenger's Survival rate.
* Then we changed the categorical variables by converting the labels into a numeric form so as to convert them into the machine-readable form (Sex , Embarked)
* After splitting the target variable from the model.
* As Age column has some NULL values so replacing them with mean of the column. ( 29.699117647058763 )
* Now time to use train_test_split to split the the data for testing and training
* Using DecisionTreeClassifier() function to train our Model.
* Our model is now ready to predict the survival rate.

## Classes Used inside this Project
1) LabelEncoder() from sklearn
2) train_test_split() from sklearn.model_selection
3) confusion_matrix from sklearn.metrics
