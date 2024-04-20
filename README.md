# Facial Expression Recognition Project

## Project Overview
This project aims to develop a classifier capable of recognizing six distinct facial expressions: happiness, fear, surprise, anger, disgust, and sadness. The classifier utilizes 68 facial landmarks that define specific regions of the face to achieve this.

## Data Source
The dataset used in this project is derived from the `CK+` dataset, which consists of individuals mimicking various expressions. The dataset includes `csv` files that provide detailed descriptions of the facial expressions and associated facial landmarks for each subject across different sessions.

### Dataset Structure
- `emotion.csv`: This file lists subjects, sessions, and the expressions they performed.
- `omlands.csv`: Located in individual subject folders, this file contains the coordinates of the 68 facial landmarks for each subject throughout their sessions.

### Expression Intensity
Each session includes several images ranging from a neutral expression to the peak intensity of the expression.

## Project Objectives
- **Data Preparation:** Load and format data using numpy and pandas.
- **Data Analysis:** Perform descriptive and statistical analysis.
- **Visualization:** Create graphs to illustrate the data and analysis results.
- **Model Training:** Experiment with different algorithms, evaluate error rates, compare models, and select optimal hyperparameters.
- **Performance Analysis:** Assess model performance based on data size, attribute importance, and learning curves.
