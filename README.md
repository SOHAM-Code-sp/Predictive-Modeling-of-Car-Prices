# Predictive Modeling of Car Prices

## Project Overview
This project aims to build a predictive model for car prices using a dataset containing various car attributes. The model will help management understand pricing dynamics and formulate market strategies.

## Dataset
The dataset `CarPrice_Assignment.csv` contains information on 205 cars with 26 attributes, including features like fuel type, engine specifications, and price.

## Project Structure

car-prices-prediction/
│ README.md
│ requirements.txt
│
├───data/
| problem_statement
│ CarPrice_Assignment.csv
│
└───notebooks/
car_price_analysis.ipynb



## Project Overview
This project aims to build a predictive model to estimate car prices based on various automotive features. The goal is to assist Geely Auto in understanding pricing dynamics in the US market and inform their market entry strategy.

### 🎯 Business Problem
A Chinese automaker, Geely Auto, plans to enter the US market by manufacturing cars locally. They need to understand:

Which factors significantly influence car pricing in the US

How well these factors explain price variations.


### 📈 Data Source
**Dataset**: Car Price Prediction Dataset
**Samples**: 205 vehicles
**Features**: 25+ attributes including:

* Technical specifications (engine size, horsepower, dimensions)

* Vehicle characteristics (body type, fuel system, drive wheel)

* Market attributes (symboling insurance risk rating)

* Key Features Examined:

* enginesize, horsepower, curbweight - Strongest price correlates

* carbody, drivewheel, fueltype - Categorical influencers

* citympg, highwaympg - Fuel efficiency metrics



### Key Analysis Steps
**Data Exploration**: Statistical summaries and missing value analysis

**Feature Engineering**: One-hot encoding, correlation analysis

**Model Training**: Linear Regression, Decision Trees, Random Forest

**Model Evaluation**: Cross-validation, error metrics, feature importance

**Business Insights**: Actionable recommendations for stakeholders

### 📊 Results & Findings
Model Performance Comparison

Model	Training R²	Test R²	Test RMSE	Test MAE
Random Forest	0.96	0.85	$2,450	$1,890
Decision Tree	0.98	0.78	$3,120	$2,410
Linear Regression	0.82	0.79	$3,050	$2,380

**Key Feature Importance**
- The Random Forest model identified these as the most influential price factors:

https://reports/assets/images/feature_importance.png

## Top Price Determinants
* Engine Size (24% importance) - Strongest individual predictor

* Curb Weight (18% importance) - Correlates with vehicle size and luxury features

* Horsepower (15% importance) - Key performance indicator

* Car Width (9% importance) - Indicator of vehicle class and luxury

* City MPG (7% importance) - Fuel efficiency economic factor

## Business Insights
**Premium Segment**: Engine size and horsepower are critical differentiators

**Economic Segment**: Fuel efficiency (MPG) significantly impacts pricing

**Design Strategy**: Vehicle dimensions (width/weight) should align with target price points

**Market Positioning**: Drive wheel type (FWD/RWD/4WD) affects perceived value across segments

### 🚀 Technologies Used
#### Core Technologies
**Python**: Primary programming language

**Pandas**: Data manipulation and analysis

**NumPy**: Numerical computations

**Scikit-learn**: Machine learning algorithms and evaluation

**Matplotlib/Seaborn**: Data visualization and plotting

Machine Learning Algorithms
**Random Forest Regressor**: Primary model (best performance)

**Decision Tree Regressor**: Baseline non-linear model

**Linear Regression**: Baseline linear model

**GridSearchCV**: Hyperparameter tuning

## Data Science Techniques
* **Exploratory Data Analysis (EDA)**: Comprehensive data understanding

* **Feature Engineering**: One-hot encoding, correlation analysis

* **Cross-Validation**: Robust model evaluation

* **Feature Importance**: Model interpretability and business insights

### 💡 Business Impact
This model provides automotive companies with:

* **Pricing Strategy Optimization**: Data-driven approach to setting competitive prices

* **Feature Value Assessment**: Quantify the monetary value of specific vehicle features

*  **Market Segmentation**: Identify key differentiators for various price segments

* **New Product Planning**: Guide development of vehicles for specific price points



Contributors: [Soham Poria]
License: MIT License


