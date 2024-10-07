# Electric Vehicles EDA

## Overview

This project involves exploratory data analysis (EDA) of a dataset focusing on electric vehicles. The dataset includes essential information about various electric vehicles, including their specifications, pricing, and geographic details.

## Dataset Information

The dataset is obtained from Kaggle:
https://www.kaggle.com/datasets/ironwolf404/electric-vehicle-population-in-usa

The dataset contains the following columns:

- **VIN (1-10)**: Vehicle Identification Number, which uniquely identifies the vehicle (1-10)
- **County**: Geographic county information
- **City**: Geographic city information
- **State**: State where the vehicle is registered
- **Postal Code**: Zip code of the vehicle's location
- **Model Year**: Year the vehicle model was released
- **Make**: Manufacturer of the vehicle
- **Model**: Specific model of the vehicle
- **E.V_Type**: Type of electric vehicle (e.g., battery electric, plug-in hybrid)
- **CAFV**: Clean Alternative Fuel Vehicle designation
- **Electric Range**: Estimated range on a full charge
- **Base MSRP**: Manufacturer's suggested retail price
- **Legislative District**: Relevant legislative district
- **DOL Vehicle ID**: Department of Licensing Vehicle ID
- **Vehicle Location**: Detailed location information
- **Electric Utility**: Electric utility provider for the vehicle
- **2020 Census Tract**: Census tract information based on the 2020 census

However, I have minimized into the following data set as the other columns are not relevant
- **Vehicle ID**: Unique identifier for each vehicle
- **County**: Geographic county information
- **City**: Geographic city information
- **State**: State where the vehicle is registered
- **Postal Code**: Zip code of the vehicle's location
- **Model Year**: Year the vehicle model was released
- **Make**: Manufacturer of the vehicle
- **Model**: Specific model of the vehicle
- **E.V_Type**: Type of electric vehicle (e.g., battery electric, plug-in hybrid)
- **Electric Range**: Estimated range on a full charge
- **Base MSRP**: Manufacturer's suggested retail price
- **Vehicle Location**: Detailed location information

*Note: This dataset is a small extract from a larger dataset.*

## Tools and Technologies

- **Programming Language**: Python
- **Libraries Used**: 
  - Pandas and NumPy for data manipulation and wrangling
  - Matplotlib and Seaborn for data visualization
- **Dashboard Tool**: IBM Cognos Analytics for presenting insights and visualizations
