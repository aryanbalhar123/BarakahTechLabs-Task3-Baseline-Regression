# Barakah TechLabs – Task 3: Baseline Regression

## Project Overview

This project is part of the Barakah TechLabs Applied Data Scientist Internship.

The objective of this task is to build baseline regression models to predict median house values using the California Housing dataset.

Two regression algorithms were implemented and evaluated:

- Linear Regression
- Random Forest Regressor

The models were evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Dataset

The project uses the **California Housing Dataset** available through Scikit-learn.

The dataset contains information about different housing areas in California, including:

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

The target variable is:

- `MedHouseVal` – Median House Value

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

The project follows a complete baseline regression workflow:

1. Dataset Loading
2. Exploratory Data Analysis
3. Data Inspection
4. Missing Value Analysis
5. Feature and Target Selection
6. Target Distribution Analysis
7. Correlation Analysis
8. Train-Test Split
9. Linear Regression Model
10. Random Forest Regression Model
11. Model Prediction
12. Model Evaluation
13. Model Performance Comparison
14. Visualization of Predictions

## Models

### 1. Linear Regression

Linear Regression was used as the baseline regression model.

The model was trained on the training dataset and evaluated on the test dataset using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

### 2. Random Forest Regressor

Random Forest Regressor was implemented as a second regression model.

The model used 100 decision trees and was evaluated using the same MAE and RMSE metrics.

## Evaluation Metrics

### Mean Absolute Error (MAE)

MAE measures the average absolute difference between the actual and predicted values.

Lower MAE indicates smaller prediction errors.

### Root Mean Squared Error (RMSE)

RMSE measures the square root of the average squared prediction errors.

Lower RMSE indicates better prediction performance.

## Results

| Model | MAE | RMSE |
|---|---:|---:|
| Linear Regression | ~0.535 | ~0.751 |
| Random Forest | ~0.328 | ~0.506 |

Based on the test-set results, the Random Forest Regressor produced lower MAE and RMSE values than Linear Regression on this dataset.

## Visualizations

The notebook includes:

- Target variable distribution
- Correlation heatmap
- Model performance comparison
- Actual vs Predicted values plot

## Conclusion

This project demonstrates a complete baseline regression workflow using the California Housing dataset.

Linear Regression and Random Forest Regressor were trained and evaluated using MAE and RMSE.

The Random Forest model achieved lower error values on the test dataset compared with Linear Regression, demonstrating better performance for this particular test split.

## Repository Contents

```text
BarakahTechLabs-Task3-Baseline-Regression/
│
├── Task3_Baseline_Regression.ipynb
└── README.md
