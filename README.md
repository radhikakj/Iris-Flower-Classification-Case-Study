# Iris Classification Case Study

This case study involves the classification of Iris flowers into three species based on their sepal and petal dimensions.
Various classification algorithms such as Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Decision Trees, and Random Forest are implemented and evaluated for their performance.

**Introduction**

The Iris dataset is a popular dataset used for classification tasks.
It contains measurements of sepal length, sepal width, petal length, and petal width for three different species of Iris flowers:
setosa, versicolor, and virginica. The goal of this case study is to build and evaluate classification models to predict the species of Iris flowers based on these measurements.

**Dataset**

The Iris dataset consists of 150 samples with four features (sepal length, sepal width, petal length, and petal width) and one target variable (species).
The target variable has three classes: setosa, versicolor, and virginica.


**Data Preprocessing**

Data preprocessing involves handling missing values, outliers, and encoding categorical features. 
In this case study, missing values are filled with the median, outliers are detected using the IQR method, and categorical features are encoded using label encoding.


**Exploratory Data Analysis**

Exploratory data analysis includes basic statistics, visualization of data distributions, and correlation analysis.
Descriptive statistics such as mean, median, and standard deviation are computed, and data distributions are visualized using box plots and histograms. 
Correlation analysis helps understand the relationships between features.

**Modeling**

Various classification algorithms such as Logistic Regression, KNN, SVM, Decision Trees, and Random Forest are trained on the dataset.
These models learn patterns from the input features and predict the species of Iris flowers.


**Evaluation**

Model evaluation involves assessing the performance of each classification algorithm using metrics such as accuracy, precision, recall, and F1-score.
Confusion matrices are also used to visualize the performance of the models in predicting each class.


**Conclusion**

In this case study, all classification models achieve high accuracy scores above 90%.
Logistic Regression and SVM perform slightly lower compared to other algorithms. However, overall, all models perform effectively in predicting the species of Iris flowers based on their measurements.
