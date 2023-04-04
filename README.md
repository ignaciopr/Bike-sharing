# Bike-sharing

This is an interactive, insightful, and complete report about the bike-sharing service in the city. Our aim is to provide the head of transportation services of the local government with a comprehensive analysis of the service, including a deep analysis of usage patterns and a predictive model to forecast bike usage on an hourly basis.

**Data Analysis**

We conducted a thorough data analysis of the bike-sharing service, focusing on ensuring data quality, plotting clear and meaningful figures, and generating extra features for prediction. We also discussed missing values and outliers and treated text and date features.

Our analysis revealed several interesting insights about the bike-sharing service, such as the most popular routes and peak hours when the service is most in demand. We identified the demographics of users and observed how weather conditions and special events affect the demand for the service.

**Machine Learning**

We chose the best model to solve the problem of predicting bike usage on an hourly basis, taking into account both linear and non-linear models. We split the data correctly to train and test our models and tuned model parameters with validation.

Our predictive model accurately predicted bike usage on an hourly basis and provided additional insights when plotted against actual bike usage. We conducted a deep analysis of the results and provided explanations about the decisions taken, including the chosen model, hyperparameter settings, and evaluation metrics employed.

Note: The predictions are for the last week of 2012.

**Conclusion**

Our report provides the head of transportation services with a comprehensive analysis of the bike-sharing service, including deep insights into usage patterns and a predictive model for forecasting bike usage on an hourly basis. Our analysis and model will help the transportation services team optimize bike provisioning, reduce costs, and provide a better service to citizens.

**Description of the dataset**
- `instant`: record index
- `dteday` : date
- `season` : season (1:springer, 2:summer, 3:fall, 4:winter)
- `yr` : year (0: 2011, 1:2012)
- `mnth` : month ( 1 to 12)
- `hr` : hour (0 to 23)
- `holiday` : weather day is holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
- `weekday` : day of the week
- `workingday` : if day is neither weekend nor holiday is 1, otherwise is 0.
+ `weathersit` : 
	- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
	- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
	- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
	- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- `temp` : Normalized temperature in Celsius. The values are divided to 41 (max)
- `atemp`: Normalized feeling temperature in Celsius. The values are divided to 50 (max)
- `hum`: Normalized humidity. The values are divided to 100 (max)
- `windspeed`: Normalized wind speed. The values are divided to 67 (max)
- `casual`: count of casual users
- `registered`: count of registered users
- `cnt`: count of total rental bikes including both casual and registered
