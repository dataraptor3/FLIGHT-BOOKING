<h1>Project Report: Predicting Flight Prices</h1>
<h3>Introduction:</h3>
Airline companies are constantly seeking ways to optimize ticket pricing for increased revenue and improved customer satisfaction. In this project, we aim to develop predictive models to estimate flight prices based on various features such as airline, source city, departure time, arrival time, destination city, class, duration, and days left for departure.

Data Exploration:
We started by exploring the dataset, which consists of information about different flights. Key insights from the exploration include:

A summary of the dataset's basic statistics.
Histograms and box plots for visualizing the distribution of key features.
Identification of trends, outliers, or patterns in the data.
Example Graphs:

Histograms and box plots for key features (e.g., duration, price).
Data Preprocessing:
To prepare the data for modeling, we performed the following preprocessing steps:

Handling missing values.
Encoding categorical variables using one-hot encoding.
Standardizing numerical features.
Example Graphs:

Visualization of missing values.
Feature Selection and Engineering:
We applied feature selection techniques to choose the most relevant features for our models. Additionally, we created new features to capture additional information.


Feature importance plot from a tree-based model.
Model Training:
We trained three different models: Linear Regression, Decision Tree Regressor, and Random Forest Regressor. The data was split into training and testing sets, and hyperparameter tuning was performed.

Model Evaluation:
The models were evaluated using various metrics, including R-squared, Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), Mean Squared Error (MSE), and Root Mean Square Error (RMSE).

Bar chart comparing model performance metrics.
Insights and Interpretation:
Based on the model evaluations, the Random Forest Regressor outperformed the other models with a lower MAPE and RMSE. Key insights include:

Identification of influential features.
Understanding the model's predictive accuracy.
Conclusion:
In conclusion, our predictive models provide valuable insights into estimating flight prices. The Random Forest Regressor is recommended for its superior performance.
