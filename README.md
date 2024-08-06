# Heart Disease Prediction

## Exploring Data Analysis
``EDA.ipynb`` - Compares bagged decision tree and logistic regression

## Project Structure
CVDs Prediction/
│
├── Exploratory Data Analysis/
│   ├── images/
│   └── Models/
│ 
├── Flask/
│   ├── static/
│   ├── templates/
│   ├── app.py


## Installation
Clone the repository:
git clone https://github.com/yourusername/heart-disease-prediction.git

## Set up
In "Models" folder, run models.py to generate neccessary machine learning models.

## Usage
1) Open the ``flask`` folder in terminal.
2) Run ``python app.py`` on the command line
3) Open the URL (localhost) on your browser.
- It should look something like this: ``http://127.0.0.1:5000/``

## MAKING CHANGES TO DATASET:
- If you're changing the model, Make sure to rerun ``python models.py`` in the ``Exploratory Data Analysis\Models`` folder to create a new "bagged_decision_tree_model.pkl" file.