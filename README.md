**Zoho Assignment_
 rotten_tomatoes_movies3.ipynb_**
 

With the given dataset, build a model to predict 'audience_rating'. Demonstrate the working of the pipeline with a notebook, also validate the model for its accuracy. Using Machine Learning

Here’s a brief summary of the code in short points:

1. **Load Data**: Import the dataset (`Rotten_Tomatoes_Movies3.xls`) and handle missing values by dropping rows with NaN values.

2. **Preprocessing**:
   - Convert DateTime columns to numeric.
   - Apply Label Encoding to categorical features (e.g., movie genres).

3. **Train-Test Split**: Split the data into 80% training and 20% testing sets.

4. **Pipeline Creation**: 
   - Use `StandardScaler` to scale features.
   - Use `RandomForestRegressor` as the model for prediction.

5. **Hyperparameter Tuning**: 
   - Define a grid of hyperparameters for Random Forest.
   - Use `GridSearchCV` to find the best model configuration based on cross-validation.

6. **Model Evaluation**: 
   - Evaluate the model’s performance on the test set using MAE, MSE, and R² score.

7. **Save Model**: Save the trained model (`audience_rating_model.pkl`) using `joblib`.

8. **Prediction on Entire Dataset**:
   - Apply preprocessing to the entire dataset.
   - Predict the `audience_rating` for all rows and add it as a new column.

9. **Model Validation**: Re-validate the model on the test set and display performance metrics (R², MAE, MSE).

