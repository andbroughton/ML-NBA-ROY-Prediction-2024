# ML-NBA-ROY-Prediction-2024

This repository contains the code and resources for a predictive model that forecasts the NBA Rookie of the Year winner based on historical data from the past 20 years. 

# Results
Below the predicted top 10 vote-getters for the Rookie of the Year Award for the 2023-2024 NBA Season (using statistics through 1/6/2024)
![image](https://github.com/andbroughton/ML-NBA-ROY-Prediction-2024/assets/134515627/b1a54fe4-84d1-490a-a8f1-475184bd01e0)

# Process
Used the Jupyter Lab IDE
Data Acquisition: Utilized Python, Selenium WebDriver, BeautifulSoup, and pandas for web scraping NBA data. Downloaded files using Selenium and Requests library, parsed them with Beautiful Soup, and loaded them into Pandas DataFrames.
Data Cleaning and Integration: Merged and cleaned 20 years of rookie data using using pandas. Explored the data using Matplotlib for insights.
Machine Learning: Prepared the data for machine learning, implemented a Ridge Regression model using scikit-learn, and defined an error metric for evaluation. Backtested the model across the dataset, iterating on predictors for refinement.
Finally, used the newly trained model on the current season's data.
