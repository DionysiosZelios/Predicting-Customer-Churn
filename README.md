# Predicting Customer Churn 
Churn prediction consists of detecting which customers are likely to cancel a subscription to a service based on how they use the service. We want to predict the answer to the following question: “Is this customer going to leave us within the next X months?” There are only two possible answers, yes or no; a binary classification task. 


### Why it matters?
Businesses often have to invest substantial amounts attracting new clients, so every time a client leaves it represents a significant investment lost. Both time and effort then need to be channelled into replacing them. Being able to predict when a client is likely to leave and offer them incentives to stay can offer huge savings to a business. 


### What is the main challenge?
In a real world application, our data would never be too tidy or easy to work with and we would have to undertake a much more rigorous process for evaluating our predictions. We should enrich our data with additional sources (social media feeds, weather and location data, 3rd party data) and perform any transformations we needed such as aggregations, normalization, imputation, etc. 

Once we have our initial results / predictions, the next stage would be to iterate over the steps (cleaning the data, feature selection, modelling, etc.) in an effort to boost the accuracy (or whatever scoring metric you use) of our model. The addition or removal of features, the tuning of hyper parameters, or simply the use of a more complete or larger dataset may all boost our model.
