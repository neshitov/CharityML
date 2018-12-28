# Census data analysis
## Installations.
Project consists of Python3 notebook that uses the following libraires:
- standard libraries numpy, pandas, scikit-learn, matplotlib,
- [CatBoost](https://catboost.ai/), a library for decision tree gradient boosting.

## Project motivation.
This notebook is a part of Udacity CharityML project. It analyses census data from census.csv that describe education, age and other demographical data. Aim of the project is to construct a model that predicts the  income of a person based on the census data. This is a binary classifiction problem as there are two possible values in the income column ('>50k' and '<=50k')

## Files description.
There is one notebook with analysis, and a data file census.csv

## Results
Several models were tested, and the one provided by categorical boosting turned out to be the most accurate one with
0.716 F1 score on the test set. Feature analysis shows that the features 'capital-gain' that shows a gain of the capital in the account, 'relationship' that shows family status, and 'age' are the most important ones. 


## Licensing and Acknowledgements
Please feel free to use the code from this notebook.
