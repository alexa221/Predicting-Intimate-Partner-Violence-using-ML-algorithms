# Predicting the Types of Intimate Partner Violence against Married Women in Ethiopia using  Ensemble Machine Learning Algorithms 
This repository contains data's of Intimate Partner Violence  (IPV) and implementing with Python programming languages primarily used to predict  IPV against women. 
The study is based on data gathered from the Ethiopian demographic, health survey (EDHS) collected two times with five-year intervals of 2011 and 2016 E.C. 

The study was conducted following an experimental research approach. 
The ensemble ML algorithms such as extreme gradient boosting, CatBoost, Random Forest, and support Vector Machine with class decomposition One versus Rest (OVR) were employed to develop a prediction model. 

For constructing the proposed model, experiments were conducted with a total of 35185 instances with 22 features, and a training and testing dataset split ratio of 80/20.

### The research questions that tried to addressed are:

•	Which type of  ensemble machine learning algorithms is suitable to construct an IPV predictive model?

•	What are the demographic and socioeconomic risk factors that influence IPV against women? 

•	What are the most important rules that can be generated from the predictive model to formulate policy towards reducing and ending IPV in Ethiopia? 






## Author

- [@Alexander Takele Mengesha](https://www.github.com/alexa221)
  
- [@Tesfamariam Mulugeta Abuhay](https://www.github.com/TesfamariamAbuhay)
  

# Hi, We are authors of this project! 👋


## Authors Github

- [Github](https://www.github.com/alexa221)

- [Github](https://www.github.com/TesfamariamAbuhay)


## Tech Stack
    Advanced Python for data science

    Statistical tools 


# Acknowledgements
First and foremost, I express my gratitude to the almighty God and the Virgin Mary, mother of Jesus Christ, for providing me with the opportunity, knowledge, and inspiration to complete my thesis and achieve it at this stage of my life. I am deeply indebted and very glad to express my heartfelt thanks and appreciation to my Advisor Dr. Tesfamariam Mulugeta for his important and constructive comments, criticisms, and professional advice and for doing all these on time from the beginning of the proposal writing to the completion of this thesis.  

## Installation

Install Anaconda 2020 for Python3 and open jupiter Notebook

```bash
•    Install mlxtend for feature selection: ---pip install mlxtend 
•    Install xgboost for model building: ---pip install xgboost
•    Install catboost for model building: ---pip install catboost 
•    Install imblearn for class balancing: ---pip install imblearn

```
    
## Optimizations/ parameter tuning

As datascientist, we have tuned hyperparameters of the ML model. Hyperparameter tuning aims to find parameters where the performance of the model is highest or where the model performance is best and the error rate is least. We define the hyperparameter as shown below for the XGBoost,Catboost and random forest classifier model.

### Steps that we follow  Hyper Parameter Tuning are
##### 1.  Select the type of model we want to use like XGBoost, CatBoost, RandomForestClassifier, LightGBM or any other model.
##### 2.  Check what are the parameters of the model

##### 3.  Select the methods for searching the hyperparameter

##### 4.  Select the cross-validation approach

##### 5.  Evaluate the model using the evaluation metric

## Train-Test Split 
we split the dataset

A. 80% for training set used to  train the model.
  
B. 20% for testing set used to evaluate the model performance. it only used once a model is completely trained using traind and validationset.

## Model Evaluation

In this ***Machine Learning process***, evaluate and compare ***model performance, Visualize and communicate results***.Model evaluation is the most important part of the machine learning process from a ***Data scientist*** perspective


## Deployment

 1. desingned protype using selected features 
 2. save the model using.pkl extension
 3. join both files using flask python frame work
 4. upload intergrted files using linux terminal to   heroku cloud free space

```bash
  open linux terminal
  .pkl 
  npm run heroku 

```

