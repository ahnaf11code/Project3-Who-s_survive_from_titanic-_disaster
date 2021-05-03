# Project3-Who-s_survive_from_titanic-_disaster_
This is a simple project, and I think every data science learner have done this project. 
The dataset contains several informations about titanic passanger that can be used to predict whether they're survive or not from this terrible disaster. The data has 12 features.

![image](https://user-images.githubusercontent.com/82840840/116876402-9ad0de80-ac46-11eb-9ee2-fc79a130a50d.png)

Questions in this project are:
1. Who's survive ?
2. How's the model performance ?

The dataset has several rows with missing values

![image](https://user-images.githubusercontent.com/82840840/116876550-de2b4d00-ac46-11eb-8c03-239dea400724.png)

First, we drop cabin variable because there's too much missing values on it and hard to impute.
Then, we drop all the rows with missing values.

After dealing with missing values, now we see there are 3 categorical variables. So we have to encode those variables into 0 and 1 in order to be calculated.

![image](https://user-images.githubusercontent.com/82840840/116877635-678f4f00-ac48-11eb-8eee-f8ce6d9d3966.png)

So the dataset is cleaned. Then we make classification model, method that used is Logistic Regression, and we got 84% accuracy.

![image](https://user-images.githubusercontent.com/82840840/116877797-9efdfb80-ac48-11eb-9218-7b780a95b137.png)
