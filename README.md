Copyright (c) 2024 Brad Stafford

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


Key Findings:
1. Low Mileage: Vehicles with lower mileage are more desirable. The majority of vehicles have odometer readings less than 100,000 miles.
2. Good Condition: The condition of vehicles varies, with many being in 'good' or 'excellent' condition.
3. Popular Brands: The top car manufacturers include Ford, Chevrolet, Toyota, Honda, and Nissan.
4. Recent Model Years: A significant number of vehicles are from recent model years (2010 onwards).
5. Fuel Efficiency: Gasoline is the most common fuel type, followed by diesel and hybrid.
6. Vehicle History Report: Many vehicles have a clean title status, indicating no major issues.
7. Certified Pre-Owned: A portion of the vehicles are certified pre-owned, adding to their appeal.

Overview of the Dataset
Data Loading:

The dataset vehicles.csv is loaded into a pandas DataFrame named vehicles_data.
Data Inspection:

The first few rows of the dataset are displayed to get an initial look at the data.
Basic information about the dataset is printed, including the number of entries, column names, and data types.
Summary statistics of the dataset are shown to understand the distribution and central tendencies of the numerical columns.
Data Cleaning and Preparation:

Missing values are handled by dropping rows with missing data in key columns such as price, year, manufacturer, etc.
Data types of relevant columns are converted to ensure consistency.
Feature Engineering:

A new feature certified_pre_owned is created to indicate whether the vehicle has a clean title status.
Exploratory Data Analysis (EDA):

Several visualizations are generated to explore the key features that influence car prices:
Odometer Readings: Distribution of mileage.
Condition of the Cars: Count of cars in different conditions.
Top 10 Car Manufacturers: Count of cars from the most popular manufacturers.
Model Years: Distribution of car model years.
Fuel Types: Count of cars with different fuel types.
Title Status: Count of cars with different title statuses.
Certified Pre-Owned Status: Count of cars that are certified pre-owned.



Car Price Analysis
Objective: The goal of this analysis is to understand the factors that influence the price of a used car. Based on the insights obtained, we aim to provide clear recommendations to a used car dealership on what consumers value in a used car.

Project Structure
Introduction:

Overview of the analysis objective and its significance for a used car dealership.
Import Libraries:

Importing essential libraries such as numpy, pandas, matplotlib, seaborn, and plotly for data analysis and visualization.
Data Loading:

Loading the dataset vehicles.csv into a pandas DataFrame.
Data Exploration:

Initial exploration to understand the structure and contents of the dataset.
Displaying the first few rows and summary statistics of the dataset.
Data Cleaning and Preparation:

Handling missing data and data preprocessing steps to prepare the dataset for analysis.
Exploratory Data Analysis (EDA):

Generating various visualizations (e.g., histograms, scatter plots) to explore the relationships between different features and the price of used cars.
Modeling:

Implementing multiple regression models (Ridge, Lasso, and ElasticNet) to predict car prices.
Splitting the data into training and testing sets.
Evaluating model performance using metrics such as Mean Squared Error (MSE).
Visualizing Model Predictions:

Plotting the actual versus predicted values for each regression model to assess their performance.
Findings and Recommendations:

Summarizing key insights from the data analysis and modeling.
Providing recommendations to the used car dealership on factors that influence car prices and what consumers value in a used car.
Key Insights
Factors Influencing Car Prices:
Vehicle age, mileage, manufacturer, model, condition, fuel type, transmission type, and color are some of the factors that significantly impact the price of a used car.
Consumer Preferences:
Consumers tend to value newer models, lower mileage, and well-maintained cars.
Certain brands and models may have higher resale value due to their reputation for reliability.
Recommendations
Based on the analysis, the following recommendations are made to the used car dealership:

Inventory Selection:

Focus on acquiring newer models with lower mileage and in good condition.
Prioritize popular brands and models that have a higher resale value.
Pricing Strategy:

Use the insights from the regression models to set competitive prices that reflect the value consumers place on different car features.
Marketing:

Highlight the key features that consumers value, such as low mileage, good condition, and popular models, in marketing materials and sales pitches.
Conclusion
This analysis provides a comprehensive understanding of the factors influencing used car prices and offers actionable recommendations for a used car dealership. By leveraging these insights, the dealership can better meet consumer preferences and optimize their pricing strategy.

