Project Title: Analysis of Viewer Preferences in the Harry Potter Franchise.

Team Members
1. Raghad Alamoudi:
	Proposal: Predictor Variables. 
	Presentation: Slides 11-18
	Report: Data & Results.
	Code: Graphs, Joining Data & Machine Learning Scikit-learn. 
2. Ehadaa AlMarhabi: 
	Proposal: Outcome Variable
	Presentation: Slides 6-10
	Report: Problem Statement and Background & Analysis.
	Code: Using Basic Python Syntax on the Dataset of "HarryPotterDataset.csv"
3. Manar Alharbi: 
	Proposal: Definition of “Success”.
	Presentation: Slides 1-5
	Report: Introduction & Discussion.
	Code: Data Cleaning and Preparation, Data Manipulation & Analysis.

All of us did (High-Level Statement of the Problem) in the Proposal part.


Description: The "Analysis of Viewer Preferences in the Harry Potter Franchise" project utilizes a comprehensive dataset encompassing spells, characters, locations, and financial metrics from the Harry Potter films. It aims to uncover patterns in audience engagement through narrative analysis, character insights, and financial performance evaluation. By integrating multiple dimensions of the franchise, the project seeks to identify key factors contributing to its storytelling success, such as character dynamics, magical elements, and box office performance. Ultimately, it provides actionable insights for enhancing future storytelling and marketing strategies within the franchise.

Table of Content for "Report":
1. Introduction
2. Problem Statement and Background
3. Data
4. Analysis
5. Result
6. Discussion
7. References

Installation: 
To run this project, ensure you have the following software installed:

Python: 3.8
- Anaconda: Latest version (e.g., 2023.x)
- Jupyter Notebook: Latest version
- Libraries:
	- Pandas: 1.3.5
	- Seaborn: 0.11.2
	- Matplotlib: 3.4.3
	- NumPy: 1.21.5
	- Scikit-learn: 1.0.2

Codebook: 
The following table outlines the key variables used in the analysis:
Variable names & Data Type: 
1. Movie ID: Integer
	Description: Unique identifier for each movie in the franchise.
2. Movie Title: String
	Description: Title of the film.
3. Release Year: Integer
	Description: Year the movie was released.
4. Runtime: Integer
	Description: Duration of the film in minutes.
5. Budget: Float
	Description: Production budget of the movie.
6. Box Office: Float
	Description: Revenue generated from the movie.
7. Character ID: Integer
	Description: Unique identifier for each character.
8. Character Name: String
	Description: Name of the character.
9. Species: String
	Description: Species of the character (e.g., Human, Magical Creature).
10. Gender: String 
	Description: Gender of the character.
11. House: String
	Description: Hogwarts house of the character (if applicable).
12. Patronus: String
	Description: Patronus of the character.
13. Dialogue ID: Integer
	Description: Unique identifier for each dialogue line.
14. Dialogue: String
	Description: Line of dialogue spoken by the character.
15. Place Name: String
	Description: Name of the location.
16. Place Category: String
	Description: Category of the place (e.g., Dwelling, School).
17. Profit Margin: Float
	Description: Profit margin calculated from box office and budget.


Usage
To run the analysis, open Jupyter Notebook and execute the following steps:

- Load the necessary libraries:
	import pandas as pd
	import numpy as np	
	import matplotlib.pyplot as plt
	import seaborn as sns
	Load the dataset:
		Harry_Potter = pd.read_csv('path/to/HarryPotterDataset.csv')

	from sklearn.model_selection import train_test_split  # For splitting data
	from sklearn.ensemble import GradientBoostingClassifier
	from sklearn.linear_model import LogisticRegression	
	from sklearn.neighbors import KNeighborsClassifier    
	from sklearn.metrics import accuracy_score, confusion_matrix
