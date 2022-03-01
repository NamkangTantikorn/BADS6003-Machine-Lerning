# BADS6003-Machine-Lerning
[![](https://img.shields.io/badge/-Logistic--Regression-orange)](#)
[![](https://img.shields.io/badge/-Decision--Tree-orange)](#) 
[![](https://img.shields.io/badge/-Random--Forest-orange)](#) 
[![](https://img.shields.io/badge/-Support--Vector--Machine-orange)](#) 
[![](https://img.shields.io/badge/-K--Nearest--Neighbors-orange)](#)  
[![](https://img.shields.io/badge/-Gaussian--Naive--Bayes-orange)](#)
[![](https://img.shields.io/badge/-XG--Boost-orange)](#)
[![](https://img.shields.io/badge/-Python-brightgreen)](#)

Machine Learning: Field of study that gives computers the ability to learn without being explicitly programmed

## Outcome

1. Have a good understanding of the fundamental issues and challenges of machine learning. 

2. Have an understanding of the strengths and weaknesses of various machine learning approaches. 

3. Be able to design and implement various machine learning algorithms in a range of real-world applications.

### Logistic Regression

```python
logmodel = LogisticRegression(max_iter=10000, C=0.05) 
```

### Decision Tree

```python
dtree = DecisionTreeClassifier(criterion='gini') #criterion = entopy, gini
```

### Random Forest

```python
rfc = RandomForestClassifier(n_estimators = 2000)#criterion = entopy,gini
```

### Support Vector Machine

```python
svm = SVC(kernel = 'sigmoid')
```

### Naive Bayes

```python
gaussiannb = GaussianNB()
```

### XGBoost

```python
xgb = XGBClassifier()
```
