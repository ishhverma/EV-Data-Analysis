# Electric Vehicle Population Data Analysis 🚗⚡
## Project Overview
This project presents a comprehensive analysis of the **Electric Vehicle Population Dataset** provided by the Washington State Department of Licensing.
The dataset contains information related to:
* Battery Electric Vehicles (BEVs)
* Plug-in Hybrid Electric Vehicles (PHEVs)
* Vehicle registration details
* Electric range
* County and geographic information
* CAFV eligibility
* Vehicle manufacturers and models
The analysis focuses on **data cleaning, exploratory data analysis (EDA), data visualisation, and machine learning** to understand electric vehicle adoption patterns and predict electric range.

# Objectives
This project aims to:
✔ Clean and prepare the dataset
✔ Handle missing values and duplicate records
✔ Protect privacy through VIN anonymisation
✔ Explore EV adoption and registration trends
✔ Analyse county-wise and regional EV distribution
✔ Create interactive and statistical visualisations
✔ Build and evaluate a Linear Regression model for electric range prediction

# Dataset Information
**Dataset Source:**
Electric Vehicle Population Data – Washington State Department of Licensing
The dataset includes:
* Vehicle Identification Number (VIN)
* County and City
* State and Postal Code
* Model Year
* Vehicle Make and Model
* Electric Vehicle Type
* Electric Range
* Vehicle Location
* Electric Utility
* CAFV Eligibility
* Census Tract Information

# Tools and Technologies Used
The project was completed using:
* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Folium
* Scikit-learn
* Jupyter Notebook

# Project Workflow
## 1. Data Cleaning
Key preprocessing steps included:
* Missing value analysis
* Electric Range imputation
* Duplicate record checking
* VIN anonymisation using SHA256 hashing
* Vehicle location parsing into latitude and longitude

## 2. Exploratory Data Analysis (EDA)
The analysis explored:
* Top EV makes and models
* County-wise EV distribution
* EV adoption by model year
* Average electric range
* CAFV eligibility distribution
* Regional adoption trends
* Electric range variation across makes and models

## 3. Data Visualisation
Visualisations created in the project include:
* Bar Chart – Top EV Makes and Models
* County Distribution Map
* EV Adoption Trend Line Graph
* CAFV Eligibility Pie Chart
* Geospatial Vehicle Location Map (Folium)

## 4. Machine Learning – Linear Regression
A Linear Regression model was developed to predict:
**Electric Range**
### Features Used
* Model Year
* Make
* Model
* Electric Vehicle Type
### Data Preparation
Categorical variables were transformed using:
* One-Hot Encoding
* `pd.get_dummies(drop_first=True)`

### Model Evaluation

| Metric   | Score |
| -------- | ----: |
| R² Score |  0.51 |
| MAE      | 36.86 |
| RMSE     | 54.30 |

# Key Findings
The analysis revealed several important insights:
* Tesla dominates EV registrations
* Model Y and Model 3 are the most registered EV models
* King County records the highest EV adoption
* EV registrations increased sharply after 2018
* Urban regions show stronger EV adoption than rural regions
* CAFV eligibility remains limited for many vehicles
* Linear Regression explains approximately 51% of electric range variation

# Repository Structure
```text
EV-Data-Analysis/
│
├── EV_Analysis_Ishu_Verma.ipynb
├── README.md
├── dataset.csv
├── charts/
├── images/
└── report/
```

# Repository Link
Repository:
https://github.com/ishhverma/EV-Data-Analysis

# Author
**Ishu Verma**
