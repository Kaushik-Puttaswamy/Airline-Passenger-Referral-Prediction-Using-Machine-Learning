# ✈️ Airline Passenger Referral Prediction Using Machine Learning

## 📌 Introduction

This project aims to predict whether a passenger referred by an existing customer will book a flight, leveraging various features such as seat comfort, cabin service, travel class, food & beverage, entertainment service, and more.

We developed a **classification model** using machine learning techniques, allowing the model to learn from **historical passenger** and **booking data** to make accurate predictions for new cases. Airlines can utilize this model to **target marketing efforts** towards potential passengers likely to book flights based on referrals from existing customers.

## 🎯 Objective

The dataset comprises **airline reviews from 2016 to 2019** for major airlines worldwide, with multiple-choice and open-text responses collected in Spring 2019.

The primary objective is to **predict whether passengers will recommend the airline** to their friends based on various service factors.

## 🏗️ Project Architecture Diagram

Below is the architecture diagram outlining the core flow of the system:

![Project Architecture](https://github.com/Kaushik-Puttaswamy/Airline_Passenger_Referral_Prediction_Using_Machine_Learning/blob/main/Project%20Architecture.png)

## 📊 Data Description
The dataset contains 131,895 entries and the following columns:

The dataset contains 131,895 entries with the following key features:

•	**✈️ Airline:** Name of the airline

•	**⭐ Overall:** Overall rating given by the passenger

•	**📝 Author:** Name of the reviewer

•	**📅 Review Date:** Date of the review

•	**💬 Customer Review:** Text of the customer review

•	**🏢 Aircraft:** Type of aircraft

•	**👤 Traveller Type:** Type of traveler (solo, couple, family)

•	**🏷️ Cabin:** Class of travel (economy, business, etc.)

•	**🛫 Route:** Route of the flight

•	**📅 Date Flown:** Date of the flight

•	**🪑 Seat Comfort:** Rating for seat comfort

•	**🛎️ Cabin Service:** Rating for cabin service

•	**🍽️ Food & Beverage:** Rating for food and beverage service

•	**🎬 Entertainment:** Rating for entertainment service

•	**🏢 Ground Service:** Rating for ground service

•	**💰 Value for Money:** Rating for value for money

•	**👍 Recommended:** Whether the passenger recommended the airline

# 🔍 Data Analysis and Preprocessing

✔️ Handled **missing values** appropriately

✔️ Converted **data types** for model compatibility

✔️ Selected **relevant features** for prediction

✔️ Conducted **exploratory data analysis (EDA)** to understand feature relationships


# 📈 Key Insights

•	🧑‍✈️ **Traveler Type: 37.22%** of passengers travel solo, followed by couples and families

•	🏷️ **Travel Class: 78.44%** of passengers opt for **economy class**

•	🛎️ **Cabin Service: 50%** of passengers rated it **4.0 or 5.0**, positively impacting airline reputation

•	🎬 **Entertainment: 30%** of passengers were dissatisfied, rating it **1.0**

•	🪑 **Seat Comfort: 38%** rated it **4.0 or 5.0**, indicating comfort significantly impacts satisfaction

•	⭐ **Overall Rating: 42%** of passengers rated below **3.0**, highlighting service improvement areas

# 🤖 Model Development

We implemented and evaluated multiple **classification models**:

1.	📊 **Logistic Regression**

2.	**🌳 Decision Tree**

3.	**🌲 Random Forest**

4.	**🔍 K-Nearest Neighbour (KNN)**

5.	**📏 Support Vector Machine (SVM)**

6.	**📉 Naïve Bayes**

# 🎯 Model Evaluation

✔️ Performed hyperparameter tuning using Grid Search CV to optimize model performance

✔️ Logistic Regression achieved the best performance overall

✔️ Support Vector Machine (SVM) demonstrated the highest accuracy by a narrow margin

# 🔑 Feature Importance

The **most influential features** in predicting recommendations were:
	
 1.	⭐ **Overall Rating**
	
 2.	💰 **Value for Money**

# 🔧 Recommendations

To enhance customer satisfaction and business performance, airlines should concentrate on improving:

1.	🛎️ **Cabin Service**
	
2.	🏢 **Ground Service**
	
3.	🍽️ **Food & Beverage**
	
4.	🎬 **Entertainment**
	
5.	🪑 **Seat Comfort**


# ✅ Conclusion

The project successfully developed a **predictive model** achieving **over 90% accuracy**. By focusing on essential service areas, airlines can boost **customer satisfaction and referral rates**, leading to business growth.

# 🚀 Future Work

🔹 Enhance models with **ensemble methods** for better accuracy

🔹 Incorporate **demographic data** for more personalized predictions

🔹 Continuously update models with **new data** to maintain accuracy & relevance


