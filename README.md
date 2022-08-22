# Tasks

Task 1-
->The code iterates over the list of orders and creates a new list, m, which is an empty list.
->The code then iterates over each value in the c array and creates a new tuple with two elements: one for the order number and one for its corresponding values.
->The code then iterates over each element in i (the original list) to create a new tuple with three elements: one for the order number, one for its corresponding values, and another element that will be used as an index into j's values.
->The code will print the following list: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 648, 649, 650, 651, 652, 653, 3]


Task 2
Train
Model	Accuracy	AUC
0	Logistic Regression	97.96077	0.623846
1	Naive Bayes Classifier	96.12000	0.677929
2	SVC(Support Vector Classification)	95.47000	0.613267
3	Random Forest	98.52000	0.694548
4	k-Nearest Neighbors	98.21000	0.664229

Test
Model	Accuracy	AUC
0	Logistic Regression	98.8	0.756539
1	Naive Bayes Classifier	92.4	0.881958
2	SVC(Support Vector Classification)	50.8	0.500000
3	Random Forest	99.4	0.755533
4	k-Nearest Neighbors	97.6	0.764588

In  both Train and Test -  Random Forest method accuracy was higher 




Task 3
Explain back propagation: Back-propagation is mainly used for imporving the accuracy of the predicition, backpropogation is also know as backward propogation. It is an algorithm used to calculate derivatives quickly.
1. If the data set is large:

We can just simply remove the rows with missing data values.
It is the quickest way, we use the rest of the data to predict the values.
2. For smaller data sets:

We can substitute missing values with the mean or average of the rest of the data using the pandas' data frame in python. There are different ways to do so, such as df.mean(), df.fillna(mean).
