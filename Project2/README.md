Project 2 - Ames Housing Data and Kaggle Challenge¶

Problem Statement

Ames is a city in Story County, Iowa, United States, located approximately 30 miles (48 km) north of Des Moines in central Iowa. It is best known as the home of Iowa State University (ISU), with leading agriculture, design, engineering, and veterinary medicine colleges.In 2020, Ames had a population of 66,772 .

This project analyses the housing dataset of Ames in Iowa, USA. The dataset is obtained from KaggleLink. People often invest in remodelling to increase value of the house and don't get much return on investment when selling the house. Likewise, people looking to buy houses want to get the best house within their budget.

I will use the housing data collected from Kaggle to build a Linear Regression model that best predicts sale prices for properties located in Ames.

Executive Summary

This dataset provides 80 features (of nominal, discrete, and ordinal types) to describe properties in Ames, Iowa that were sold between the years 2006-2010. During the first step in the analysis - data cleaning, missing values were fixed, incorrect data types were fixed, and any unsual values were also investigated and fixed. Once the data was cleaned, Exploratory Data Analysis (EDA) was conducted to explore the relationship between Sale Price and each feature in the model. For numeric features, the linear relationship was examined using a heatmap and correlation coefficients. For categorical data, bar plots were created to visualize the mean Sale Price across categories. Following EDA, features were engineered to reduce dimensionality of the data and to account for the patterns and clusters that emerged during EDA. Categorical variables of were encoded. During modeling, three models were built: a Linear Regression, Ridge Regression and Lasso Regression. The models were compared based on R2 score, and the highest scoring model was selected for further evaluation using RMSE and residuals plots. Interpretations and recommendations were made based off of the best-performing model.

Conclusions and Recommendations

Based on the findings,

Square feet area, property age, Overall conditions and location are the most important determinant factors of Saleprice.

Best locations are - Northridge Heights, Stone Brook and Northridge.

People looking to sell should do it sooner rather than later.

To increase the value of a home:

Renovate the kitchen
Remodel the interior and exterior finish
Add fireplace(if not present)
Renovate Garage
Renovate house if not in good condition



