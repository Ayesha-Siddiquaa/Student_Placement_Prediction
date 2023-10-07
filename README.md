# Student_Placement_Prediction

## Overview

This project is aimed at predicting the placement status of students based on their CGPA (Cumulative Grade Point Average). It uses a machine learning model to classify students into two categories: "Placed" or "Not Placed," depending on their CGPA scores.

The project consists of the following components:

1. Data Collection: Data about students' CGPA and placement status is collected from a CSV file (`placement.csv`).

2. Data Preprocessing: The data is cleaned and preprocessed to prepare it for training the machine learning model.

3. Machine Learning Model: A Logistic Regression model is trained on the preprocessed data to predict placement status.

4. Gradio Interface: An interactive web interface is created using Gradio, allowing users to input their CGPA and receive real-time placement predictions.

Project Structure:
   *train_model.py: Python script for training the machine learning model.
   *gradio_interface.py: Python script for creating the Gradio interface.
   *placement.csv: CSV file containing student data (CGPA and placement status).
