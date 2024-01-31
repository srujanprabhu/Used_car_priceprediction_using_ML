# Used_car_priceprediction_using_ML

``Overview``
This project focuses on predicting used car prices using a machine learning model based on linear regression. The dataset was preprocessed and cleaned to handle missing values. The data was then split into training and testing sets for model evaluation. Linear regression was chosen as the predictive model, and the performance was assessed using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).

``Dataset``
The dataset used for this project contains information about used cars, including various features such as make, model, year, mileage, and price. The dataset was obtained from Kaggle and is available in the data directory. https://www.kaggle.com/datasets/rishabhkarn/used-car-dataset?resource=download

``Data Processing``

Handling Missing Values: Any missing values in the dataset were addressed through imputation or removal.
Categorical Variables: Categorical variables were encoded or transformed to be compatible with the linear regression model.

``Model Training``

The data was split into training and testing sets using a ratio of [60-40]. The linear regression model was fitted on the training data to learn the relationships between the features and the target variable (car prices).

``Model Evaluation``

The model's performance was evaluated using the following metrics:

Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)

``Future Work``

Explore the possibility of using other machine learning algorithms for comparison.
Fine-tune hyperparameters to improve model performance.
Include additional features that might enhance prediction accuracy.
