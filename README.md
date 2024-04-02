# Wine Quality Prediction Project

## Description
This project aims to predict the quality of wine based on various chemical properties. It explores a dataset containing information about different types of wine, including their chemical composition and quality ratings. The goal is to develop machine learning models that can accurately classify wines as either high-quality or low-quality based on their features.

## Installation
1. Clone the repository:
2. Install the required dependencies:

## Usage
1. Run the Jupyter Notebook `wine_quality_prediction.ipynb`.
2. Follow the instructions provided in the notebook to explore the dataset, preprocess the data, train machine learning models, and evaluate their performance.
3. Experiment with different models and hyperparameters to improve the predictive accuracy.

## File Structure
- `wine_quality_prediction.ipynb`: Jupyter Notebook containing the project code.
- `winequalityN.csv`: CSV file containing the dataset.

## Data
The dataset used in this project contains information about various types of wine, including the following columns:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target variable)

## Models
Three machine learning models are trained and evaluated in this project:
1. Logistic Regression
2. XGBoost Classifier
3. Support Vector Classifier (SVC)

## Results
The models are evaluated based on their training and validation accuracy using the ROC AUC score. The XGBoost Classifier performs the best among the three models, achieving the highest validation accuracy.

## Contributing
Contributions to this project are welcome. To contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them to your branch.
4. Push to your fork and submit a pull request.

