# TwitterTrendMining
The project aims to predict taxi trip prices using regression-based machine learning algorithms and comprehensive data preprocessing techniques. The system analyzes features such as trip distance, passenger count, time of day, traffic conditions, and weather to provide accurate price predictions.
# Features
- Data Preprocessing: Handles missing values using imputation (mean, median, mode), encodes categorical variables, and standardizes numerical features.
- Feature Engineering: Selects relevant features and creates polynomial features to capture non-linear relationships.
- Machine Learning Models:
  - Linear Regression: Baseline model for linear relationships.
  - Ridge Regression: Uses L2 regularization to improve generalization.
  - Polynomial Regression: Captures non-linear patterns in the data.
  - Decision Tree Regression: Models complex relationships using hierarchical decisions.
- Model Evaluation: Assesses performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared (R²), and accuracy.
- Data Visualization: Includes correlation heatmaps, scatter plots, bar charts, and residual plots to analyze data patterns and model performance.

# Results
The project evaluated four regression models:
- Decision Tree Regression: Best performer with an R² of 0.816 and accuracy of 81.59% (MSE: 0.098, MAE: 0.231).
- Polynomial Regression: Highest R² of 0.905, accuracy of 80.47% (MSE: 0.050, MAE: 0.140).
- Linear Regression: Accuracy of 76.7%.
- Ridge Regression: Accuracy of 76.9%.
- The Decision Tree model showed superior predictive capability, while Polynomial Regression excelled in capturing underlying data relationships.
# Software Requirements
- Programming Language: Python 3.x
- Libraries:
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
- Development Environment: Jupyter Notebook or Google Colab
# Hardware Requirements
- Processor: Intel i3 or equivalent
- Memory: 4 GB RAM or higher
- Storage: 5 GB free space
- Internet Connection: Required for accessing cloud-based platforms like Google Colab
# License
- This project is licensed under the MIT License. See the LICENSE file for details.
# Dataset
The project uses the taxi_trip_pricing.csv dataset, which includes features such as trip distance, passenger count, time of day, traffic conditions, weather, and trip price. Ensure the dataset is available in the project directory before running the code.
