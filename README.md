# Fligh Fare Prediction
Predicting flight fares is a crucial task in the airline industry and for travelers looking to plan their trips efficiently. The primary objective of this project is to develop a machine learning model that accurately predicts flight fares based on various influencing factors.
## Dataset Overview
The dataset used for this project is sourced from Kaggle [https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh/data].The dataset is divided into training and test files. The training dataset contains 10,000 rows and 11 columns
* Features of the Flight Fare Prediction Dataset
* Airline: The airline operating the flight.
* Date_of_Journey: The date on which the journey is scheduled.
* Source: The departure location of the flight.
* Destination: The arrival location of the flight.
* Route: The route taken by the flight, including any layovers.
* Dep_Time: The departure time of the flight.
* Arrival_Time: The arrival time of the flight.
* Duration: The total duration of the flight.
* Total_Stops: The number of stops or layovers during the flight.
* Additional_Info: Additional information about the flight, such as in-flight amenities or restrictions.
* Price: The fare price of the flight (target variable).
finaly we have to predict wheather the employee get promotion(binary classification)
## EDA
Perform exploratory data analysis (EDA) to understand the dataset. Create plots and graphs to visualize the relationships and connections between different features.
## Feature Engineering
* Feature Identification: Identifying and creating relevant features that impact flight prices, such as departure and arrival locations, dates, times, airlines, and class of service.
* Feature Encoding:use Label Encoding and get_dummies method
## Model creation
I have tested a total of four algorithms on the model to determine the most effective accuracy score
* Linear regression
* Random Forest
## Hyperparameter Tunning
I employed RandomizedSearchCV to fine-tune the hyperparameters of the algorithm that yielded the highest accuracy among the ones listed above

