# Predicting California Housing Prices Using Linear Regression

## Project Overview  
This project demonstrates an end-to-end machine learning workflow to predict median house prices in California using the California Housing dataset from `scikit-learn`. It covers data loading, preprocessing, training/testing split, model training with Linear Regression, and evaluation.

## Dataset  
The dataset contains features such as median income, house age, average rooms, and location-related attributes for California districts. The target variable is the median house price.

## Approach  
- Loaded and explored the dataset using Pandas  
- Split data into training (80%) and testing (20%) sets  
- Trained a Linear Regression model on the training data  
- Evaluated model performance using Mean Squared Error (MSE) and R² score  

## Results  
- Achieved an R² score of approximately 0.59 on the test set  
- The model explains about 59% of the variance in house prices based on input features  

## Next Steps  
- Improve model performance by adding feature engineering  
- Experiment with more complex models like Random Forests or Gradient Boosting  
- Tune hyperparameters and perform cross-validation  

## How to Run  
1. Clone the repository  
2. Install dependencies (`scikit-learn`, `pandas`, `matplotlib`)  
3. Run the notebook or script file  
