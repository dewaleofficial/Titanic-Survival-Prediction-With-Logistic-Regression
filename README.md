## Titanic-Survival-Prediction-With-Logistic-Regression
 A machine learning project predicting survival outcome of all passengers n the titanic accident.
 Check out the [medium post](https://dewaleofficial.medium.com/titanic-survival-prediction-34ddf9dfc731) for brief explanation of the result gotten from the analysis

### TABLE OF CONTENT
1.  [Libraries used](#libraries-used)
2.  [Motivation for the project](#motivation-for-the-project)
3.  [File Description](#file-description)
4.  [Results of the analysis](#results-of-the-analysis)
5.  [Acknowledgement](#acknowledgement)



### Libraries used

- Numpy
- Pandas
- scikitlearn for machine learning
- Seaborn and Matplotlib for visualization


```sh
import pandas as pd
import numpy as np
import seaborn as sns
from matplotlib import pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import classification_report
```

### Motivation for the project

The objective is to determine the survival chance of every passenger on board. First, we explore information  by applying exploratory  data analytics  on available  dataset and then apply a machine learning model to complete the analysis of what sorts of people were likely to survive. After this  the  results  of  applying  machine  learning  models  are compared and analyzed on the basis of accuracy.


### File Description

1. **README.md** - contains the description of the project and resullt from analysis
2. **titanic_train.csv** - The dataset used in the project is stored in this file
3. **titanic_survival_prediction.ipynb** - Contains all codes used in the analysis and machine learning model for prediction


### Results of the analysis

- From the analysis, we can see that most men did not survive the attack. About 77% of men did not survive while over 66& of women survived the accident, Therefore gender played a huge role in deciding the survival tendency of every passenger 
- The ticket class also affected the outcome of survival. From the analysis, we can also see that about 70% of 3rd class passengers did not survive the accident while over 60% of first class passengers survived the accident
- The number of siblings on board also had a role to play in determining the survival tendency of each passenger as more passengers with no sibling survived than passengers with siblings. It makes sense because passengers with siblings wouldnt want to leave their sibliings behind.


### Acknowledgement


