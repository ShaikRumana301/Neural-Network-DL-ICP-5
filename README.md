# Neural-Network-DL-ICP-5

Student ID: 700752115, Student Name: Rumana Shaik

Video Link: 

The following steps are followed for ICP-5:

In Jupiter notepad written the code for the following and mentioned the comments for the code and uploaded the "ICP-5.ipynb" to repo:
1.	Implemented Naïve Bayes method using scikit-learn library
  - Used dataset available with name glass 
  - Used train_test_split to create training and testing part
  - Evaluated the model on test part using score and classification report. 

3.	Implemented linear SVM method using scikit library
  - Used the same dataset above
  - Used train_test_split to create training and testing part
  - Evaluated the model on test part using score and classfiication report.

In the "Neural Networks & DL ICP-5 Screenshots & Github link.pdf" file consists of screenshots of the resultant compiled code and Github link to the repository.

In the Video Link consists of Video regarding the technical explanation of the code.

Conclusion:

When we compare the Naïve Bayes and linear SVM both read the glass.csv data set and x_train has all the data except for type column data and y_train had only type column data x_train and y_train has been divided into 80:20 ratio. Declared naive Bayes method in Code 1 and linear SVM method for Code 2, to fit and train data. Following the training, predictions are made, and the results are stored in y_pred, with the actual data available in y_test.
After running both methods and comparing the accuracy, we can say that Linear SVM has a better accuracy score than Gaussian Naive Bayes. The reason for this could be because Linear SVM is better suited for complex and non-linearly separable datasets. The SVM algorithm tries to find the maximum margin between the data points and the decision boundary, which makes it robust to outliers and non-linearities, where it finds the hyper plane. Additionally, SVM allows for more flexibility in terms of choosing different kernel functions to tackle different types of data distributions. Gaussian Naive Bayes, on the other hand, assumes independence between the features and is not as robust as SVM for complex datasets.

The dataset size and structure, if the data has many features and is easy to interpret, Naive Bayes can be more effective. The data distribution, Naive Bayes assumes that the features are independent, if the features in the data are not independent, the performance of Naive Bayes can decrease.
The accuracy of the model can also depend on the choice of hyperparameters, if the hyperparameters of the Naïve Bayes algorithm were not optimized, this could result in a lower accuracy score. It is important to keep in mind that accuracy is not the only evaluation metric that should be considered, other metrics such as precision, recall, and f1-score should also be considered to get a comprehensive evaluation on performance.



