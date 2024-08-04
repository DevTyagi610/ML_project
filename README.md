# Student Score Prediction

### This project understands how the student's performance (test scores) is affected by various variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course. We use the following input features : Gender, Ethnicity, Parental level of education, Lunch, Test preparation course, Reading Score and Writing Score to predict Math Score of the Student. 
### Through this analysis and prediction we aim to gain insights into the factors that influence student performance and visualize the relationships between different variables. 

### DATASET :
The dataset used for this project includes information about students' attributes such as gender, ethnicity, parental education level, lunch, test preparation course, and scores in math, reading, and writing.  
**The Categorical Features** : gender, ethnicity, parental education level, lunch, test preparation course   
**Numerical Features** : reading score, writing score, math score.

## Setup

### Prerequisites

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Flask
- Machine Learning Algorithms 

### Flow Of Project :
1) Setting up Git hub and Virtual Environment in VS Code
2) creating and Updating requirements.txt file for whole project
3) Creating Logging and Custom Exception files
4) EDA of dataset
5) Creating Data Ingestion File
6) Doing Data Transformation using Pipelining
7) Creating Model Trainer File
8) Model Hyperparameter Tuning
9) Buliding Prediciton Pipeline
10) Creating Flask app to create a basic UI to enter data and get prediction

### Steps :
- Clone the repository using : `git clone https://github.com/DevTyagi610/Student_Score_Prediction.git`
- Create a virtual environment for the project : `python -m venv venv`
- Activate the **venv** : `venv\Scripts\activate`
- install all required libraries using command : `pip install -r requirements.txt`
- run the app.py fil using command : `python app.py`
- open your localhost and go to url : `localhost:5000/predictdata` and fill in the form with details and get the predicted output
