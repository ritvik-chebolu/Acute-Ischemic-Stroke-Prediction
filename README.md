
# Acute Ischemic Stroke Prediction

A machine learning approach for early prediction of acute ischemic strokes in patients based on their medical history.  

The goal of using an Ensemble Machine Learning model is to improve the performance of the model by combining the predictive powers of multiple models, which can reduce overfitting and improve the generalizability of the model.
Out of the two approaches for an ensemble model, simple/weighted average and the majority vote, the former seemed to be the best way to proceed since it has a weighted contribution to the final prediction. The majority vote on the other hand, only considers the most common prediction among individual models.

With a relatively smaller dataset (although quite big in terms of a healthcare facility), every possible effort to minimize or eliminate overfitting was made, ranging from methods like k-fold cross validation to hyperparameter optimization (using grid search CV) to find the best value for each parameters in a model.


## Documentation

This repo has all the project files for building an ML model to predict the severity of acute ischemic strokes (brain strokes) observed in patients. For quick navigation, use the following links: 

1. [Google colab notebook](https://github.com/ritvik-chebolu/Acute-Ischemic-Stroke-Prediction/blob/main/Acute_Ischemic_Stroke_Prediction.ipynb)

2. [Project report](https://docs.google.com/document/d/1ZVsonRynmAsxGZw2BLKrY8D7oIZ6xdR-tUDu9xBbLmY/edit?usp=sharing)
 
3. [Dataset](https://docs.google.com/spreadsheets/d/1cNZF7WZMC8EilYWb8W6Ak1R6nNdk-jPgEjusff2Lj7k/edit?usp=sharing)

4. [Presentation slides](https://docs.google.com/presentation/d/1BHvYFqW6S5d0M0U3DJCgl3KzzHvGrnXEObBFhcSa5OM/edit?usp=sharing)


## Appendix

© 2021 Dr. Harshika Chebolu  
All copyrights of the dataset belong to Dr. Harshika Chebolu, Post Graduate in General Medicine at Gandhi Medical Hospital, Hyderabad, India.  
 

