# Rainfall-Runoff Linear Regression

**Machine Learning & Data Analysis Project | Hydrology | Rainfall-Runoff Prediction**

## Project Overview

This project applies **Simple Linear Regression** to investigate the relationship between rainfall and runoff and to predict runoff from rainfall measurements.

The project demonstrates a basic machine learning workflow, including data preparation, exploratory data analysis, visualization, model training, prediction, evaluation, and residual analysis.

## Objective

The main objective is to develop a simple regression model that estimates runoff based on rainfall.

## Dataset

The dataset contains **30 rainfall and runoff observations**.

* **Independent variable (X):** Rainfall (mm)
* **Dependent variable (y):** Runoff (mm)

## Methodology

The project followed these steps:

1. Created and organized the rainfall-runoff dataset.
2. Explored the dataset using descriptive statistics.
3. Checked for missing values.
4. Visualized the relationship between rainfall and runoff.
5. Prepared the independent and dependent variables.
6. Split the dataset into training and testing sets.
7. Trained a Simple Linear Regression model.
8. Generated runoff predictions.
9. Evaluated the model using MAE, MSE, RMSE, and R².
10. Visualized the regression line and residuals.
11. Used the trained model to predict runoff for a new rainfall value.

## Model

The fitted regression equation was:

**Predicted Runoff = -0.4865 + (0.2721 × Rainfall)**

The coefficient indicates that, within this dataset, a 1 mm increase in rainfall is associated with an estimated increase of approximately 0.272 mm in predicted runoff.

## Model Performance

The model produced the following results on the test dataset:

| Metric |   Result |
| ------ | -------: |
| MAE    |    0.193 |
| MSE    |    0.077 |
| RMSE   | 0.278 mm |
| R²     |    0.999 |

The results show a very strong linear relationship between rainfall and runoff in this practice dataset.

## Example Prediction

For a new rainfall measurement of **250 mm**, the trained model predicted approximately:

**67.53 mm of runoff**

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab
* GitHub

## Key Skills Demonstrated

* Data cleaning and preparation
* Exploratory data analysis
* Data visualization
* Statistical interpretation
* Simple Linear Regression
* Model evaluation
* Prediction
* Residual analysis
* Python programming

## Limitations

This project uses a small practice dataset with a very strong linear relationship between rainfall and runoff. Real-world rainfall-runoff processes are more complex and may depend on additional factors such as soil properties, land use, slope, antecedent moisture conditions, evapotranspiration, drainage characteristics, and watershed geometry.

Therefore, the results should not be interpreted as a real-world hydrological model.

## Future Improvements

Future versions of this project could:

* Use a larger real-world rainfall-runoff dataset.
* Include additional hydrological variables.
* Apply Multiple Linear Regression.
* Compare different machine learning algorithms.
* Incorporate GIS and remote sensing data.
* Develop rainfall-runoff forecasting models.
* Investigate flood prediction using machine learning.

## Author

**Jamiu Abimbola Kolawole, GMNSE**

Civil & Environmental Engineering | Data Analyst | Hydrology | Water Resources | Machine Learning

