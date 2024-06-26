# BoomBikes
This project aims to develop a multiple linear regression model to predict the demand for shared bikes for BoomBikes, a US-based bike-sharing provider. The company seeks to understand and prepare for post-pandemic demand, with the goal of accelerating revenue and gaining a competitive edge in the market. The primary objectives are to identify significant variables that influence bike-sharing demand and to determine how well these variables describe the demand.
The project will focus on model development, using 'cnt' (total bike rentals) as the target variable. Once the model is built, it will be evaluated using the R-squared score on a test set. The final step will involve interpreting the results to identify the most significant predictors of bike demand. Based on these insights, business recommendations will be formulated to help BoomBikes adjust their strategy, meet customer expectations, and understand demand dynamics in potential new markets.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
BoomBikes, a US bike-sharing company, has experienced revenue declines due to the COVID-19 pandemic. They offer a service where people can rent bikes short-term from computer-controlled docks. The company wants to prepare for post-pandemic recovery and growth.
BoomBikes needs to understand and predict the factors influencing bike-sharing demand in the post-pandemic American market. This will help them develop a strategic business plan to boost revenues, meet customer needs effectively, and gain a competitive advantage once the economy recovers.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Temprature: As the temprature increases, there is an increase in bike rentals as well. For every unit of increase in temprature, there is almost an increase of 1080 rentals.
- Seasonality: Summer and winter positively impact bike rentals, with winter having a slightly larger effect (+1187.45) than summer (+903.00).
- Monthly trends: August, September, and October positively affect rentals, with September having the strongest impact (+1030.20).
- Day of week: Tuesdays negatively impact rentals (-429.98) compared to other days.
- Weather conditions: Both misty and rainy weather negatively affect rentals, with rain having a much stronger negative impact (-2702.80) than misty conditions (-697.71).
- Year: Being in 2019 has a strong positive effect on rentals (+1980.89).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python 3.11.5 
- pandas 2.2.2
- numpy 1.26.4
- matplotlib 3.8.4
- seaborn 0.13.2
- scikit-learn 1.5.0
- statsmodels 0.14.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project done as part of ML course in Upgrad


## Contact
Created by [@varsim91] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->