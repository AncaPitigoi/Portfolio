# Anca Pitigoi - Portfolio
# Table of Contents
* [About me](#about-me)
* [Projects](#projects)
* [Education](#education)
* [Certificates](#certificates)
* [Contact](#contact)

## About me

Hello, I am Anca! I am currently a graduate student pursuing a Master's Degree in Analytics, concentrating on statistical modeling. I have always been passionate about statistics and data, 
and how certain aspects influence the world, the business and ultimately our actions. In my journey as a data analyst I hope to bring positive changes that can help organizations and society develop. 

During my studies, I have developed skills for identifying patterns and trends in complex datasets, using data mining and regression techniques.
I enjoy having walks early in the morning, reading and tending to my orchid collection in the spare time. I also like to expand my knowledge and skills, and solving challenges give me great satisfaction.

This repository displays past and current projects I am working on, showcasing my skills and progress in the Data Analytics field. 

# Projects
* Python
  * [KNN and Neural Networks: Digit Recognition](#Digit-Recognition-with-KNN-and-Neural-Networks)
  * [Predicting the Weather](#Predicting-the-Weather)
  * [Forecast the Car Insurance Risk Rating](#forecast-the-car-insurance-risk-rating)

* R
  * [Decision Tree: Mushrooms Selection](#mushrooms-selection)

* [Tableau Portfolio](https://public.tableau.com/app/profile/anca.pitigoi/vizzes)
  * [Boston Crime Analysis](#Boston-Crime-Analysis)
  * [AirBnB Occupancy in Seattle](#AirBnB-Occupancy-in-Seattle)
 
* SQL
  * [The Store Database](#The-Store-Database)

# Digit Recognition with KNN and Neural Networks
This project explores children’s handwriting data to assess the feasibility of using machine learning models to identify potential motor skill development concerns. By analyzing images of handwritten digits, the study aims to evaluate how accurately different models can recognize numbers drawn by students to ultimately identify students that need help. Two different methods were used: KNN and Neural Networks.

__Code__: [Digit Recognition with KNN and Neural Networks Code](https://github.com/AncaPitigoi/car-risk/blob/5d4a864e18ecec7822313e3527b734da03fcbd28/Forecast%20the%20Insurance%20Risk%20Rating.ipynb)

__Report__: [Digit Recognition with KNN and Neural Networks](https://github.com/AncaPitigoi/digit-recognition/blob/95f4ec2edba92d55e0fce98c995ffdfa294fd123/Pitigoi-Digit%20Recognition.pdf)

__Skills__: classification, KNN, neural networks, data validation, data visualization

__Results__: The CNN consistently outperformed KNN across all metrics, achieving 70% accuracy versus 65% for KNN, with similar improvements in precision (71% vs 65%) and recall (70% vs 65%). The confusion matrices revealed that while both models struggled with 5 and 9 digits, the CNN still classified them more accurately overall. However, the CNN model performed a little bit worse than KNN on digit 9, but improved classification rates for all the other digits. While the current accuracy of 70% may seem modest compared to cutting-edge digit recognition systems, this limitation stems from the sparse and incomplete pixel data rather than the model architecture itself.


# Predicting the Weather
This project investigates historical weather data to evaluate the effectiveness of rain prediction models. By analyzing meteorological characteristics such as temperature, humidity, wind direction, and atmospheric pressure, the study aims to identify the most influential features contributing to accurate rainfall prediction. Three different methods were used: Logistic Regression, Decision Tree, and Gradient Boosting.

__Code__: [Predicting the Weather Code](https://github.com/AncaPitigoi/weather-prediction/blob/e12e2062aae18aba010979bcf8711c02554e5932/Pitigoi-Weather%20Forecast.ipynb)

__Report__: [Predicting the Weather](https://github.com/AncaPitigoi/weather-prediction/blob/e12e2062aae18aba010979bcf8711c02554e5932/Pitigoi-Weather%20Forecast.pdf)

__Skills__: classification, gradient boosting, decision tree, logistic regression, benchmark results data validation, feature engineering, data visualization

__Results__: All three models (Logistic regression, Decision Tree, and Gradient Boosting) performed similarly well, achieving 86-87% accuracy with strong recall rates (93-95%) for detecting rain. Moreover, the speed of the models was the same for this dataset. However, all models exhibit a systematic bias toward overpredicting rain. They correctly identify actual rainy days but struggle with dry days, falsely predicting rain 34-40% of the time it does not actually rain. Rainfall prediction in this dataset is strongly influenced by moisture-related variables, like cloud cover percentage, dew point, relative humidity, and sunshine hours. These features consistently emerged as significant predictors across the first two models, reflecting real-world atmospheric conditions: higher cloud cover and dew point increase the chance of rain, while longer sunshine hours reduce it. Interestingly, traditional variables like atmospheric pressure and wind patterns had minimal predictive power.

For real-world deployment, the decision tree model can support weather-responsive decision-making such as scheduling agricultural activities, issuing rain alerts, or managing drainage systems. It is recommended to add more dry days to reduce bias, and integrate the model with near real-time data feeds. Given the high recall, the model is especially valuable in risk-averse applications, where missing a rainy day would be more costly than predicting one that does not occur.


# Forecast the Car Insurance Risk Rating
This project attempts to forecast the vehicle risk rating for an insurance company. Different data mining applications will be used and compared to see which one is best fit for this dataset. Data validation, cleaning, and exploratory analysis was performed. Moreover, the Jupyter Notebook will be using functions to facilitate coding and keep the notebook clean. Finally, three different classification methods were used: SVM with different kernels, Decision Tree, and Random Forest.

__Code/Report__: [Forecast the Car Insurance Risk Rating](https://github.com/AncaPitigoi/car-risk/blob/5d4a864e18ecec7822313e3527b734da03fcbd28/Forecast%20the%20Insurance%20Risk%20Rating.ipynb)

__Skills__: classification, decision tree, support vector machines, random forest, hyperparameter tuning, PCA, data validation, data visualization, function creation

__Results__: The SVM with RBF kernel achieved the best accuracy of 67.68%, demonstrating that non-linear relationships between features and risk ratings are important. The Random Forest model, which aggregates the predictions of multiple decision trees, achieved a close accuracy of 67.78%. Despite this, further hyperparameter tuning and cross-validation could still enhance its performance. Moreover, based on the analysis, the categorical features have shown little importance in the feature importance plots and haven't significantly contributed to improving the accuracy of the models, it could be worth considering their removal to simplify the model, and potentially improve generalization by reducing noise.


# Mushrooms Selection
In order to find which mushrooms are safe to eat, the Decision Tree classification method is used. The dataset was first cleaned, exploratory data analysis was performed, the tree was built on the training dataset, optimization was applied, and finally the validation of the classification model results was achieved on the test set.

__Report__ [Decision Tree - Mushrooms Selection](https://ancapitigoi.github.io/mushrooms-selection/)

__Code__: [Decision Tree - Mushrooms Selection Code](https://github.com/AncaPitigoi/mushrooms-selection/blob/main/Decision%20Tree%20-%20Mushroom.R)

__Skills__: data cleaning, data visualization, classification, decision tree

__Results__: The most important features to look for when mushroom foraging are odor, spore print color, gill size, population, and habitat. The model is exceptional, but achieving perfect classification accuracy and precision is not common in practice, especially in real-world datasets with inherent complexities and noise.


# Boston Crime Analysis
Two dashboards were created to inform the targeted audience (the mayor of Boston and all city council members) of the shootings occurring in Boston. All the elements were carefully placed to avoid cluttering and focus the attention where it is needed. One dashboard answers questions related to where the shootings occur and a second dashboard shows when the shootings are more predominant.

__Dashboards__: [Where and What Type of Offense](https://public.tableau.com/app/profile/anca.pitigoi/viz/BostonCrimeAnalysis2015-2024/Where), 
[When do the shootings occur?](https://public.tableau.com/app/profile/anca.pitigoi/viz/BostonCrimeAnalysis222015-2024/When)

__Skills__: Tableau, data visualization, creating map charts, dashboards, and plots

__Results__: It is noticed that most shootings happen in Roxbury, Mattapan and Dorchester, and a few spots are in Jamaica Plain and South Boston. The safest district from this perspective is Charlestown. Most of the shootings happened when the officer went to investigate a property, so more caution is desired. A significant spike where 876 shootings occurred in 2021 is seen, marking a substantial increase from 2020. This rise is particularly surprising given that the onset of the Covid-19 pandemic in 2020 was expected to keep people indoors. Lastly, most shootings happen on the weekends, between 9 PM and 3 AM, as expected, and before the winter holidays (some causes can include holiday-related stress and the transition from warm to cold weather).


# AirBnB Occupancy in Seattle
This dashboard presents different types of plots for the Seattle AirBnB rentals in 2016. Firstly three tables were joined using the ID of the listings, then the data was filtered to include only the relevant information for the project. The dashboard contains two bar charts, a map, a table, and a line plot.

Dashboard: [AirBnB Occupancy in Seattle](https://public.tableau.com/app/profile/anca.pitigoi/viz/AirBnBExercise_17123393960360/Dashboard1)

__Skills__: Tableau, joining multiple tables, data visualization, creating map charts, dashboards, and plots

__Results__: Renting an apartment in certain zip codes can be more expensive on average because of the proximity to certain sightseeings. Moreover, the revenue is slowly increasing from February, with a peak near the winter holidays as expected. This information is helpful for any investor that wants to rent out an apartment and have the largest return on investment. It also makes sense to buy a larger apartement because the average price increases with size, and the competition is more scarcer.

# The Store Database
The Store Database project presents SQL querying skills using three data tables. Data cleaning, data validation, and exploratory data analysis will be performed using diverse functions such as joining tables, grouping by certain criteria, and performing calculations.

__Report__ [The Store Database: Report](https://github.com/AncaPitigoi/Store-Database/blob/48574e2e3aa35a448ef9571dd787f78ba5fe05c9/SQL%20-%20Store%20Database.pdf)

__Code__: [The Store Database: Code](https://github.com/AncaPitigoi/Store-Database/blob/48574e2e3aa35a448ef9571dd787f78ba5fe05c9/store-inventory-code.sql)

__Skills__: joining, grouping, filtering data, data validation, SQL, indexing, databse schema

__Results__: Based on the analysis, Ben Franklin store achieved the highest revenue across all years, rice paper is the most sold product in terms of quantity, and Sultanas brings the highest revenue across all stores. In terms of profitability, corn brooms and Sultanas stand out with the highest profit margins, whereas hazelnut cream coffee yields the lowest margins. The sales trends over the years show a noticeable decline in December each year. Also, the best year in terms of revenue was 2018, toping $8.4 million dollars. The highest transaction ever recorded was in 2019, where a customer bought 411 items in one sale.


# Education
Northeastern University, Boston, USA: Master's Degree in Analytics, Statistical Modeling Concentration, 2023 - 2025

Bucharest University of Economic Studies, Bucharest, Romania: Bachelor's Degree in Business Administration, Tourism Concentration, 2013 - 2016

# Certificates
[Google Data Analytics Specialization](https://www.coursera.org/account/accomplishments/specialization/certificate/DDJETLMG2H3A) Coursera, 2022

# Contact
[LinkedIn](https://www.linkedin.com/in/ancapitigoi/)
