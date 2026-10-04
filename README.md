# Women's Reproductive Health Recommendation System

A prototype recommendation system focused on women's reproductive health information. The project combines content-based filtering (CBF), recommendation ratings, and an experiment comparing XGBoost with Random Forest.

## Project Overview

This project explores how a computer-based system can recommend relevant reproductive health information. Content-based filtering generates recommendations, while a reinforcement-learning component records the rating given to each recommendation as user feedback.

The project also compares XGBoost and Random Forest for **choosing the best model for giving any recommendations based on the models result**.

## How It Works

1. The system uses **Random Forest** as input.
2. Content-based filtering (CBF) generates recommendations based on relevant content features.
3. A user can provide a rating for a recommendation.
4. The reinforcement-learning component records the rating associated with that recommendation.
5. XGBoost and Random Forest are compared for **the recommendations that being choose by the user's symptoms** using **accuracy, macro precision, macro recall, and F1-score**.

## Models and Methods

- **Content-Based Filtering (CBF):** Generates recommendations based on the available content features.
- **Reinforcement Learning:** Records feedback ratings associated with recommendations.
- **XGBoost and Random Forest:** Compared for **giving the recommendations that being close to the knowledge based**. The results are evaluated using **accuracy, macro precision, macro recall, and F1-score**.

## Tech Stack

- **Programming language:** [e.g. Python]
- **Libraries:** [e.g. scikit-learn, XGBoost]
- **Development environment:** [e.g. Jupyter Notebook]
- **Other tools:** [add tools used in the project]

## Results

The comparison between XGBoost and Random Forest showed **that Random Forest are being choose for the best model**. Based on **evaluation metric and criteria of giving the results of recommendations**, **Random Forest** was the more suitable model for **giving the recommendations based on the symptoms that user will choose**.

## Running the Project

1. Clone this repository.
3. Open and run **this file**.
4. Follow the notebook or application instructions to view the recommendations and model comparison.

## Project Status

This project was developed as **a research for the papers**. It is a prototype for learning and experimentation.

## Responsible Use

This project is an educational prototype. It does not provide medical diagnoses or replace advice from qualified healthcare professionals. Do not include sensitive personal health information in a public dataset or repository.

## Contributors

Syahdu
