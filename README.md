# Boston House Pricing Prediction

## Project Overview
This project analyzes the Boston housing dataset to predict house prices using various statistical and machine learning techniques. The dataset consists of 506 samples with 14 attributes related to housing features, neighborhood characteristics, and economic factors.

## Dataset Description
The dataset contains the following features:
- **CRIM**: Per capita crime rate by town
- **ZN**: Proportion of residential land zoned for large lots
- **INDUS**: Proportion of non-retail business acres per town
- **CHAS**: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- **NOX**: Nitrogen oxide concentration (parts per 10 million)
- **RM**: Average number of rooms per dwelling
- **AGE**: Proportion of owner-occupied units built before 1940
- **DIS**: Weighted distances to employment centers
- **RAD**: Accessibility to radial highways
- **TAX**: Property tax rate per $10,000
- **PTRATIO**: Pupil-teacher ratio by town
- **OUTSIDERS**: Proportion of population considered outsiders
- **LSTAT**: Percentage of lower status population
- **Price**: Median value of owner-occupied homes in $1000s (Target Variable)

## Data Preprocessing
- Checked for missing values and confirmed there were none.
- Conducted exploratory data analysis (EDA) to understand correlations between variables.
- Visualized relationships between different features and house prices using scatter plots and regression plots.

## Exploratory Data Analysis (EDA)
- **Correlation Analysis**: Examined the relationships between features and the target variable.
  - RM (Number of Rooms) showed a strong positive correlation with house prices.
  - LSTAT (Lower Status Population) had a strong negative correlation with house prices.
  - Crime rate (CRIM) and other socio-economic indicators also had notable correlations.
- **Visualization**:
  - Scatter plots were generated to explore the relationship between features like RM, LSTAT, CHAS, and PTRATIO with house prices.
  - Regression plots helped understand the linear relationships between features and price.

## Feature Engineering
- Separated independent features (X) and the target variable (Y).
- Identified key features that influence house pricing.
- Normalized and scaled features for better model performance.

## Model Building & Evaluation
- Implemented multiple regression models to predict house prices.
- Evaluated model performance using metrics such as RMSE and R-squared.
- Applied feature selection techniques to improve model accuracy.

## Output & Results
- The model successfully predicted house prices based on input features.
- Identified significant factors influencing property values in Boston.
- Provided insights into how crime rate, number of rooms, and socio-economic status affect housing prices.

## Conclusion
This project demonstrates an effective approach to predicting house prices using data-driven methods. The findings can assist in real estate decision-making and policy planning by identifying key factors affecting property values.

