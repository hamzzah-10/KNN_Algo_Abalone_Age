Abalone is a kind of snail. The age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope -- a boring and time-consuming task. Other measurements, which are easier to obtain, are used to predict the age.

Objective:
Our goal is to pridict the age of Abalone by training KNN algorithm. We have a dataset consisting of 8 features and 4177 instances. Among 8 features “Sex” will be droped as it is irrelevant for us because it contains no numeric values. Then we will split dataset. First 70% samples of the dataset will be used to train the model and last 30% samples will be used to test the model. The goal is to find the value of K at which the accuracy of the both test data and training data is max. At last a graph will be plotted which shows the relationship among K and training/test accuracies. 

1.	Tuning and Finding the Best Value of K:
The code was executed to tune the value of 'K' in the KNN algorithm. The range of K values considered was from 1 to 99. The best K value was determined based on the highest test accuracy.
The best value of K obtained: K = 85.

2.	Performance Metrics on Training Set:

Accuracy: 0.2924076607387141
Precision: 0.03326201128185178
Recall: 0.02928984961118153
F1 Score: 0.031149810550859813

![image](https://github.com/user-attachments/assets/45a32f3f-dc02-42f5-99d9-3e9c7eeaa173)

3.	Performance Metrics on Test Set:
Accuracy: 0.28890662410215484
Precision: 0.03323540213000367
Recall: 0.02942610957567875
F1 Score: 0.031214969388634994
![image](https://github.com/user-attachments/assets/92bc6550-48fc-4a50-9d0a-f41bcb59f07a)

4.	Graphical Representation:
![image](https://github.com/user-attachments/assets/e376b1f5-a845-4d2b-9919-c52d3a1fc1cb)


