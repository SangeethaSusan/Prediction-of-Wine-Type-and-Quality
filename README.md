# Prediction of Wine Type and Quality

## Overview
This project examines the application of Deep Learning techniques in classifying and predicting the quality of wines based on their physicochemical properties. The dataset includes features such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, sulphur dioxide levels, density, pH, sulphates, alcohol content, and quality. An additional column, `type`, indicates 0 and 1 for white and red wine, respectively.

We implemented:
- **Classification**: An Artificial Neural Network (ANN), specifically a Feedforward Neural Network (FNN), to classify wines as red or white.
- **Regression**: Traditional ML algorithms (Linear Regression, Random Forest, XGBoost, Gradient Boosting) and Deep Learning models to predict wine quality scores.

## Dataset
The dataset used in this project is based on the publicly available [Wine Quality dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality) from the UCI Machine Learning Repository.  
Some versions of this dataset are also available on Kaggle.

## Methods
- **Classification**: ANN/FNN architecture for red vs. white wine classification.
- **Regression**: Linear Regression, Random Forest, XGBoost, Gradient Boosting, and Neural Networks for quality prediction.
- **Evaluation Metrics**: Accuracy for classification; R² score for regression.

## Results
- **Classification**: High accuracy in distinguishing wine types (red/white).
- **Regression**: Moderate R² scores across models, reflecting the difficulty of predicting subjective quality using only physicochemical data.

## Insights
- Deep Learning methods are highly effective for categorical classification tasks.
- Regression approaches reveal the limitations of physicochemical properties alone for predicting subjective quality scores.
- Future improvements could include additional sensory or consumer preference data.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/SangeethaSusan/Prediction-of-Wine-Type-and-Quality.git

- pip install tensorflow scikit-learn pandas numpy matplotlib 
- jupyter notebook "Prediction of Wine Type and Quality using Deep Learning.ipynb"
