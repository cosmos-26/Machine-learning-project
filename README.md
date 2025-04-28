**Rock vs Mine Prediction using Logistic Regression**

 
This project builds a machine learning model to classify objects detected by sonar as either Rock or Mine based on the energy patterns returned by the sonar signals.

**Project Overview**

Sonar signals reflect differently off rocks and mines. By analyzing 60 different frequency-based energy readings, this project uses a Logistic Regression model to predict whether a sonar return corresponds to a rock or a mine.

**Technologies Used**

Python

NumPy

Pandas

Scikit-learn (sklearn)

**Dataset Information**

Dataset: Sonar Dataset (Binary Classification)

Features: 60 continuous numerical attributes

Label:

R → Rock

M → Mine

Total Records: 208

**Project Workflow**

_Data Loading_

Load the sonar dataset into a pandas dataframe.

_Data Exploration_

Check class distribution (R vs M).
Analyze mean values grouped by label.

_Data Preprocessing_

Split data into features (X) and label (Y).
Further split into training and testing sets using train_test_split with stratification.

_Model Training_

Train a Logistic Regression model using the training data.

_Model Evaluation_

Calculate accuracy scores on both training and testing datasets.

_Prediction System_

Create an input system to predict if a new set of sonar measurements corresponds to a rock or a mine.

**Results**

The model achieves good accuracy on both training and test datasets.

A simple prediction system is implemented for real-time classification.

Built a simple prediction system that takes new input values and predicts the object's class (Rock or Mine).




 
