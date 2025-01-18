# Task_04---Sales-Prediction-CodSoft

# Advertising Sales Prediction

This project involves building a Linear Regression model to predict sales based on advertising data. The dataset contains information about advertising expenditures across three channels (TV, Radio, and Newspaper) and the corresponding sales figures.

## Project Structure

The project is implemented using Python, with the following major steps:

1. **Data Loading**
   - The dataset (`advertising.csv`) is loaded using `pandas`.
   - Exploratory Data Analysis (EDA) is performed to understand the dataset.

2. **Data Preprocessing**
   - Handling missing values and duplicate records.
   - Scaling the features using `StandardScaler`.

3. **Data Visualization**
   - Correlation heatmaps and line plots using `seaborn` and `matplotlib` to explore relationships.

4. **Model Development**
   - Splitting the data into training and testing sets using `train_test_split`.
   - Training a Linear Regression model using `scikit-learn`.

5. **Model Evaluation**
   - Calculating metrics such as R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

6. **Prediction**
   - Making predictions using the trained model for both test data and new inputs.



## Example

Given the following advertising expenditures:

| TV    | Radio | Newspaper |
|-------|-------|-----------|
| 180.8 | 10.8  | 58.4      |

The predicted sales are approximately **17.9**.

## Results

- R-squared: The proportion of variance in the dependent variable that is predictable from the independent variables.
- MAE and RMSE provide insights into the model's prediction errors.


