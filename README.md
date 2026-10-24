# House Price Prediction using Machine Learning

## Project Overview
This project predicts house prices using Machine Learning algorithms. The dataset contains different features related to houses, which are used to train models and predict house prices.

## Objectives
- Analyze and preprocess house price data.
- Handle missing values and duplicate records.
- Perform feature encoding and data preparation.
- Train and evaluate different Machine Learning models.
- Compare model performance using evaluation metrics.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithms
- Linear Regression / Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regression (SVR)

## Data Preprocessing
- Removed duplicate records.
- Handled missing values.
- Created additional date-related features.
- Applied One-Hot Encoding to categorical features.
- Split the dataset into training and testing sets.

## Model Evaluation
The models were evaluated using the following metrics:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Measures how well the model explains the variation in house prices.
- **Adjusted R² Score:** Evaluates model performance while considering the number of features.

## Best Model
The Random Forest Regressor achieved an R² score of approximately **0.9275** in the current experiment, making it the best-performing model among the compared models.

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Open the project notebook in Jupyter Notebook or VS Code.
4. Run the notebook cells in order.
5. Review the model evaluation results.

## Conclusion
This project demonstrates how Machine Learning regression algorithms can be used to predict house prices. Different models were compared, and Random Forest performed best in the current experiment based on the R² score.

## Author
Alex Macwan
