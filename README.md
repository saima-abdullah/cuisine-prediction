# Cuisine Prediction?

This repository showcases my approach to the **"What's Cooking?"** Kaggle competition, completed as part of a one-day hackathon during my **Data Science Bootcamp at General Assembly**. The competition involves building a machine learning model to classify cuisines based on a list of ingredients.
## Table of Contents
- [Project Overview](#projectoverview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Hackathon Highlights](#hackathonhighlights)
- [Results](#results)
- [Tools and Libraries](#toolsandlibraries)
- [Future Work](#futurework)


## Project Overview

The goal of this project was to develop a predictive model that identifies the cuisine of a dish based solely on its ingredients. Given the time constraints of a one-day hackathon, the focus was on creating a robust pipeline with exploratory data analysis, feature engineering, and modeling.

- **Competition Link:** [Kaggle - What's Cooking?](https://www.kaggle.com/c/whats-cooking)
- **Task:** Multi-class classification of cuisines.
- **Approach:** Build a machine learning pipeline that processes ingredients and predicts cuisines with high accuracy.

## Dataset

The dataset contains recipes with the following fields:

- `id`: Unique identifier for each recipe.
- `cuisine`: The target variable — the cuisine of the dish (e.g., Italian, Mexican, etc.).
- `ingredients`: A list of ingredients used in the recipe.

### Files Used:
1. **`train.json`**: Training data with cuisine labels and ingredients.
2. **`test.json`**: Test data for predictions.
3. **`sample_submission.csv`**: Example submission file format.

## Methodology

 1. **Exploratory Data Analysis (EDA):**
   - Visualized the distribution of cuisines.
   - Analyzed ingredient frequency by cuisine.
   - Identified common and unique ingredients for each cuisine.

 2. **Preprocessing:**
 
   - Cleaned and tokenized ingredient lists.
   - Used techniques like TF-IDF vectorization and Count Vectorization for text representation.



 3. **Modeling:**
   - Tested multiple machine learning models, including:
     - Logistic Regression
     - XGBoost
   - Use hyperparameter tuning to improve performance.
4. **Evaluation:**
 - Used accuracy, F1 score, Recall metrics for evaluation.
   - Applied cross-validation to ensure generalization.


 


 5. **Deployment and Submission:**
   - Generated predictions for the test dataset.
   - Created a formatted submission file for Kaggle.

## Hackathon Highlights

- **Time Constraints:** Completed this project within a single day, balancing efficiency and experimentation.
- **Collaborative Learning:** Gained valuable insights from peer discussions and feedback.
- **Tools and Skills:** Reinforced key data science skills, including feature engineering, model building, and rapid prototyping.

## Results

- Logistic Regression
   - **Training Accuracy:** 86%
   - **Testing Accuracy:** 78%
   - **Recall (Weighted Average):** 0.78
   - **F1 Score (Weighted Average):** 0.78

- XGBoost
   - **Training Accuracy:** 74%
   - **Testing Accuracy:** 72%
   - **Recall (Weighted Average):** 0.72
   - **F1 Score (Weighted Average):** 0.71


## Tools and Libraries

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib and Seaborn for visualization

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone [https://github.com/saima-abdullah/cuisine-prediction]
   cd cuisine-prediction
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
## Future Work

- Explore more advanced NLP techniques like Word2Vec or embeddings.
- Improve accuracy by using ensemble methods.
- Deploy the model using a web application for real-time predictions.

   
