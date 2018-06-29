# MACHINE LEARNING ENGINEER NANODEGREE
## PREDICTION OF CONSUMER CREDIT RISK
### Useful Links
* [Research paper](http://cs229.stanford.edu/proj2014/Marie-Laure%20Charpignon,%20Enguerrand%20Horel,%20Flora%20Tixier,%20Prediction%20of%20consumer%20credit%20risk.pdf)
* [Article](https://www.sciencedirect.com/science/article/pii/S095741741101342X?via%3Dihub)
* [Kaggle competition](https://www.kaggle.com/c/GiveMeSomeCredit)
* [Dataset](https://www.kaggle.com/c/GiveMeSomeCredit/data)

### Data Information
* Number of instances or rows :- 1,50,000
* Number of features or independent variables :- 10
* Number of target or dependent variables :- 1

### Target label and description
1. **SeriousDlqin2yrs** - Person experienced 90 days past due delinquency or worse.

### Features label and description
1. **RevolvingUtilizationOfUnsecuredLines** - Total balance on credit cards and personal lines of credit except real estate and no installment debt like car loans divided by the sum of credit limits.
2. **Age** - Age of borrower in years.
3. **NumberOfTime30-59DaysPastDueNotWorse** - Number of times borrower has been 30-59 days past due but no worse in the last 2 years.
4. **DebtRatio** - Monthly debt payments, alimony,living costs divided by monthy gross income.
5. **MonthlyIncome** - Monthly Income
6. **NumberOfOpenCreditLinesAndLoans** - Number of Open loans (installment like car loan or mortgage) and Lines of credit (e.g. credit cards).
7. **NumberOfTimes90DaysLate** - Number of times borrower has been 90 days or more past due.
8. **NumberRealEstateLoansOrLines** - Number of mortgage and real estate loans including home equity lines of credit.
9. **NumberOfTime60-89DaysPastDueNotWorse** - Number of times borrower has been 60-89 days past due but no worse in the last 2 years.
10. **NumberOfDependents** - Number of dependents in family excluding themselves. (spouse, children etc.)

### Software Requirements
1. Python version = 2.7.x
2. pip = 10.0.1
3. jupyter = 1.0.0
4. ipython = 5.5.0
4. numpy = 1.14.0
5. pandas = 0.20.3
6. scikit-learn = 0.19.0
7. xgboost = 0.7

### Running the ipython notebook
To run the notebook **predict.ipynb**, navigate to top level directory and type the following command on your terminal or command prompt :-
`jupyter notebook predict.ipynb`
