## Description of the problem.

### The goal is to classify wines' types (red / white) using 'Wine Quality' data-set (https://archive.ics.uci.edu/ml/datasets/Wine+Quality) available in the UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets.php). In fact, these are two data-sets related to red and white variants of the Portuguese "Vinho Verde" wine. They are directly available under this link: https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/.

### The data-sets and their possible modelling are described in details in the paper of P. Cortez, A. Cerdeira, F. Almeida, T. Matos & J. Reis. "Modeling wine preferences by data mining from physicochemical properties", published in "Decision Support Systems", Elsevier, Volume 47, Issue 4, Pages 547-553 in November 2009 (https://www.sciencedirect.com/science/article/abs/pii/S0167923609001377?via%3Dihub).

### Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (i.e. there is no data about grape types, wine brand, wine selling price, etc.).

### Above-mentioned input variables that base on the physicochemical tests are included in the first 11 columns of the data-sets:
#### 00 - fixed acidity
#### 01 - volatile acidity
#### 02 - citric acid
#### 03 - residual sugar
#### 04 - chlorides
#### 05 - free sulfur dioxide
#### 06 - total sulfur dioxide
#### 07 - density
#### 08 - pH
#### 09 - sulphates
#### 10 - alcohol
### The only one utput variable that base on the sensory data is given in the last, 12th column of the data-sets:
#### 11 - quality (score between 0 and 10)

### The classes are ordered and not balanced. It is not obvious if all input variables are relevant. Outlier detection algorithms could be used to detect the few excellent or poor wines.

### These data-sets can be viewed as classification or regression tasks. But in fact, it may be approached as a problem of risk assessment that is very common in the financial sector.
