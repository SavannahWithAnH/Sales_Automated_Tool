# BigMart Sales Data Neural Network
  
## Overview

This project focuses on leveraging regression analytics to predict future sales for a diverse range of products across various store locations. The sales data, collected from BigMart in the year 2013, serves as the foundation for this predictive analysis. The primary objective is to utilize historical sales data, product attributes, and location-related factors to build a robust regression model that can accurately forecast sales in the future.

**Benefits of Sales Prediction:**
Predicting future sales has significant benefits for both businesses and consumers. For BigMart, accurate sales predictions enable strategic inventory management, optimizing stock levels to prevent overstocking or stockouts. This, in turn, enhances operational efficiency and reduces carrying costs. Additionally, sales predictions allow the identification of high-demand products and locations, aiding in targeted marketing campaigns and improved resource allocation. For consumers, accurate sales predictions can lead to more consistent product availability and potentially lower prices due to optimized inventory management.

As this project encompasses contributions from diverse aspects such as data preprocessing, feature engineering, regression modeling, and location-based analysis, it showcases the collaborative efforts of contributors with varied expertise, ultimately culminating in a predictive model that can drive informed decision-making for BigMart.

Please click [here](https://docs.google.com/presentation/d/1MLGNz3lZow-65TH0pca2mxmcsVfNuM0Paq-pxnvl1vI/edit#slide=id.g278fa82c89e_0_50) to view our findings presentation.  

## Datasets
Click [here](https://www.kaggle.com/code/hiralmshah/bigmart-sales-prediction/notebook) to view one of our primary datasets!  

# Contributors & Responsibilities
- Alex Kopp
- Andrew Skorupa
- Savannah Porter
- Mohamed Abou elkhier

  ## Alex

- **File Name:** Sales_predict_rf.ipynb
- **Methods:** RandomForestRegressor, train_test_split, StandardScaler, tensorflow_decision_forests, mean_squared_error
- **Performance:** The model's R-squared value of 0.586 showcases reasonable performance on the dataset, indicating its ability to capture sales patterns with a certain degree of accuracy.

## Savannah

- **File Name:** RF3.ipynb
- **Methods:** RandomForestRegressor, train_test_split, StandardScaler, RandomizedSearchCV
- **Performance:** RF3 achieves an R-squared value of 0.6080, indicating improved predictive accuracy compared to RandomForest's default settings.

## Mohamed

- **File Name:** GBR.IPYNB
- **Methods:** GradientBoostingRegressor, MinMax, KFold, hyperparameter tuning with nested loops
- **Performance:** The model achieves an R-squared value of around 0.705, indicating decent-to-good fit. Such performance is typically acceptable for real-world scenarios, showcasing the model's ability to capture meaningful data patterns.

## Andrew

- **File Name:** Exploratory_Analysis.ipynb
- **Methods:** train_test_split, StandardScaler, mean_squared_error, ensemble.GradientBoostingRegressor
- **Performance:** Evaluated by Mean Squared Error (MSE), the model's calculated MSE of approximately 0.0013 signifies accurate predictions aligned with actual sales. The accompanying deviance plot highlights its effective error minimization through boosting iterations.

 ## Mohamed

- **File Name:** XGBR_final_results.ipynb
- **Methods:** train_test_split, XGBRegressor, StandardScaler, SimpleImputer, sklearn.metrics
- **Performance:** The model achieved an R-squared value of approximately 0.82, indicating good performance for sale predictions. This level of performance is attributed to the model's ability to capture underlying sales patterns while considering real-world variability and noise.

## Alex

- **File Name:** Sales_predict_product.ipynb
- **Methods:** train_test_split, StandardScaler, LabelEncoder, XGBRegressor, sklearn.metrics
- **Performance:** The model achieved an R-squared value of about 0.543, suggesting moderate predictive accuracy. While the model captures a significant portion of sales data patterns, there's potential for improvement to enhance its predictive power.




Item_Identifier: Unique product ID

Item_Weight: Weight of product

Item_Fat_Content: Whether the product is low fat or not

Item_Visibility: The % of total display area of all products in a store allocated to the particular product

Item_Type: The category to which the product belongs

Item_MRP: Maximum Retail Price (list price) of the product

Outlet_Identifier: Unique store ID

Outlet_Establishment_Year: The year in which store was established

Outlet_Size: The size of the store in terms of ground area covered

Outlet_Location_Type: The type of city in which the store is located

Outlet_Type: Whether the outlet is just a grocery store or some sort of supermarket

Item_Outlet_Sales: Sales of the product in the particulat store. This is the outcome variable to be predicted.
## Project Deliverables
Our project will provide analysis of the following areas:
- Accurate model for predicting 2014 Sales of product by product and location
- Provide comparative data for projectied sales across locations
- Provide aggregate for total sales predicted in 2014.


# Data collection, cleaning, modeling, and visualization tools
- SQL for database and table setup, data validation, exploration, and analysis. we divided to 3 parts
    - PART 1: Datebase and table setup
    - PART 2: Data validation and exploration
    - PART 3: Model Creation
    - PART 4: Model Training
    - PART 5: Model Testing
    - PART 6: Model Optimization
    - PART 7: Data Output Visualization and Analysis


    - Entity Relationship Diagram was also created using pgAdmin4 and saved as "ERD.png" to represent the visual of the relationship between our two data set 
    <img width="500" alt="image" src="./SQL/ERD.png">


# Part 1: Database and table setup
- SQL for database and table setup, data validation, exploration, and analysis. we divided to 3 parts
    - PART 1: Datebase and table setup
    - PART 2: Data validation and exploration
    - PART 3: Model Creation
    - PART 4: Model Training
    - PART 5: Model Testing
    - PART 6: Model Optimization
    - PART 7: Data Output Visualization and analysis

# Part 2: Data validation and exploration
- SQL for database and table setup, data validation, exploration, and analysis. we divided to 3 parts
    - PART 1: Datebase and table setup
    - PART 2: Data validation and exploration
    - PART 3: Model Creation
    - PART 4: Model Training
    - PART 5: Model Testing
    - PART 6: Model Optimization
    - PART 7: Data Output Visualization and analysis

# Part 3: Model Creation
- SQL for database and table setup, data validation, exploration, and analysis. we divided to 3 parts
    - PART 1: Datebase and table setup
    - PART 2: Data validation and exploration
    - PART 3: Model Creation
    - PART 4: Model Training
    - PART 5: Model Testing
    - PART 6: Model Optimization
    - PART 7: Data Output Visualization and analysis

# Part 4: Model Training
- SQL for database and table setup, data validation, exploration, and analysis. we divided to 3 parts
    - PART 1: Datebase and table setup
    - PART 2: Data validation and exploration
    - PART 3: Model Creation
    - PART 4: Model Training
    - PART 5: Model Testing
    - PART 6: Model Optimization
    - PART 7: Data Output Visualization and analysis

# Part 5: Model Testing
- SQL for database and table setup, data validation, exploration, and analysis. we divided to 3 parts
    - PART 1: Datebase and table setup
    - PART 2: Data validation and exploration
    - PART 3: Model Creation
    - PART 4: Model Training
    - PART 5: Model Testing
    - PART 6: Model Optimization
    - PART 7: Data Output Visualization and analysis

# Part 6: Model Optimization
- SQL for database and table setup, data validation, exploration, and analysis. we divided to 3 parts
    - PART 1: Datebase and table setup
    - PART 2: Data validation and exploration
    - PART 3: Model Creation
    - PART 4: Model Training
    - PART 5: Model Testing
    - PART 6: Model Optimization
    - PART 7: Data Output Visualization and analysis

# Part 7: Data Output Visualization and Analysis
- SQL for database and table setup, data validation, exploration, and analysis. we divided to 3 parts
    - PART 1: Datebase and table setup
    - PART 2: Data validation and exploration
    - PART 3: Model Creation
    - PART 4: Model Training
    - PART 5: Model Testing
    - PART 6: Model Optimization
    - PART 7: Data Output Visualization and Analysis

# Data collection, cleaning, modeling, and visualization tools
- SQL for database and table setup, data validation, exploration, and analysis. we divided to 3 parts
    - PART 1: Datebase and table setup
    - PART 2: Data validation and exploration
    - PART 3: Model Creation
    - PART 4: Model Training
    - PART 5: Model Testing
    - PART 6: Model Optimization
    - PART 7: Data Output Visualization and analysis


- Python and panda to clean and convert csv files to json.



- Plotly for interactive bar and line graphs visualizing stock price changes over time. 

- Flask app using 'render_template' to serve up the dashboard and jsonify to pull in data files enabling dashboard. please check 'Memo' in our application.py for more info.


**Please visit our individual Github pages below**  
[Alex Kopp](https://github.com/alexkopp12)  
[Andrew Skorupa](https://github.com/AndyMSkor)  
[Savannah Porter](https://github.com/SavannahWithAnH)  
[Mohamed Abou elkhier](https://github.com/nabroo101)  
 
