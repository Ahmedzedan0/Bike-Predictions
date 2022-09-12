# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Ahmed Zidane

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: you must drop all negative values and set them to zero before submission 

### What was the top ranked model that performed?
TODO: Initial model with score 1.80832

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: EDA found the negative values, then we changed it. and get some descriptive information
and we changed the datetime format 

### How much better did your model preform after adding additional features and why do you think that is?
TODO: not much, i don't know why. I think we just try and pick the better one

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: not much it decreases from 1.80832 to 0.68068 

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: no i will not since the acuuracy improvement is constant

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
    |model|           |hpo1|                   |hpo2|           |hpo3|                   |score|
    ------------|-------------------|-----------------------|--------------------------------
0	initial	    | time_limit = 600	|presets='best_quality'	| default vals               | 1.80832
1	add_features| time_limit=600    |presets='best_quality'	| problem_type = 'regression'| 0.68874
2	hpo	        |time_limit=600     |presets='best_quality' | tabular autogluon	         | 0.68068

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)

## Summary
TODO: Add your explanation
