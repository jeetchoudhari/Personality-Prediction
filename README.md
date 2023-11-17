# Personality-Prediction
Overview
The objective of this project is to predict personality based on the 5 features (BIG5 – O.C.E.A.N.) that are Openness, Conscientiousness, Extroversion, Agreeableness, and Neuroticism in order to diagnose psychological problems as well to assist candidates. Specifically, the following were defined to achieve the general objective of the study:

1. Develop an app to screen candidates for college, employment
2. To diagnose psychological problems
3. Focusing on strengths, weaknesses, temperament, and style of leadership
4. Predict personality at workplace as well as for personal inventories

About this project
**Text Predictor:** The Personality of a person can be predicted by inputting any text with the help of this tab. The user interface of the web app gives option to predict the personality based on the text. The text is converted into vectors using tf-idf vectorization then, five models for the Big-Five personality traits are trained using RandomForest Algorithm. The vectors are given input to the models and the score as well as the classification is obtained.
**Questionnaire:** In this section, user undergoes 50 questions regarding the O.C.E.A.N model, 10 questions for each personality traits. The score is evaluated based on the answers to the questions and the radar graph for user’s personality is implemented. It can also be termed as Psychometric Assessment.
**Facebook:** For comparing the personality among the Facebook network or any other social media site network this tab is helpful. Comparison between user’s personality score evaluated from the Questionnaire section and the same models trained for text prediction are used here for evaluation of the scores of the Big-Five personality traits. The comparison is shown in the radar graph too on the user interface.

Registered project for copyright with diary number 16783/2021-CO/SW

Steps:
Execute model.ipynb
Save the login credentials on the Facebook to access in the file fb_login_creds.yaml
Execute fb_webscrapper.ipynb
Execute predict.ipynb
Execute app.ipynb
Run command, npx create-react-app “project-name”, on command prompt.
The folder name “project-name” will be created on Desktop. Copy the src folder into the latest created src folder.
Now after copying, run the command, npm start, on command prompt.
Now, the front-end will be visible on localhost:3000
Save all the .py and .ipynb files in the “project-name” folder.
