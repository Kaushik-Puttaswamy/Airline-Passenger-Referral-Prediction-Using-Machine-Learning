# Airline_Passenger_Referral_Prediction_Using_Machine_Learning

## Introduction
This project aims to predict whether a passenger referred by an existing customer will book a flight, leveraging various features such as seat comfort, cabin service, travel class, food & beverage, entertainment service, and more. We developed a classification model using machine learning techniques, allowing the model to learn from historical passenger and booking data to make accurate predictions for new cases. Airlines can utilize this model to target marketing efforts towards potential passengers likely to book flights based on referrals from existing customers.

## Objective
The dataset comprises airline reviews from 2016 to 2019 for major airlines worldwide, with multiple-choice and open-text responses collected in Spring 2019. The primary objective is to predict whether passengers will recommend the airline to their friends.

## Project Architecture Diagram
Below is the architecture diagram outlining the core flow of the system:
![Project Architecture](https://github.com/Kaushik-Puttaswamy/Airline_Passenger_Referral_Prediction_Using_Machine_Learning/blob/main/Project%20Architecture.png)

## Data Description
The dataset contains 131,895 entries and the following columns:

1. Airline: Name of the airline.
2. Overall: Overall rating given by the passenger.
3. Author: Name of the reviewer.
4. Review Date: Date of the review.
5. Customer Review: Text of the customer review.
6. Aircraft: Type of aircraft.
7. Traveller Type: Type of traveler (solo, couple, family).
8. Cabin: Class of travel (economy, business, etc.).
9. Route: Route of the flight.
10. Date Flown: Date of the flight.
11. Seat Comfort: Rating for seat comfort.
12. Cabin Service: Rating for cabin service.
13. Food & Beverage: Rating for food and beverage service.
14. Entertainment: Rating for entertainment service.
15. Ground Service: Rating for ground service.
16. Value for Money: Rating for value for money.
17. Recommended: Whether the passenger recommended the airline.

# Data Analysis and Preprocessing
• Handled missing values appropriately.

• Converted data types as necessary for model compatibility.

• Selected features based on their relevance to the prediction task.

• Conducted exploratory data analysis (EDA) to understand the distribution and relationships of features.

# Key Insights
1. Traveler Type: 37.22% of passengers travel solo, with couples and families following.
2. Travel Class: 78.44% of passengers opt for economy class.
3. Cabin Service: 50% of passengers rated cabin service as 4.0 or 5.0, which positively impacts the airline's reputation.
4. Entertainment Service: 30% of passengers were dissatisfied with entertainment, giving it a rating of 1.0.
5. Seat Comfort: 38% rated seat comfort as 4.0 or 5.0, indicating that inadequate seat comfort negatively affects overall satisfaction.
6. Overall Rating: 42% of passengers provided an overall rating below 3.0, indicating significant room for improvement in airline services.

# Model Development
We developed and evaluated various classification models:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbour
5. Support Vector Machine
6. Naive Bayes

# Model Evaluation

• Performed hyperparameter tuning using Grid Search CV to optimize model performance and mitigate overfitting.

• Evaluation metrics indicated that the Logistic Regression model achieved the best performance overall.

• The Support Vector Machine demonstrated the highest accuracy rate by a narrow margin.

# Feature Importance
The most influential features predicting whether a passenger would recommend an airline include:
1. Overall Rating
2. Value for Money

# Recommendations
To enhance customer satisfaction and business performance, airlines should concentrate on improving:

1. Cabin Service
2. Ground Service
3. Food & Beverage
4. Entertainment
5. Seat Comfort

# Conclusion
The project successfully developed a predictive model achieving over 90% accuracy. By focusing on essential service areas, airlines can boost customer satisfaction and referral rates, contributing to business growth.

# Future Work
• Further refine models using advanced techniques, such as ensemble methods.

• Incorporate additional features, such as demographic data, for more personalized predictions.

• Continuously evaluate and update models with new data to maintain accuracy and relevance.


