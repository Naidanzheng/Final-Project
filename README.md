# Adult Census Income

#####    by <b>[Naidan Zheng](https://github.com/Naidanzheng)</b>

---

## Repo Content
- <b>Data</b> - The raw dataset can be found on the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php). 
- <b>[images](https://github.com/Naidanzheng/Final-Project/blob/Master/Image)</b> - Various plots and images used in the documents found in this repo.
- <b>[DATA 602 Final Project.ipynb](https://github.com/Naidanzheng/Final-Project/blob/Master/DATA%20602%20Final%20Project.ipynb)</b> - The main Jupyter Notebook containing the models and analysis for this project.
- <b>[README.md](README.md)</b> - A description of the project goals, process, and results.

---

## Table of Content
- <b>[Overview](https://github.com/Naidanzheng/Final-Project/blob/Master/README.md#overview) 
- <b>[Goals](https://github.com/Naidanzheng/Final-Project/blob/Master/README.md#goals) 
- <b>[Motivation & Background](https://github.com/Naidanzheng/Final-Project/blob/Master/README.md#motivation--background) 
- <b>[Data](https://github.com/Naidanzheng/Final-Project/blob/Master/README.md#data) 
- <b>[Modeling](https://github.com/Naidanzheng/Final-Project/blob/Master/README.md#modeling) 
- <b>[Conclusion](https://github.com/Naidanzheng/Final-Project/blob/Master/README.md#conclusion) 
- <b>[Future Work](https://github.com/Naidanzheng/Final-Project/blob/Master/README.md#future-work) 
- <b>[Software Requirements](https://github.com/Naidanzheng/Final-Project/blob/Master/README.md#software-requirements) 
- <b>[Resource](https://github.com/Naidanzheng/Final-Project/blob/Master/README.md#resource) 

## Overview
The significant disparity of wealth and income, especially in the United States, is a huge concern. One legitimate explanation for reducing the world's increasing level of economic disparity is the possibility of declining poverty. The concept of basic moral equality guarantees sustainable growth and promotes a nation's economic stability. Governments in various countries have tried their best to tackle this issue and provide an optimal solution.This research aims to illustrate the use of techniques of machine learning and data mining in offering a solution to the problem of income equality. To that end, the UCI Adult Dataset was used. The classification was done to predict whether, based on a certain collection of characteristics, the annual income of an individual in the US falls into the income category of either greater than 50K Dollars or less equal to 50K Dollars. In this analysis, I have used six algorithms to predict the target variable: Decision tree, SVM, Random Forest, Gaussian, KNN, and logistic Regression, and compare their accuracy scores to determine the best algorithm.
![income.png](https://github.com/Naidanzheng/Final-Project/blob/Master/Image/income.png)

## Goals
The first goal for this project it to determine whether a person makes over $50K a year by using Logistic Regression, Decision tree, SVM, Random Forest, Gaussian, and KNN, and compare their accuracy score to determine the best algorithm.

The second goal for this project is to know if a good marital relationship is a key for earning more money.

## Motivation & Background
The distribution of income is extremely important for development as it affects society's stability, determines the level of poverty for any given average per capita income and the impact of growth on poverty reduction, and also affects people's health.It finds that the Kuznets hypothesis that income distribution worsens is not at all strongly supported by the evidence as levels of income rise, whereas income growth rates are not systematically connected to changes in income distribution. Nevertheless, evidence is accumulating that a more equitable distribution of income increases economic growth. It has advanced both political and economic explanations. The result indicates that a more equitable distribution of income is beneficial for both equity and growth promotion. I am very interested in this topic because I think it is very important for everyone to know what they can do to increase their income and have better life quality, and I hope to analyze the relationship between marriage and income.

## Data
The data for our study were accessed from the University of California Irvine (UCI) Machine Learning Repository. It was actually extracted by Barry Becker using the 1994 census database. The data set includes figures on 48,842 different records and 14 attributes for 42 nations. The adult income dataset involves predicting personal income levels as above or below $50,000 per year based on personal details such as relationship and education level.  There are many more cases of incomes less than $50K than above $50K, although the skew is not severe.
![data.png](https://github.com/Naidanzheng/Final-Project/blob/Master/Image/data.png)

From this graph, we can see that a good marital relationship is a key for earning more money.
![marraige.png](https://github.com/Naidanzheng/Final-Project/blob/Master/Image/marriage.png)



## Modeling
Supervised learning is an approach to creating artificial intelligence (AI), where the program is given labeled input data and the expected output results. The AI system is specifically told what to look for, thus the model is trained until it can detect the underlying patterns and relationships, enabling it to yield good results when presented with never-before-seen data.

Supervised learning is good at classification and regression problems. In supervised learning, the aim is to make sense of data toward specific measurements.

After looking at the data, I decid to use classification algorithms. A classification algorithm tries to determine the class or the category of the data it is presented with.

The six algorithms that used in this project are:
1. Logistic Regression.
2. KNN.
3. Decision Tree.
4. SVM.
5. Random Forest.
6. Decision Tree.
7. Gaussian Naive Bayes.
![accuracy.png](https://github.com/Naidanzheng/Final-Project/blob/Master/Image/accuracy.png)
The accuracy score of Random Forest Classifer is 85.8113 which is higher than accuracy scores of other models.
Therefore, Random Forest Classifer is the best model to predict adult income by giving these varaibles.


## Conclusion
In this project, we found that income can be determined by a lot of factors, this dataset involves predicting personal income levels as above or below 50,000 dollars per year based on personal details such as relationship and education level. There are many more cases of incomes less than $50K than above 50,000 dollars, although the skew is not severe. We found that a good marital relationship is a key for earning more money, people who married have higher percentage of earning more than 50K each year.

After comparing the accuracy score of these six models, we found that Random Forest Classifer is the best model to predict adult income by giving these variables.

## Future Work
To derive even more accurate results, we'd like to expand the project with additional data, specifically 'Years'. Therefore, we will use the Time Series analysis to improve our model. Also, we can add 'parents' education level','Health' and 'Location' variables to analyze the relationships with adult income.

## Software Requirements
<pre>
Languages    : Python 3.9.0
Tools/IDE    : Anaconda, Colab
Libraries    : numPy,pandas, matplotlib, seaborn, scipy.stats, scikit-learn,warning
</pre>

<pre>
Duration     : December 2020
Last Update  : 12.7.2020
</pre>
## Resource
- <b>[Machine Learning Classification Algorithms](https://data-flair.training/blogs/machine-learning-classification-algorithms/)
- <b>[Classification Algorithms in Machine Learning: How They Work](https://monkeylearn.com/blog/classification-algorithms/)
