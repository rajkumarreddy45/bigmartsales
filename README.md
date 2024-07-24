## BigMart Sales Prediction Project

## Overview

This project aims to build a machine learning model to predict sales for BigMart products and deploy a web application to make the model accessible to users. It involves data preprocessing, exploratory data analysis, model building, evaluation, and deployment using Python and various libraries.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Building](#model-building)
- [Web Application](#web-application)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Features

- Data preprocessing and cleaning
- Exploratory data analysis
- Model building and evaluation
- Hyperparameter tuning
- Web application for user interaction
- Sales prediction based on user input

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bigmart-sales-prediction.git
   cd bigmart-sales-prediction
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the data preprocessing script:
   ```bash
   python data_preprocessing.py
   ```

2. Perform exploratory data analysis:
   ```bash
   python eda.py
   ```

3. Build and evaluate the machine learning models:
   ```bash
   python model_building.py
   ```

4. Start the web application:
   ```bash
   flask run
   ```

5. Open a web browser and go to `http://127.0.0.1:5000` to interact with the application.

## Model Building

1. **Data Preprocessing:** Handling missing values, normalizing formats, and creating new features.
2. **Exploratory Data Analysis:** Understanding relationships between variables and visualizing data using `matplotlib` and `seaborn`.
3. **Model Building:** Using algorithms like Linear Regression, Decision Trees, and Random Forests to predict sales.
4. **Model Evaluation:** Assessing model performance and tuning hyperparameters for optimization.
5. **Model Saving:** Storing the trained model for future use.

## Web Application

The web application is built using Flask and provides an interface for users to input product details and receive sales predictions. Key components include:

- **Routes:** Different routes handle various functionalities of the web app.
- **HTML Templates:** Frontend interface designed using HTML.
- **Integration:** The predictive model is integrated to display results dynamically based on user input.

## Results

The final model provides accurate sales predictions for BigMart products. The web application offers a user-friendly interface for real-time interaction and prediction.

