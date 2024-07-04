## Capstone Project: Seoul Bike Sharing Demand
The main purpose of this project is to analyze weather data, date information, and the count of rented bikes per hour obtained from the bike sharing systems in Seoul to uncover the behaviors of rental bike users and predict rental bike demand. In this project, clustering techniques (K-prototypes algorithm) are employed to group data based on their similarity or closeness to each other to explore the patterns of rental behavior. Besides, four regression models, including Gradient Boosting Machine (GBM), CUBIST Model,  Multi Layer Perceptron (MLP), and Ridge Regression are developed to predict the rental bike demand. R-squared (R²), Mean Squared Error (MSE), and Mean Absolute Error (MAE) are used for evaluating the models. A comprehensive literature review has been conducted ([Link to the Literature Review](https://docs.google.com/document/d/1sqTORA32Se4JmtVdVK5740BeO6WkfOU1EqcC-7tXJQg/edit?usp=sharing))




- Each observation contains the number of bikes rented per hour , and the corresponding date and weather information.
- Data preprocessing was performed for clustering techniques (feature engineering, and feature selection), and the development of regression models (feature selection, encoding, and scaling)
- The K-prototypes algorithm from the Kmodes package was chosen to explore the usage patterns of rental bike due to its ability to handle both numerical and categorical data
- Data visualization was used to obtain deep insights into the characteristics of each cluster.
- Out of the four regression models, MLP has the strongest performance, with the highest R-squared (95%), and the lowest MSE (22390.3) and MAE (87.39).










### Content
- Data preparation
- Exploratory data analysis (EDA)
- Application of K-prototypes algorithm
- Application of Four regression models
- Code: ([Link](https://github.com/CheukH/Capstone-2024/blob/main/Revised_Capstone_Bike_Initial_Results_and_Code.ipynb))








The proposed dataset is from UC Irvine Machine Learning Repository. It has 8760 instances with below 14 features. ([Link to the dataset](https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand))
- Date – A specific date that the data was collected 
- Rented Bike count – Count of bikes rented at each hour 
- Hour – Hour of the day 
- Temperature- Temperature (in Celsius) at each hour 
- Humidity – Humidity (in %) at each hour 
- Wind speed – Wind speed (in m/s) at each hour 
- Visibility – Visibility (in 10m) at hour hour 
- Dew point temperature – Dew point temperature (in Celsius) at each hour 
- Solar radiation – Solar radiation (in MJ/m2) at each hour 
- Rainfall – Rainfall (in mm) at each hour 
- Snowfall – Snowfall (in cm) at each hour 
- Seasons – The season during which the data was collected (Winter/ Spring/ Summer/Autumn)
- Holiday – whether the day was a holiday (Holiday/No holiday) 
- Functional Day – whether the day was a functional day (Yes/ No) 

