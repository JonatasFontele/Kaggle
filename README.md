# Kaggle
Kaggle training
* [Titanic - Machine Learning from Disaster.ipynb](https://github.com/JonatasFontele/Kaggle/tree/main/Titanic)
  * Training set (train.csv)

| Feature | Definition | Key |
| ------------------- | ------------------- | ------------------- |
| PassengerId |  |  |
| Survived | "ground truth" | 0 = No, 1 = Yes |
| Pclass | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd |
| Name | Ticket class | |
| Sex | Sex | |
| Age | Age in years | |
| SibSp | # of siblings / spouses aboard the Titanic| |
| Parch | # of parents / children aboard the Titanic | |
| Ticket | Ticket number | |
| Fare | Passenger fare | |
| Cabin | Cabin number | |
| Embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton|

  * Test set (test.csv)
    * All features from Training set but 'Survived'
  * Sample submission file wich assumes that all female passengers survived (gender_submission.csv)
    * PassengerId
    * Survived
