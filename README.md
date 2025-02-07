# Electric Vehicle Population Data Analysis
# Phase 1: Data Preprocessing 
## Overview
This phase focuses on loading, cleaning, and preprocessing the Electric Vehicle Population Data. The goal is to prepare the data for further analysis and modeling.

## Dataset
* Dataset name: Electric Vehicle Population Data
* Source: https://catalog.data.gov/dataset/electric-vehicle-population-data 
* Description: The Electric Vehicle Population Data dataset contains information about electric vehicles in the United States. The dataset comprises 223995 observations and 17 variables, including:
    1.  Vehicle characteristics: make, model, electric vehicle type, and base MSRP
    2.  Geographic information: county, city, state, postal code, and legislative district
    3. Demographic data: 2020 census tract information
    4. Utility and location data: electric utility and vehicle location

The dataset aims to provide insights into the population and characteristics of electric vehicles in the United States, which can be useful for researchers, policymakers, and industry stakeholders.

## Data Preprocessing Steps
1. Handling missing values: Replaced missing values in numerical columns with mean and categorical columns with mode.
2. Outlier detection and removal: Identified and removed outliers using the IQR method.
3. Encoding categorical variables: Used LabelEncoder to convert categorical variables into numerical variables.
4. Feature scaling: Scaled numerical variables using StandardScaler.
