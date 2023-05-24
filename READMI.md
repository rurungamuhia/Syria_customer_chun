# PHASE 3 PROJECT
# SYRIA TELECOMMUNICATION ANALYSIS
# Project Description
## Introduction
SyriaTel is a telecommunications company in Syria. They have been informed that some of their customers have started to churn, discontinue their service. 

This analysis will determine what features will indicate if a customer will ("soon") discontinue their service..

# The challenge
The nature of this issue is framed by the reality that it is less expensive to lose current consumers than it is to acquire new ones. As a result, keeping your existing clientele is far preferable to acquiring new ones. Since fixing this issue would enable SyriaTel to save money, I was aware that the proposed business adjustments would also need to be taken into account from an economic standpoint; otherwise, what would be the point?
This was a binary classification project.

where I asked my classifier to respond to three questions.

1. What and how much of the dataset's characteristics are the main predictors of customer churn?
2. In what ways might these results be interpreted, and how can SyriaTel put cost-effective fixes into practice?

On a quest to build a classifier to service SyriaTel’s needs in the best way possible, I took into consideration which metric would make the most sense. I determined that incorrectly classifying a false negative would be worse than a false positive because a false negative would mean that the reality of a customer canceling would have been overlooked. The occurrence of the false-negative occurring is referred to as a type two error. In order to rank my classifiers on how well they minimized false negatives, I used the measurement of recall.
    
    
    ## Data Understanding
There were continous fetures and categorical features used in the data set which were as follows
  
## Continuous Features:
* account length
* number vmail messages
* total day minutes
* total day calls
* total day charge
* total eve minutes
* total eve calls
* total eve charge
* total night minutes 
* total night calls
* total night charge
* total intl minutes
* total intl charge
* customer service calls

## Categorical Features:
* state
* area code
* international plan
* voicemail plan
    An image of the dateset
   ![alt text](https://github.com/Cynthiah-Mulwo/dsc-phase-2-project-v2-3/blob/master/Screenshot%20from%202023-04-20%2019-35-47.png)
   


# Explolatory Data Analysis
We will explore the following areas to set context for the presentation
- Area code 
- Customer service calls
- State
- International Plans
- Voice mail Plans

Some of the visualisations are created:
Area code in relation to Churn

 ![alt text](image.png)

International Count plan
![alt text](image.png)


# Modeling 
This section demonstrates modelling done to the data
Some of the models used were 
* Logistic Regression
* K-Nearest Neighbors
* Decision Tree
* Decision Tree
* Gradient Boost
* Random Forest
* GridSearchCV


# Success Metrics 
We will use ROC and F1 score for different model comparisons to check how effective each model is.
Also we willl be using an accuracy score to check the accuracy of the different models
A Hyperparameters was also  determine the behavior and performance of the model. These parameters are not learned from the data but are set by the user or selected through hyperparameter tuning techniques
Some of the visualizations used were
![alt text](image.png)

 

# Conclusions:
The dataset made it clear that SyriaTel's pricing policy was to bill clients according to the number of minutes they consumed. But it is clear that among the causes of significant customer churn, every one of them raises the client's bill, discouraging them from keeping their phone plan.

