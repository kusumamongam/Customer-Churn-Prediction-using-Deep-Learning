This project aims to predict customer churn using deep learning techniques. Customer churn refers to the loss of clients or customers, and predicting it can help businesses take proactive measures to retain their customers. This README file provides an overview of the project, installation instructions, usage guidelines, and results.

Libraries Used
This project utilizes several Python libraries for data manipulation, visualization, and deep learning:

NumPy: For numerical operations and handling arrays.
Pandas: For data manipulation and analysis.
Matplotlib: For creating visualizations.
Scikit-learn: For preprocessing data and splitting datasets.
Keras: For building and training deep learning models.

Data Preparation:
Place your input data file (e.g., customer_data.csv) in the data/ directory. Ensure that your CSV file contains relevant features for predicting customer churn, including a target column indicating whether a customer has churned.

Data Preprocessing:
Run the data_preprocessing.py script to clean and preprocess your data. This includes:

Handling missing values
Encoding categorical variables
Scaling numerical features using StandardScaler
Splitting the dataset into training and testing sets
Model Training: Use the model.py script to build and train the deep learning model. This script includes:

Creating a Sequential model with Dense layers
Compiling the model with an appropriate loss function and optimizer
Training the model for a specified number of epochs (e.g., 100 epochs)
Evaluating the model's accuracy (achieved accuracy of 86%)
Model Evaluation: Run the evaluation.py script to evaluate the model's performance. This includes:

Generating predictions on the test set
Building a confusion matrix to visualize the model's performance.

Results
Model Accuracy: The model achieved an accuracy of 86% on the test set.
Confusion Matrix: The confusion matrix provides insights into the model's performance, showing the number of true positives, true negatives, false positives, and false negatives.
