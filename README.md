# Chicken Disease Project
A Webapp to classify different sounds from UrbanSound8K Dataste.

## Project flow: 
1. Data Ingestion (data unzipping)
2. Prepare Base Model (defining model and required parameters and hyperparameters)
3. Define Callbacks (defining callbacks used during training)
4. Train Model (train the model on dataset)
5. Evaluate Model (evaluate the model on defined evaluation metrics)
6. Prediction (predict image on trained model)

## Tech stack used:
1. GitHub
2. DVC
3. Docker

## Github Repository
### Clone Repository
```git clone https://github.com/Mayuresh999/UrbanSound8K-Classification-Project.git```
### Install Requirements
```pip install -r requirements.txt```
### Run Project
```python app.py```
### OR...
## Pull Docker Image
```docker pull mayuresh999/UrbanSound8K-Classification-Project:latest```
## Run Image
```docker run -it -p 8080:8080 UrbanSound8K-Classification-Project:latest```

It will start the project in localhost:8080