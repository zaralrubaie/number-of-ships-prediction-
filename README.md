# Number of Ships Prediction

This project focuses on predicting the **number of ships** using multiple datasets and machine learning techniques. The workflow includes data cleaning, exploration, preprocessing, model training, evaluation, and visualization.

## Datasets

- **df1, df2, df3, df4**: Original datasets containing ship-related information.
- Data from **df3 and df4** were merged (union) to create a combined dataset.
- **df1** was selected for prediction after cleaning and preprocessing.

## Data Cleaning & Preprocessing

- Unnecessary columns and columns with missing values (`NaN`) were dropped.
- Data exploration was performed to understand the structure and quality of the datasets.
- **Scaling** was applied using `MinMaxScaler` to normalize features for modeling.

## Machine Learning

- **Train-Test Split:** Done using `sklearn` to separate features and target.
- **Model Used:** Random Forest Regressor.
- **Metrics:** Model performance was evaluated using:
  - Mean Absolute Error (MAE)
  - R² Score (Coefficient of Determination)

## Visualization

- A **scatter plot** was created to compare actual vs predicted values of the number of ships, providing a visual understanding of model accuracy.

## Usage

1. Load the datasets (`df1` to `df4`).
2. Perform cleaning and preprocessing as described.
3. Train the Random Forest Regressor on `df1`.
4. Evaluate model performance using MAE and R².
5. Visualize results with a scatter plot.

## Conclusion

This workflow demonstrates a complete machine learning pipeline for predicting ship counts from multiple sources, including data cleaning, feature scaling, modeling, evaluation, and visualization. The scatter plot helps assess how well the predictions match the actual ship counts.

