# PredictFareOfAirlinesTickets
Data Description :
The dataset has 1 excel file, 
•	Data has 11 columns and 10683 rows

The data consists of the following attributes:
•	Airline: Name of Airline
•	Date of Journey: Date of journey of flight
•	Source: Source of flight
•	Destination: Destination of flight
•	Route: Route of flight
•	Dep_Time: Departure time of flight
•	Arrival_Time: Arrival time of flight
•	Duration: Duration of flight 
•	Total_Stop: Total stops of flight 
•	Additional Information: Any information about flight. For example, flight includes meal or not

Tech stack 
•	Language - Python
•	Libraries – numpy, pandas, matplotlib, seaborn, sklearn, pickle
Approach 
1. Importing the required libraries and reading the dataset.
•	Understanding the dataset

2. Exploratory Data Analysis (EDA) –
•	Data Visualization

3. Feature Engineering 
•	Dropping of unwanted columns 
•	Removal of null values
•	Checking for multi-collinearity and removal of highly correlated features

4. Model Building
•	Performing train test split
•	Linear Regression
•	Decision Tree Regressor
•	Random Forest Regressor
•	mutual_info_regression

5. Model Validation 
•	 Accuracy score
•	 r2_score
•	 MAE
•	 MSE
•	 RMSE
•	 MAPE
•	best_params_
•	best_estimator_
•	best_score_

6. Hyper parameter Tuning (RandomizedSearchCV)
7. Creating the final model and making predictions
8. Save the model with the highest accuracy in the form of a pickle file.

