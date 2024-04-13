# neural-network-challenge-1

## Overview ##
Use neural networks and the features listed in the provided dataset to create a model that will predict the likelihood that an applicant will repay their student loan.

### Detail ###
1. Prepare the data for use on a neural network model
     Use Pandas and scikit-learn’s StandardScaler() to preprocess the dataset. We will use it to compile and evaluate the neural network model later.
     - Read the data from CSV datafile to Pandas DataFrame
     - Create the features (X) and target (y) datasets. The target dataset is defined by the “credit_ranking” column. The remaining columns define the features 
        dataset.
     - Split the features and target sets into training and testing datasets.
     - Use scikit-learn's StandardScaler to scale the features data.

2. Compile and Evaluate a Model Using a Neural Network
     Use TensorFlow to design a deep neural network model. The model uses the dataset’s features to predict the credit quality of a student based on the features 
     in the dataset. Determine the number of layers and the number of neurons on each layer for the model. Then, compile and fit the model. Finally, evaluate the 
     model to calculate its loss and accuracy.
     - Create a deep neural network by assigning the number of input features, the number of layers, and the number of neurons on each layer using TensorFlow’s   
        Keras.
     - Compile and fit the model using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric.
     - Evaluate the model using the test data to determine the model’s loss and accuracy.
     - Save and export the model to a keras file, and name the file student_loans.keras.

3. Predict loan repayment success by using the neural network model
     Use the saved model to make predictions on the reserved testing data.
     - Reload saved model.
     - Make predictions on the testing data, saving them to a DataFrame and rounding the predictions to binary values.
     - Generate a classification report with the predictions and testing data.

4. Discuss creating a recommendation system for student loans
     - Describe the data that we would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data 
        would be relevant and appropriate.
     - Based on the data we chose to use in this recommendation system, would our model be using collaborative filtering, content-based filtering, or context- 
        based filtering? Justify why the data we selected would be suitable for our choice of filtering method.
     - Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these 
        challenges would be of concern for a student loan recommendation system.
   
