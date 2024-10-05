<!-- Improved compatibility of back to top link: See: https://github.com/ardor090/Heart-Disease-Prediction/back2top -->
<a id="readme-top"></a>

<!-- *** Thanks for checking out Heart-Disease-Prediction! --> <!-- PROJECT SHIELDS --> <!-- *** Reference style links for readability. -->
[![Python][Python-logo]][Python-url] [![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO --> <br /> <div align="center"> <a href="https://github.com/ardor090/Heart-Disease-Prediction/blob/main/logo.png"> <img src="logo.png" alt="Logo" width="600" height="200"> </a> <h3 align="center">Heart Disease Prediction Model</h3> <p align="center"> A Python-based project for predicting heart disease using machine learning models! <br /> <a href="https://github.com/ardor090/Heart-Disease-Prediction"><strong>Explore the Model »</strong></a> <br /> <br /> <a href="https://zindi.africa/competitions/microsoft-x-data-science-nigeria-2024-ai-bootcamp-qualification-hackathon">Join the Competition</a> · <a href="https://github.com/ardor090/Heart-Disease-Prediction/issues">Report a Bug</a> · <a href="https://github.com/ardor090/Heart-Disease-Prediction/issues">Request a Feature</a> </p> </div> <!-- TABLE OF CONTENTS --> <details> <summary>Table of Contents</summary> <ol> <li><a href="#about-the-project">About The Project</a></li> <li><a href="#project-goal">Project Goal</a></li> <li><a href="#tools-and-libraries">Tools and Libraries</a></li> <li><a href="#steps-and-methodology">Steps and Methodology</a></li> <li><a href="#results">Results</a></li> <li><a href="#getting-started">Getting Started</a></li> <li><a href="#license">License</a></li> <li><a href="#contact">Contact</a></li> <li><a href="#acknowledgments">Acknowledgments</a></li> </ol> </details> <!-- ABOUT THE PROJECT -->
About The Project
![Product Name Screen Shot][product-screenshot]

The Heart Disease Prediction Model is built using various machine learning algorithms to predict the presence of heart disease based on patient data. The project is part of a Zindi competition aimed at predicting the likelihood of heart disease in Nigerian patients.

Project Goal
The objective of this project is to predict the risk of heart disease in individuals using their medical history and other health indicators. The machine learning models were trained on patient data to improve healthcare outcomes.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
Tools and Libraries
This project leverages the following libraries and tools:

[![Python][Python-logo]][Python-url]
[![Pandas][Pandas-logo]][Pandas-url]
[![NumPy][NumPy-logo]][NumPy-url]
[![Matplotlib][Matplotlib-logo]][Matplotlib-url]
[![Seaborn][Seaborn-logo]][Seaborn-url]
<p align="right">(<a href="#readme-top">back to top</a>)</p> <!-- STEPS and METHODOLOGY -->
Steps and Methodology
Dataset: The dataset includes various health indicators such as:

Id: Unique identifier.
Age: Age of the individual.
Sex: Gender (0 = female, 1 = male).
Chest Pain Type (cp): Categorical.
Resting Blood Pressure (trestbps).
Cholesterol (chol): Serum cholesterol in mg/dl.
Fasting Blood Sugar (fbs): 1 = true, 0 = false.
Resting ECG (restecg): Categorical.
Maximum Heart Rate (thalach).
Exercise-Induced Angina (exang): 1 = yes, 0 = no.
Oldpeak: ST depression induced by exercise.
Slope: Slope of the ST segment during peak exercise.
Number of major vessels (ca).
Thalassemia (thal): Categorical.
Target (for training): 0 = no heart disease, 1 = heart disease.
Preprocessing: Data cleaning, one-hot encoding for categorical variables, and feature scaling were performed.

Exploratory Data Analysis: Visualized trends and correlations between features.

Model Training: Various machine learning models such as XGBoost, SVM, Decision Trees, Random Forests were trained.

Feature Engineering: Interaction features were added to enhance model accuracy.

Evaluation: The models were evaluated using accuracy, precision, recall, and F1-score.

<p align="right">(<a href="#readme-top">back to top</a>)</p> <!-- RESULTS -->
Results
XGBoost and Random Forest models delivered the highest accuracy.
SVM classifier provided the most robust performance on the leaderboard.
Key lessons included optimizing feature engineering and cross-validation.
<p align="right">(<a href="#readme-top">back to top</a>)</p> <!-- GETTING STARTED -->
