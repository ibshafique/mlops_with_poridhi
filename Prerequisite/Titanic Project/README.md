[Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)

# The data has been split into two groups:

* training set (train.csv)
* test set (test.csv)

The training dataset, train.csv is used to train the machine learning model.
The test dataset, test.csv is used to test the performance of the machine learning model.


# Data Dictionary

| Variable   | Definition                          | Key                              |
|------------|-------------------------------------|----------------------------------|
| survival   | Survival                            | 0 = No, 1 = Yes                  |
| pclass     | Ticket class                        | 1 = 1st, 2 = 2nd, 3 = 3rd        |
| sex        | Sex                                 |                                  |
| age        | Age in years                        |                                  |
| sibsp      | # of siblings / spouses aboard      |                                  |
| parch      | # of parents / children aboard      |                                  |
| ticket     | Ticket number                       |                                  |
| fare       | Passenger fare                      |                                  |
| cabin      | Cabin number                        |                                  |
| embarked   | Port of Embarkation                 | C = Cherbourg, Q = Queenstown, S = Southampton |

---

## Variable Notes

### `pclass`: A proxy for socio-economic status (SES)
- **1st** = Upper  
- **2nd** = Middle  
- **3rd** = Lower  

### `age`
- Age is fractional if less than 1.  
- If the age is estimated, it is in the form of `xx.5`.

### `sibsp`: Family relations
- **Sibling** = brother, sister, stepbrother, stepsister  
- **Spouse** = husband, wife (mistresses and fiancés were ignored)  

### `parch`: Family relations
- **Parent** = mother, father  
- **Child** = daughter, son, stepdaughter, stepson  

> Some children travelled only with a nanny, therefore `parch = 0` for them.