# NFL Injury Prediction Project

## **Table of Contents**
- Overview
- Datasets
- Methodology
-	Exploratory Data Analysis
-	Feature Engineering & Selection
-	Modeling


Overview

This project aims to investigate the factors that lead to injuries in the NFL, particularly lower extremity and head injuries, using multiple public datasets from Kaggle. The objectives include:
-	Conducting in‐depth exploratory data analysis (EDA) on each dataset 
-	Identifying which features (player tracking stats, field conditions, weather, etc.) are most predictive of injury risk
-	Building predictive models (logistic regression, neural networks, etc.) to classify whether a player/place/play will result in injury
-	Comparing model performance and interpreting which features are driving predictions

Datasets

Below are the key datasets / competitions used, along with relevant links:

NFL 1st & Future – Playing Surface Analytics
- Includes non‐contact lower extremity injuries, Next Gen Stats player tracking data (position, velocity, acceleration, hit angle), field/playing surface, weather, etc. 
- Link: https://www.kaggle.com/competitions/nfl-playing-surface-analytics?

NFL Big Data Bowl
Large dataset including play‐by‐play tracking, game, player info; intended for exploratory analysis and varied predictive tasks. 
- https://www.kaggle.com/competitions/nfl-big-data-bowl-2025

NFL Punt Analytics (Head Injuries during Punt Plays)
A detailed dataset of NFL punt plays including concussin injury data. 
- https://www.kaggle.com/competitions/NFL-Punt-Analytics-Competition


Methodology
  1. Data Processing & Cleaning / Exploratory Data Analysis
     •	Download data from Kaggle for each dataset.
	   •	Preprocess: handle missing values, correct data types, align time periods / seasons, unify naming conventions.
     •	Statistical summaries of injury rates by position, by playing surface, by weather, by game conditions.
     •	Visualizations: distributions, correlation matrices, time / game‐week trends, spatial / tracking visualizations.

  2.	Feature Engineering & Selection
     •	Create derived features: acceleration / deceleration, distances, angles, playing history (e.g. rest, prior injuries), field surface type, weather conditions.
     •	Use feature selection methods (e.g. univariate tests, regularization, tree‐based importance, PCA) to identify most informative variables.

  3.	Modeling
     •	Baseline models: Logistic Regression, possibly decision trees.
	   •	More advanced models: ensemble methods (Random Forest, Gradient Boosting), neural networks.
	   •	Possibly time‐series or sequence models if tracking / temporal data is involved.
	
 

 
