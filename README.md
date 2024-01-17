# Customer-Prediction-For-Bank
The code is organized into sections for data preprocessing, model building, training, and evaluation. It demonstrates the complete process of training an ANN for predicting customer churn in a bank, followed by testing and making predictions for new data.

This code utilizes an Artificial Neural Network (ANN) built with TensorFlow to predict customer churn in a bank, considering diverse features. The trained model enables predictions on whether a customer is likely to leave the bank. Beyond mere classification accuracy, the results, evaluated through a confusion matrix, provide actionable insights for strategic decisions. By anticipating potential customer exits, the bank can implement retention strategies, thereby encouraging customer loyalty, optimizing resource allocation, and ultimately enhancing the overall customer experience. The predictive analytics derived from the ANN contribute to a data-driven approach for effective customer relationship management.

## 1. Data Preprocessing:
Libraries such as NumPy, Pandas, and TensorFlow are imported. The dataset is loaded using Pandas. Features (X) and the target variable (y) are extracted. Categorical data is encoded: 'Gender' using Label Encoding and 'Geography' using One-Hot Encoding.
# 2. Data Splitting and Scaling:
The dataset is split into training and testing sets using train_test_split from scikit-learn. Feature scaling is performed using StandardScaler to standardize feature values.
# 3. Building the Artificial Neural Network (ANN):
An instance of the Sequential model in TensorFlow is created. Dense layers are added for the input layer, two hidden layers, and the output layer.
# 4. Training the ANN:
The ANN is compiled with the 'adam' optimizer and 'binary_crossentropy' loss function. The model is trained on the training set with a batch size of 32 for 100 epochs.
# 5. Making Predictions:
The trained ANN is used to predict whether a specific customer, with given information, will leave the bank.
# 6. Test Set Predictions and Evaluation:
Predictions are made on the test set. A confusion matrix and accuracy score are calculated for model evaluation.
# 7. Customer Churn Prediction for Homework:
The model is applied to predict whether a new customer, specified with certain information, will leave the bank.
