This Jupyter Notebook demonstrates a complete **Simple Linear Regression** workflow using Python and scikit-learn to predict exam scores based on study hours.

### Overview of Steps

1. **Import Libraries:** Loads essential data science and visualization tools (`pandas`, `numpy`, `matplotlib`, `seaborn`).


2. **Load Data:** Reads the dataset (`1-studyhours.csv`).


3. **Exploratory Data Analysis:** Visualizes the relationship between study hours and exam scores using scatter plots.


4. **Data Preprocessing:**
* Splits features (`X`) and target (`y`).


* Splits the data into training and test sets using `train_test_split`.


* Scales the features using `StandardScaler`.




5. **Model Training:** Fits a `LinearRegression` model to the training data and extracts the model's coefficients and intercept.


6. **Prediction & Evaluation:**
* Generates predictions on the test set.


* Evaluates model performance using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), $R^2$ Score, and Adjusted $R^2$.




7. **Inference:** Tests the trained model with custom inputs to predict exam scores for specific study hours.
