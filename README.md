# Emotion Detection and Suicidal Intention Prediction of Depressed Patients using ML

This project aims to develop a machine learning model that can detect emotions of a person and predict suicidal tendencies in depressed patients based on their facial expressions detected by the emotion detection model.

# Features

The developed ML model takes the details of the depressed patients with the image of the face as input, detects the emotion based on the expression in the image and predicts the tendency of suicidal intentions of the patient based on the detected emotion.
For emotion detection, DeepFace library of python is used to detect the emotion of the face in the image.
For suicidal intention prediction, decision tree model is used to train the model.

# Installation

Clone the repository:
$ gh repo clone shrutichaubey2501/intention-Prediction-of-depressed-patients<br />
install anaconda

# Usage

Run the file "run.ipynb"<br />
provide valid inputs

# Endpoints
/suicide.csv : dataset of depressed patients<br />
/suicide_prediction.ipynb : training and testing of the dataset using ML model<br />
/decisiontree_model.joblib : trained decision tree model for suicide intention prediction<br />
/run.ipynb : main file that needs to be run in order to take input from the user and display the output using the trained model<br />
