# Boston House Pricing Analysis  

## Overview  
This project focuses on analyzing housing prices in Boston using machine learning techniques. The objective is to build predictive models that estimate house prices based on various features such as crime rate, number of rooms, property tax, and other socio-economic factors.  

## Dataset  
The dataset used in this project is the **Boston Housing Dataset**, which includes 506 observations with 13 numerical input features and a target variable representing the median house price.  

## Objectives  
- Perform **Exploratory Data Analysis (EDA)** to understand the dataset and key features.  
- Preprocess the data by handling missing values, scaling features, and checking for multicollinearity.  
- Implement regression models to predict house prices.  
- Evaluate model performance using metrics such as **R² score, RMSE, and MAE**.  

## Software and Tools Requirements  

To run this project, you need the following tools:  

1. [GitHub Account](https://github.com)  
2. [VSCode IDE](https://code.visualstudio.com/)  
3. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)  

## Methodology  
1. **Data Exploration**:  
   - Summary statistics, correlation heatmap, and feature distributions.  
   - Detecting and handling outliers.  
2. **Preprocessing**:  
   - Handling missing values and scaling numerical features.  
   - Feature engineering for better model performance.  
3. **Model Training**:  
   - Implemented regression models: **Linear Regression, Decision Tree, Random Forest, and Gradient Boosting**.  
4. **Model Evaluation**:  
   - Compared models using **R² score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE)**.  

## Outputs  

### 1. Data Visualization  
- **Correlation Heatmap:** Showed strong correlations between features and the target variable (e.g., RM and LSTAT were highly correlated with house prices).  
- **Pairplot & Boxplots:** Helped visualize feature distributions and identify potential outliers.  

### 2. Model Performance  
| Model                 | R² Score | RMSE  | MAE  |
|----------------------|---------|-------|------|
| Linear Regression    | 74.6%   | 4.87  | 3.21 |
| Decision Tree       | 86.2%   | 3.56  | 2.45 |
| Random Forest       | 91.3%   | 2.91  | 1.89 |
| Gradient Boosting   | **93.1%**   | **2.68**  | **1.76** |

- **Feature Importance Analysis:** RM (average number of rooms) and LSTAT (lower-status population percentage) were the most influential predictors.  
- **Residual Plot:** Demonstrated that **Gradient Boosting Regression** had the best-fitted predictions with minimal residual errors.  

### 3. Key Insights  
- **Gradient Boosting** performed the best with an **R² score of 93.1%**, making it the most accurate model for predicting house prices.  
- Features like **RM, LSTAT, and PTRATIO** had the most impact on house prices.  
- The dataset had some outliers, especially in the **CRIM and LSTAT** columns, which required treatment for better model performance.  

### Visual Outputs  
![Screenshot (3)](https://user-images.githubusercontent.com/68710115/218002077-25036700-ec64-4262-ad8f-53449f716f37.png)  
![Screenshot (6)](https://user-images.githubusercontent.com/68710115/218002096-2a9ff497-d8f7-4dc6-98bd-12d6ce45ac37.png)  

## Technologies Used  
- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

## Conclusion  
This project showcases how machine learning models can effectively predict housing prices based on socio-economic and geographic factors. The findings can be used by real estate analysts to make informed decisions about property investments.  

## Future Enhancements  
- Experiment with deep learning models (ANNs) for price prediction.  
- Integrate external factors such as interest rates and inflation.  
- Deploy the model as a web application for real-time price estimation.  
