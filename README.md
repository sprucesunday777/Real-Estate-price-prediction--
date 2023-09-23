# Real-Estate-price-prediction--

Real estate is a dynamic market with fluctuating prices influenced by various factors. The goal of this project is to build a predictive model that can help customers  determine the prices of houses in Nigeria based on specific features like location, title, and number of bedrooms, bathrooms and parking space.

Problem Statement
Predicting house prices in the current market has been a major challenge for Wazobia Real Estate Limited, and they are determined to provide accurate and competitive pricing for houses.

Aim and Objective
The objective of this project is to develop a powerful and accurate predictive model that can estimate house prices in Nigeria, and analyse various factors that impact house prices.

Data Access
The dataset used for this project was provided by DSN Network and Zindi Africa for the DSN-MICROSOFT-HACKATHON and can be accessed on the Zindi platform: Wazobia Real Estate Hackathon Data and was given to me by Pharm Chinelo Cynthia Ezenwafor

Dataset Description
This dataset contains valuable information on various features related to houses, including the location, number of bathrooms, bedrooms, parking spaces, property types, and their corresponding prices.
Data Preparation
The steps taken in the preparation of this data include:

Exploratory Data Analysis
Various visualisation charts were used to understand the pattern and behaviour of the dataset.
Data Cleaning
Missing values in the 'title' and 'location' columns were imputated with the Forward filling function 
Missing values in the 'bedroom', 'bathroom', and 'parking_space' columns were imputated with their respective means. 

Feature Engineering

category_encoders was applied to  'loc' and 'title' columns to transform words to numbers.
Model Building
Various regression algorithms, including lazypredict, Linear Regression was used. 
Cross validation was later applied to obtain a better root mean square. 

Model Evaluation
The models were evaluated using Root Mean Squared Error (RMSE) to assess their predictive performance.

Model Selection
The cross validated linear regressor model with a mean score of 0.269 was chosen as the model of choice for the prediction because it had the least RMSE score and shows a strong generalisation ability as it performed well on multiple folds of data hence can adapt better to unseen data.

Feature Importance Analysis
Feature importance analysis was conducted on the Cross validated linear regressor model to identify which features have the most significant impact on house prices. This analysis provides valuable insights into the factors that drive property prices in Nigeria. The top three features that have significant impact on house prices are The bedroom, bathroom etc

Conclusion
This data science project successfully predicts house prices for the real estate company based on essential features like location, title, bedroom, bathroom etc and the top-performing model is the Cross-validated linear regressor.


Acknowledgment
I acknowledge the real estate company in Nigeria for providing the dataset and Pharm Chinelo Cynthia Ezenwafor for giving me access to the dataset and edikan for helping me with the data cleaning 

Read more on my medium page;https://medium.com/@nsisongsunday7778/real-estate-house-prices-prediction-in-nigeria-ba8cdc2b18f3
 
