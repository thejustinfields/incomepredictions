# Income Predictions

## How personal information helps predict income

Author: Justin Fields

## Business Problem
How does information about a person predict the level of income they will have?

## Data
The original data source is: https://www.kaggle.com/datasets/wenruliu/adult-income-dataset

The data includes information pertaining to age, education level, working class, occupation, capital gain and loss, race, gender, marital status, and native country.

## Results

![Unknown-3](https://github.com/thejustinfields/incomepredictions/assets/128246388/53bd301e-ded5-4c7a-b8b6-c3ce4d948b93)
- The highest earners globally are over 40.
- The highest earners live in North America and Europe

![Unknown-4](https://github.com/thejustinfields/incomepredictions/assets/128246388/a679b20d-26ed-4569-aa08-161c8e09e295)
- Those with a high school education and undergraduate degrees are well represented in both groups--those make more than and less than or equal to 50k.

## Model
The final model is KNN with parameters tuned to: 'kneighborsclassifier__n_neighbors': 8, 'kneighborsclassifier__p': 1, 'kneighborsclassifier__weights': 'uniform'.
The model predicts with a precision of 81% and for <=50k and 70% for >50k. The percentage of correct predictions was 87% for <=50k and 48% for >50k.
The model will accurately predict income at just under 80% accuracy.



