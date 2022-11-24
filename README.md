# Serverless-Machine-Learning-App-Titanix
This repository is part of an assignment done in the course ID2223 Scalable Machine Learning at KTH. 


Problem description: 
Create a serverless machine learning application where we do the following;
  - Load, clean and upload the Titanic dataset to Hopsworks
  - Load the dataset from Hopsworks, train and upload a classifier model (in our case we tried with two models, XGboost and RandomForestClassifier)
  - Create a program that creates and adds a sample to the existing data in Hopsworks. 
  - Create a program that loads the data from Hopsworks, predicts on the latest inserted data, summarizes the predictions and creates and uploads a confusion matrix and prediction history to Hopsworks. 
  
  To complement our programs, we use Huggingface to create two UI:s, one that loads and shows the confusion matrix and prediction history, and the other UI that can take in features and output a prediction using the model that we trained previously. 
  
  To run the code, simply import the notebook and run the cells. You need to have your Hopsworks API-key available. NOTE! The last cell is the same as the UI application we have on huggingface. 
  
  
  
  HuggingeFace URL-Links:
    
    
    https://huggingface.co/spaces/davidt123/titanic-feature?logs=true  
    
    https://huggingface.co/spaces/davidt123/titanic-daily-report
