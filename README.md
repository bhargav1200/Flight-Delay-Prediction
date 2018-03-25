# Flight-Delay-Prediction
This repository hosts code and files for the project "Flight Delay Prediction". This project was done as part of our course, "Topics in Data Science". Following were the steps involved in the project.

Steps:

1. Flight data from the BTS website was downloaded for the years 2013 - 2016
2. Pandas library was used to perform basic preprocessing of data like rmoval of null values, label encoding and onehot encoding for inputs and output varaibles.
3. The data was then divided into Training and Testing data in the ratio 70:30 respectively.
4. A Random Forests classifier was trained with the training data.
5. A 3 - fold Cross Validation was performed on the Training dataset to find the optimal set of hyperparameters for the Random Forest classifier.
6. The model is retrained with the optimal set of hyperparameters.
7. The performance of the model is measured by plotting the ROC curves and Confusion Matrix with the 30% Testing Data.

The Project report contains the details has been included in the repository.

