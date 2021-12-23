# Machine-Learning-Model-SVM
Machine Learning Model: SVM was created for the dataset QSAR biodegradation using python.

In this project we use Python to implement SVM on the QSAR biodegradation dataset. First, we import the important libraries and the chosen dataset. Next, we select the best features using the wrapper method and assign those features to x variable. Then we split the dataset into testing and training data before choosing the best kernels to build the model. We fitted the training dataset for all the kernels and predicted the data for both training dataset and testing dataset. The figures below show graphs of the test dataset against the predicted dataset.

![](https://github.com/kiti31/Machine-Learning-Model-SVM/blob/main/Images/1.png)


![](https://github.com/kiti31/Machine-Learning-Model-SVM/blob/main/Images/2.png)

After the prediction, we computed all the scores for accuracy, precision, recall and F1. Table 3.1.1 below shows graphs of data models, the four kernels (Linear, Polynomial, Gaussian and Sigmoid) against metric scores, Accuracy, Recall Macro Average, Recall Weight Average, Precision Macro Average, Precision Weight Average, F1 Macro Average and F1 Weight Average. The scores of all the four kernels are tabulated in Table 3.1.2.

![](https://github.com/kiti31/Machine-Learning-Model-SVM/blob/main/Images/3.png)

![](https://github.com/kiti31/Machine-Learning-Model-SVM/blob/main/Images/4.png)

![](https://github.com/kiti31/Machine-Learning-Model-SVM/blob/main/Images/5.png)


![](https://github.com/kiti31/Machine-Learning-Model-SVM/blob/main/Images/7.png)
Table 3.1.2: Metric Scores of the Four Kernels

As we can see, the accuracy for the linear model is 85% which is the highest among other types of kernels. However, accuracy only counts all of the true predicted values but not specific for each label (TruePositive, FalseNegative etc). So, we also compare the precision, recall and F1 scores for each kernel. Based on the table, the linear kernel scores the highest in all metrics for both testing and training data. Hence, we choose the linear kernel as the best model.


Group Members:

Siti Zainab Binti Sahardin

Kirtiniroopa Shankar

Rafia Hossain

Pamela Rabecca Saraswathy	
