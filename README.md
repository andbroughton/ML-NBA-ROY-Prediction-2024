# ML-NBA-ROY-Prediction-2024

This repository contains the code and resources for a predictive model that forecasts the NBA Rookie of the Year winner based on historical data from the past 20 years. 

# Results
Shown below are the predicted top 10 vote-getters for the Rookie of the Year Award for the 2023-2024 NBA Season (using statistics through 1/6/2024)

![image](https://github.com/andbroughton/ML-NBA-ROY-Prediction-2024/assets/134515627/b1a54fe4-84d1-490a-a8f1-475184bd01e0)

# Findings
Backtesting across the data set, the model was found to be around 75% accurate at predicting the top 5 finishers for the ROY race in a given year, with most players predicted ranks being very close to their actual ranks.

The model was trained using data from 2003-2022, and tested on the data from the 2023 season to predict who the ROY was. Shown below are the results.

![image](https://github.com/andbroughton/ML-NBA-ROY-Prediction-2024/assets/134515627/c35d15e4-083f-466b-8c3f-96cd98bdf41d)

As can be seen, 4/5 actual top 5 finishers were correctly placed in the top 5, and other member of the actual top 5, Keegan Murray, finished just outside of the top 5, at 7th.

Consistent with expectations, the model predicts Victor Wembanyama and Chet Holmgren as the top contenders for the 1st and 2nd positions in the NBA Rookie of the Year race. Notably, Jaime Jaquez Jr. is projected to be ranked 7th, contrasting with many analysts who consider him the third-best candidate for the award. Additionally, the model reveals intriguing insights, suggesting a more dispersed distribution of votes compared to the concentrated patterns observed in real-life voting outcomes.

# Process
Used the Jupyter Lab IDE

Data Acquisition: Utilized Python, Selenium WebDriver, BeautifulSoup, and pandas for web scraping NBA data. Downloaded files using Selenium and the Python Requests library, parsed them with Beautiful Soup, and loaded them into pandas DataFrames.

Data Cleaning and Integration: Merged and cleaned 20 years of rookie data (2003-2023) using using pandas. Explored the data using Matplotlib for insights.

Machine Learning: Prepared the data for machine learning, implemented a Ridge Regression model using scikit-learn, and defined an error metric for evaluation. Backtested the model across the dataset, iterating on predictors for refinement.

Finally, used the newly trained model on the current season's data.

This project was inspired by Dataquest's project predicting the NBA MVP.
