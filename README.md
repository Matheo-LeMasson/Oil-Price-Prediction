## Predicting Oil Price

# Overview
This project focuses on predicting the price of oil using machine learning techniques and exploring the factors that influence oil prices. While there are numerous existing ML projects predicting oil prices using only historical price and time features, this project takes a unique approach by constructing a custom dataset with 23 diverse parameters believed to impact oil prices. Additionally, feature selection methods are employed to gain insights into which parameters play a significant role in determining oil prices.

# Why is Predicting Oil Price Interesting
Understanding and predicting the price of oil has immense importance due to its widespread impact on various industries and on the global economy. Oil prices directly influence energy costs, transportation, inflation rates, and investment decisions. Accurate predictions can assist businesses, investors, policymakers, and researchers in making informed decisions, managing risks, and developing effective strategies to navigate the dynamic oil market.

# Custom Dataset and Feature Selection
In contrast to conventional approaches, this project curates a comprehensive dataset with 23 distinct parameters, carefully selected based on domain knowledge and hypotheses regarding their potential influence on oil prices. These parameters encompass economic indicators, geopolitical factors, supply-demand dynamics, and other relevant variables. By incorporating such a wide range of features, this project aims to capture a more holistic view of the factors impacting oil prices.
To identify the most influential features, feature selection techniques are employed. Various algorithms, such as correlation analysis, sequential feature selection and Boruta are utilized to evaluate the relevance of each parameter to the target variable. This feature selection process allows us to gain valuable insights into which factors have a significant impact on oil prices, providing a deeper understanding of the underlying dynamics.

# Project Structure and Usage
The project is organized into several main components:
Data Collection and Preparation: Describes the process of gathering and preprocessing the diverse parameters to construct the custom dataset.
Exploratory Data Analysis: Explores the dataset, visualizes relationships between variables, and provides insights into the initial exploration of the data.
Model Training and Evaluation: Implements machine learning models, such as regression algorithms, to predict oil prices. Evaluates the model performance using appropriate metrics and cross-validation techniques.
Feature Selection and Interpretation: Applies feature selection algorithms to identify the most important parameters influencing oil prices. Provides visualizations and explanations of the feature importance results.
Retraining the Model with the Top 5 Features: After identifying the most important parameters influencing oil prices through feature selection, we further refine our model by retraining it using only the top five features. By focusing on these key variables, we aim to improve the model's performance and potentially enhance its predictive accuracy.


Feel free to explore the project and adapt the code and techniques to your specific requirements. Contributions, suggestions, and feedback are greatly appreciated.

