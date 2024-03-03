
## Bogazici University - MIS 49Y - Applied Machine Learning Course

# Predictive Modeling for Seoul Bike Sharing Demand Optimization
### [Project Report 🔗](https://drive.google.com/file/d/1yifO2RnsPUAqPmQQ3OHMFeaNxzqTewfX/view?usp=sharing)
**Data Source**: [UCI Machine Learning Repository, Seoul Bike Sharing Demand Dataset](https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand)

This lecture focuses on predicting and optimizing bike demand in Seoul's bike-sharing system using
machine learning. The Seoul Bike Sharing Demand dataset.
The goal is to contribute to resource optimization, user
experience improvement, cost efficiency, and positive
environmental impact.

Machine learning algorithms, Linear Regression, Random
Forest, Gradient Boosting, and LightGBM are employed, each
serving specific purposes in capturing patterns. Feature
engineering involves extracting date features and creating
interaction terms. Data preprocessing covers handling dates,
encoding categorical data, addressing outliers, and scaling
features.

**Data Description**: The dataset contains 14 columns and 8760 rows. The columns are as follows:
- Date: The date of the data
- Rented Bike Count: The count of rented bikes
- Hour: The hour of the data
- Temperature: The temperature in Celsius
- Humidity: The humidity in percentage
- Wind Speed: The wind speed in m/s
- Visibility: The visibility in metres
- Dew Point Temperature: The dew point temperature in Celsius
- Solar Radiation: The solar radiation in MJ/m2
- Rainfall: The rainfall in mm
- Snowfall: The snowfall in cm
- Seasons: The season of the data
- Holiday: The holiday information
- Functioning Day: The functioning day information
- Day of the Week: The day of the week

**Data Preprocessing**: The dataset is preprocessed by removing the unnecessary columns and handling the missing values. The missing values are handled by using the mean of the corresponding column. The categorical columns are encoded using the One-Hot Encoding technique.

**Model Selection**: The dataset is split into training and testing sets. The following models are used to predict the bike rental demand:

- Linear Regression
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM

**Model Training**: The models are trained using the training set. The hyperparameters of the models are tuned using the Grid Search Cross-Validation technique.

**Model Evaluation**: The models are evaluated using the Mean Absolute Error (MAE) and the Root Mean Squared Error (RMSE) metrics. The model with the lowest MAE and RMSE is selected as the best model.
