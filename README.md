# LSTM Model for Binary Classification

## Description

This project involves building and training an LSTM (Long Short-Term Memory) model for binary classification. The primary objective is to preprocess the data, train the model, and evaluate its performance.

### Steps Involved

1. **Import Libraries**: The necessary libraries such as NumPy, pandas, scikit-learn, Keras, and PrettyTable are imported.

2. **Load and Preprocess the Data**: The dataset is loaded from a CSV file. The data is preprocessed by mapping the target variable to binary values, splitting the data into training and testing sets, standardizing the features, and reshaping the data for LSTM input.

3. **Build the LSTM Model**: An LSTM model is constructed using the Keras Sequential API. The model architecture includes multiple LSTM layers with dropout layers in between to prevent overfitting, and a dense output layer with a sigmoid activation function for binary classification.

4. **Compile and Train the Model**: The model is compiled using the Adam optimizer and binary cross-entropy loss function. Early stopping is implemented to prevent overfitting by monitoring the validation loss. The model is then trained on the training data, with a portion of the data reserved for validation.

5. **Evaluate the Model**: The trained model is evaluated on the test data to determine its performance. Metrics such as test loss and test accuracy are calculated and displayed.

6. **Display Training Results**: The training and validation results over the epochs are displayed in a tabular format using PrettyTable for better visualization. The final test loss and test accuracy are also printed.

This project demonstrates a complete workflow for building and training an LSTM model for binary classification, from data preprocessing to model evaluation. The results provide insights into the model's performance and highlight areas for potential improvement.
