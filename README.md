#Housing Price Prediction
## Overview
This project involves building a machine learning model to predict house prices based on a diverse set of property features. Using a dataset of housing information, this analysis explores the key factors influencing home values, from basic physical attributes like area and number of rooms to amenities such as air conditioning and proximity to a main road.

## Dataset
The dataset for this project, `[housing.csv]`, contains five hundred plus records of real estate data. The columns are price, area, bedrooms, bathrooms , stories , mainroad, guestroom,prefarea , furnishing status and airconditioning                                                         ## Project Objectives                                                                                                                                                                                                              

The main goals of this project are:    
To conduct Exploratory Data Analysis (EDA) to understand the distribution, correlations, and relationships within the dataset.

To perform Data Preprocessing, including handling categorical variables using techniques like one-hot encoding, and preparing the dataset for model training.  
To build and train a machine learning model, such as  Linear Regression, Ridge, or Gradient Boosting to predict house prices.

To evaluate the model's performance using appropriate metric.   

To identify the most influential features affecting house prices based on the model's coefficients or feature importances. 

Exploratory Data Analysis (EDA) During the EDA phase,    

several visualizations were created to understand the underlying data patterns and relationships between variables.

Key Visualizations   

Density vs. Area: A density plot was used to visualize the distribution of house area. This revealed  that most houses are concentrated within a specific size range, with a few properties representing the extreme ends of the area spectrum 

 

Count vs. Bedrooms, Bathrooms, and Stories: Count plots were generated for categorical variables such as bedrooms, bathrooms, and stories to show the frequency of each category in the dataset. 



Area vs. Price (Scatter Plot): A scatter plot was created to explore the relationship between area and price. This visualization showed a clear positive correlation, indicating that larger houses tend to have higher prices. The plot helped to identify the general trend and potential outliers. 



Area vs. Price (Line Chart): A line chart was used to provide an alternative view of the relationship between area and price, which is useful for visualizing the overall trend more smoothly.



Count Plots for Binary/Categorical Features:                                                                                                           Count plots were used to display the distribution of binary features like mainroad, hotwaterheating, airconditioning, etc., showing the frequency of each category.                                                                                                                            Count vs. Parking and Furnishing Status: These plots illustrated the distribution of properties based on the number of available parking spaces and their furnishing status  




Key Findings and Results
The exploratory analysis highlighted a strong positive correlation between area and price. Additionally, features like airconditioning and prefarea showed a significant impact on property values. The final model's performance on the test set indicated a reliable ability to predict house values based on these features.
