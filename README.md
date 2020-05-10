# Udacity - Deep Learning Nanodegree

## Project 5: Sentiment-Analysis-Web-App-with-PyTorch-and-SageMaker

In this project, I built a simple web page which a user can use to enter a movie review. The web page sends the review off to a deployed model which classifies the sentiment of the review as positive or negative.

The main artefacts are:

-**SageMaker Project.ipynb** : Jupuyter notebook that goes through the process, including:

-Download the data.
-Process / Prepare the data.
-Upload the processed data to S3.
-Train a chosen model.
-Test the trained model.
-Deploy the trained model.
-Use the deployed model.

-**/website/index.html**: The frontend of the app. 

Bear in mind that the app will not work unless the steps in the model have been followed in order to deploy a trained model on SageMaker.

Various parts of the model building, training, deployment and inference have been implemented in the Python scripts in /train and /serve.
