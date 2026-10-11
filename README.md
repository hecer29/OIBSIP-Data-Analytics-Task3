# House Price Prediction with Linear Regression

## Project Overview

This project focuses on predicting house prices using machine learning regression techniques. It uses the Ames Housing dataset, which contains information about residential properties and their characteristics.

The main objective is to build a Linear Regression model, evaluate its performance, and compare it with Ridge Regression.

## Objectives

- Explore and analyze the housing dataset.
- Identify relationships between house features and sale prices.
- Handle missing values and encode categorical variables.
- Build and train a Linear Regression model.
- Evaluate model performance using regression metrics.
- Compare Linear Regression with Ridge Regression.
- Visualize predictions and analyze model coefficients.

## Dataset

The Ames Housing dataset contains information about residential properties, including:

- `SalePrice` — final sale price of the house (target variable).
- `Gr Liv Area` — above-ground living area.
- `Overall Qual` — overall material and finish quality.
- `Garage Cars` — garage capacity in cars.
- `Total Bsmt SF` — total basement area.
- `Year Built` — original construction year.
- `Lot Area` — lot size.

The target variable is `SalePrice`, which the models aim to predict.

## Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Workflow

1. Importing Libraries and Loading the Dataset
2. Exploratory Data Analysis (EDA)
3. Feature Selection and Correlation Analysis
4. Data Preprocessing
5. Splitting the Dataset into Training and Testing Sets
6. Building and Training the Linear Regression Model
7. Model Evaluation
8. Visualizing Predictions and Residuals
9. Analyzing Model Coefficients
10. Comparing Models and Saving Results

## Models Used

### Linear Regression

A supervised machine learning algorithm used to predict continuous numerical values, such as house prices.

### Ridge Regression

A regularized version of Linear Regression that adds a penalty to large coefficients. It is used for comparison with the standard Linear Regression model.

## Model Performance

The models were evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and the R² score.

| Metric | Linear Regression | Ridge Regression |
|---|---:|---:|
| MSE | 913,015,555.88 | 1,224,742,000 |
| RMSE | 30,216.15 | 34,996.32 |
| R² Score | 0.8861 | 0.8472 |

### Results

Linear Regression performed better than Ridge Regression on the test dataset.

- **R² Score:** 0.8861
- **RMSE:** 30,216.15
- **Best-performing model:** Linear Regression

The R² score indicates that Linear Regression explains approximately 88.61% of the variation in house prices in the test dataset. The RMSE represents the typical magnitude of prediction errors in the target variable's units.

## Visualizations

The project includes visualizations to better understand the dataset and model performance:

- Distribution of House Prices
- Correlation Heatmap
- Actual vs. Predicted House Prices
- Residual Plot
- Model Coefficient Analysis

## Project Structure

```text
House-Price-Prediction/
│
├── house_price_prediction.ipynb
├── AmesHousing.csv
├── house_price_predictions.csv
├── model_comparison.csv
└── README.md
```

Note: Update the filenames above to match your actual project files.

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Place the dataset in the project directory.
4. Open the notebook in Jupyter Notebook or Google Colab.
5. Run the cells in order to reproduce the analysis and model results.

## Conclusion

This project demonstrates how Linear Regression can be applied to house price prediction using property characteristics. Through exploratory data analysis, preprocessing, model training, and evaluation, I gained practical experience with a complete machine learning workflow.

The comparison showed that Linear Regression outperformed Ridge Regression on the test dataset, achieving a higher R² score and lower prediction errors.

## Author

**Həcər Ibrahimli**
