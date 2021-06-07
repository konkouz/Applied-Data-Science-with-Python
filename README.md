# Applied Data Science with Python

This repository comprises the programming assignments done for the Applied Data Science with Python specialisation by the University of Michigan (Coursera Platform)*.

The courses included in the specialization are: 

1. [Course 1: Introduction to Data Science in Python](#Course-1:-Introduction-to-Data-Science-in-Python)
2. [Course 2: Applied Plotting, Charting & Data Representation in Python](#Course-2:-Applied-Plotting,-Charting-&-Data-Representation-in-Python)
3. [Course 3: Applied Machine Learning in Python](#Course-3:-Applied-Machine-Learning-in-Python)
4. [Course 4: Applied Text Mining in Python](#Course-4:-Applied-Text-Mining-in-Python)
5. [Course 5: Applied Social Network Analysis in Python](#Course-5:-Applied-Social-Network-Analysis-in-Python)



## Course 1: Introduction to Data Science in Python
Introduces the basics of python programming libraries for data science. Use of pandas library to read, clean, sort and manipulate data and SciPy.stats for statistical analysis. (Certification: https://coursera.org/share/01a491a63f9d5593a2781218d0df3bac)


* Week 2 assignment - Pandas Introduction Part 1: Data analysis on olympic medal data extracted from Wikipedia with the use of Pandas. Part 2:  Data analysis of US census state and county data.

* Week 3 assignment - More Pandas: Intricate Data cleaning and manipulation. Imported three datasets which were cleaned, joined and reduced. Explored the data and investigated the summary statistics and correlations.

* Week 4 assignment - Hypothesis Testing: This assignment tests the hypothesis of the 2008 recesion in the US having an effect on the house prices in university towns as much as it had on other towns. Initially three datasets (housing data, university towns, timeseries of GPD) were cleaned and merged. Then the start the end and the lowest recession quarters were calculated. Lastly a t-test was performed comparing the university town values to the non-university towns values to find whether the hypothetsis of university towns being less affected by the recession is true or not.


## Course 2: Applied Plotting, Charting & Data Representation in Python

This course provides information on visualization basics, with a focus on reporting and charting using the matplotlib library, as well as the ethics and aesthetivcs behind good plotting. It introduces best practires of plotting and how to tailor data appropriately in regards to the target audience. (Certification: https://coursera.org/share/2c1cbbd8848f26e579274b7a622923a6)


* Week 2 assignment - Plotting Weather Patterns: Here a temperature time-series dataset of a decade was analysed. The objective was to create a visual that would show the average minimum and maximum temperatures throughout a year as they were calculated from the dataset and denote the days on which the average min/max temperatures were exceeded for the subsequent year. 


* Week 3 assignment - Building a  Custom Visualisation: Using a randomly produced dataset, this assignment called for an interactive bar chart that allowed the user to click a y value on the chart. According to the y-value selected the bars would change colour depending on whether y was above, below or within the confidence level for each bar.


* Week 4 assignment - Becoming an Independent Data Scientist: For this assignment a broad topic was given to each student, who was asked to find two datasets which were related and answer a question within that topic. My subject was events and tradition, and I chose to clean and analyse data about alcohol consumption during bank holidays in the US. The final visual looked at the number of bank holidays at each month and the alcohol consumption data throughout the year (2018).


## Course 3: Applied Machine Learning in Python

Introduces applied machine learning, mostly focusing on different supervised classification and regression techniques and methods using scikit-learn and giving an overview of unsupervised (clustering) techniques. Discusses the issue of dimensionality as well as model evaluation and metrics. Provides substancial knoweldge on feature selection, hyperparameter tuning (GridSearch) and data generalizability problems such as cross validation and overfitting. The course ends with a look at more advanced techniques such as building ensembles and explanations on why each method should be chosen. (Certification: https://coursera.org/share/607828df691e5c2958ac9ecdf5aa2b82)

* Week 1 assignment - Basic of Machine Learning (ML) : For this assignment the Wisconsin Breast Cancer Data Set was used to prepare train and test sets. A kNN classifier was fit on the train set using sk-learn. After being fit the model was used to predict and evaluate data from the test set.

* Week 2 assignment - Supervised ML Part 1: Used regression techniques to fit a polynomial created dataset. Evaluated different models with a variety of parameters and selected the one that best fit training and test data. Part 2: Classification problem to predict whether a mushroom is poisonous using the UCI Mushroom Data Set. Initally dummy variables were created from the dataset. Then decision trees and support vector classifiers (SVC) were fit to the training set and validation curve was used to optimise the gamma parameter (kernel width) of the SVC.

* Week 3 assignment - Evaluation: The Kaggle Fraud Data Set was used to train classifiers on predicting fraudulant transactions. Different criteria were used to evaluate and optimise a classifier. This included comparison with a dummy classifier; accuracy, precision-recall curves and ROC curve. Lastly, GridSearch was used to find the optimimum parameters for a logistic regression classifier.

* Week 4 assignment - Supervised ML Part 2: This assignment involved a data set for blight violations in Detroit. The task was to to predict whether a given blight ticket would be paid on time. For the predictive modelling students were allowed to use any machine learning technique. After the feature selection stage where any data leakage was avoided, a gradient boosted decision tree classifier was optimised with GridSearch, leading to an AUC score of 0.74 on the test set.




*Originally the assignments were done with the use of the Anaconda Jupyter notebook and the latest versions of the libraries used. Some of the assignments have been edited to comply with the Coursera online Jupyter Notebook which at the time of submission was out of date.
