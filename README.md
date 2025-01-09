# What's Cooking?

This repository showcases my approach to the **"What's Cooking?"** Kaggle competition, completed as part of a one-day hackathon during my **Data Science Bootcamp at General Assembly**. The competition involves building a machine learning model to classify cuisines based on a list of ingredients.

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

### 1. **Exploratory Data Analysis (EDA):**
   - Visualized the distribution of cuisines.
   - Analyzed ingredient frequency by cuisine.
   - Identified common and unique ingredients for each cuisine.

### 2. **Preprocessing:**
   - Cleaned and tokenized ingredient lists.
   - Converted text data into numerical features using TF-IDF vectorization.

### 3. **Feature Engineering:**
   - Experimented with bag-of-words and n-grams for better feature representation.
   - Focused on capturing the essence of ingredient combinations.

### 4. **Modeling:**
   - Tested multiple machine learning models, including:
     - Logistic Regression
     - Random Forest
     - Multinomial Naive Bayes
     - XGBoost
   - Used accuracy as the primary metric for evaluation.
   - Applied cross-validation to ensure generalization.

### 5. **Deployment and Submission:**
   - Generated predictions for the test dataset.
   - Created a formatted submission file for Kaggle.

## Hackathon Highlights

- **Time Constraints:** Completed this project within a single day, balancing efficiency and experimentation.
- **Collaborative Learning:** Gained valuable insights from peer discussions and feedback.
- **Tools and Skills:** Reinforced key data science skills, including feature engineering, model building, and rapid prototyping.

## Results

- **Best Model:** [Insert model name used in the final submission]
- **Accuracy:** [Insert accuracy or leaderboard score if available]
- **Leaderboard Placement:** [Optional]

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
   git clone https://github.com/your-username/whats-cooking.git
   cd whats-cooking
