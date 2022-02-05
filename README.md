## insurance-premium-prediction
The goal of this project is to give people an estimate of how much they need based on their individual health situation. After that, customers can work with any health insurance carrier and its plans and perks while keeping the projected cost from our study in mind. This can assist a person in concentrating on the health side of an insurance policy rather han the ineffective part.

--------------------------------------------

## Table of Content

  * [Dataset Information](#dataset-information)
  * [Overview](#overview)
  * [Technologies Used](#technologies-used)


In this project we are predicting an expense to people based on their individual health situation. This is regression supervised machine learning project. I have used linear regression to predict expenses and using mse metric to observe how our model is working. After this applied neural network, getting more robust model.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<img target="_blank" src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fmedium.com%2F%40meruguakshay%2Finsurance-cost-prediction-using-linear-regression-155edd73cf94&psig=AOvVaw1rLyA7cLYHEvTKvywLBAtB&ust=1644130162585000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCODn6qP95_UCFQAAAAAdAAAAABAD.svg" width=800; height=300>

## Dataset information:

### insurance-premium-prediction:

* Age : Age of person

* Sex : Gender of person 

* BMI : BMI of person

* Children : number of children person have

* Smoker : Smoking person or not (yes/no)

* Region: Southeast, Southwest, Northeast, Northwest

* Expenses : Expense of person

--------------------------------------------------------------------------------------------

## Overview:

we have to give people an estimate of how much they need based on their individual health situation. After that, customers can work with any health insurance carrier and its plans and perks while keeping the projected cost from our study in mind. This can assist a person in concentrating on the health side of an insurance policy rather han the ineffective part.
This is regression supervised machine learning project. I have used linear regression to predict expenses and using mse metric to observe how our model is working. After this applied neural network, getting more robust model.

Dataset contains information on Age, Sex, BMI, Children, Smoker, Region and Expenses.starting with cleaning data. we have outlier in expense column removing outlier using log10. after this we dont have any other outlier in our data. then i plot correlation plot to check independent and dependent variable correlation. having more correlated variable we wil drop that. but in our data we dont have high correlated variable.checking duplicatesand if any we will drop those data using drop_duplicated. 

In visualization we visualize all feature variable, in region more people living in southeast region 27.22% followed by southwest 24.29%, northeast and northwest 24.29%, 24.21% respectively. In countplot for smoker in region i found that there are large number of non-smoker in different region and all region have atleast 50 people smokers. checking number of smokers in different age, In all age people are smoking and maximum people are from age 19.checking smoker sex wise, gender wise male ratio is higher than female smoking and in non-smoking female have high ratio than male. checking region-wise gender distribution, there are almost equal number of male and female ratio in all region. checking region wise expenses for smokers, smoker have high expenses compare to non-smoker.checking expenses gender wise if it's smoker or not,  we found that rather male or female if he/she is smoking they are having higher expenses compare to the non-smokers. ploting batplot to finalise that smoker have higher expenses than non-smoker. countplot for smoker and non-smoker, there are very less people are smoking compare to non-smoker.(rather we have very less people with smoking but there is large effect on expenses because smokers are having large expenses.this we will check using scatterplot.) 

In feature Engineering we will create new feature i.e categorize_bmi. in this bmi will be categorize in underweight,normal, overweight and obese. we will create dummy variable for sex, children, smoker, region and categorize_bmi. applying linear regression model accuracy 77. 


Technology and tools wise this project covers,

1.Python

2.Numpy and Pandas for data cleaning

3.Data visualization

4.Sklearn for model building

5.Colab Notebook

--------------------------------

## Technologies Used:

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://user-images.githubusercontent.com/32620288/139657460-40ef4562-76bd-43f5-bbca-47b6bd29863e.png" width=100>](https://numpy.org)    [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/450px-Pandas_logo.svg.png" width=150>](https://pandas.pydata.org)  [<img target="_blank" src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width=150>](https://seaborn.pydata.org) [<img target="_blank" src="https://matplotlib.org/_static/logo2_compressed.svg" width=170>](https://matplotlib.org)   
