# Titanic Survival Prediction

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, the ask is to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

So we need to create a model that predicts which passengers survived the Titanic shipwreck.

## Data

The data for the following problem is [available on Kaggle.](https://www.kaggle.com/c/titanic) 
Since the data has been added to the `data/` directory, cloning this repository would suffice.

## Pre-requisites

The project was developed using python 3.8.3 with the following packages.
- Pandas
- Numpy
- matplotlib
- seaborn
- Scikit-learn
- statsmodels


## Files
- /notebooks/Titanic_Survival_Prediction_LogisticRegression.ipynb : Jupyter Notebook with all the workings including pre-processing, modelling (using Logistic Regression) and inference.
- /data/train.csv : The source data.
- /data/test.csv : Without the final outcome or target variable which needs to be predicted.


## Acknowledgements

[Kaggle](https://kaggle.com/), for providing the data for this problem statement.