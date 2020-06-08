# Titanic Kaggle

[Kaggle](https://www.kaggle.com/c/titanic/overview)

## Variables

| Variable |                 Definition                 |                      Key                       |
| -------- | :----------------------------------------: | :--------------------------------------------: |
| survival |                  Survival                  |                0 = No, 1 = Yes                 |
| pclass   |                Ticket class                |           1 = 1st, 2 = 2nd, 3 = 3rd            |
| sex      |                    Sex                     |                                                |
| Age      |                Age in years                |                                                |
| sibsp    |                    Sex                     |                                                |
| sex      | # of siblings / spouses aboard the Titanic |                                                |
| parch    | # of parents / children aboard the Titanic |                                                |
| ticket   |               Ticket number                |                                                |
| fare     |               Passenger fare               |                                                |
| cabin    |                Cabin number                |                                                |
| embarked |            Port of Embarkation             | C = Cherbourg, Q = Queenstown, S = Southampton |

## Variable Notes

`pclass`: A proxy for socio-economic status (SES)

- 1st = Upper
- 2nd = Middle
- 3rd = Lower

`age`: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

`sibsp`: The dataset defines family relations in this way...

- Sibling = brother, sister, stepbrother, stepsister
- Spouse = husband, wife (mistresses and fiancés were ignored)

`parch`: The dataset defines family relations in this way...

- Parent = mother, father
- Child = daughter, son, stepdaughter, stepson
- Some children travelled only with a nanny, therefore parch=0 for them.

## Ref

[EDA](https://www.kaggle.com/ash316/eda-to-prediction-dietanic/notebook)

[EDA](https://www.kaggle.com/ldfreeman3/a-data-science-framework-to-achieve-99-accuracy/notebook)

[ML workflow](https://www.kaggle.com/masumrumi/a-statistical-analysis-ml-workflow-of-titanic/notebook)

[Impute Missing Value](https://jamesrledoux.com/code/imputation)

[t test](https://towardsdatascience.com/inferential-statistics-series-t-test-using-numpy-2718f8f9bf2f)
