# Car Company Records Data Analysis and Visualization
This project focuses on analyzing and visualizing a dataset of car company records. The dataset contains information about cars listed on the Autotrade website, including features such as public_reference, mileage, reg_code, standard_colour, standard_make, standard_model, vehicle_condition, year_of_registration, price, body_type, crossover_car_and_van, and fuel_type.

## Introduction
The purpose of this project is to analyze and visualize the car company records dataset to gain insights into various aspects of the data. The dataset consists of 12 columns and 402,005 rows, providing information about cars listed on the Autotrade website.

## Features and Meaning
The dataset contains the following features:

1. public_reference: A unique identifier used for listing products on the Autotrade website.
2. mileage: The annual mileage of a car in miles.
3. reg_code: The registration code used as an extra descriptor for the year the car was registered.
4. standard_colour: The color of the external chassis of the car.
5. standard_make: The brand/manufacturer of a car.
6. standard_model: The name of a specific vehicle type of a brand.
7. vehicle_condition: The condition of a car.
8. year_of_registration: The year of registration of the vehicle.
9. price: The listed price of the car in pounds sterling.
10. body_type: The style of the car's chassis.
11. crossover_car_and_van: A boolean value indicating whether the car is a crossover or a van.
12. fuel_type: The type of energy used to power the car.

## Data Cleaning
The data cleaning process involved addressing missing values, outliers, and noise. The steps taken to clean the data include:

1. Handling missing values by filling them with appropriate values from related columns or dropping rows with missing values.
2. Treating outliers and noise by removing extreme values that do not align with the characteristics of the dataset.

## Missing Values
The dataset contains missing values in various columns, including year_of_registration, reg_code, standard_colour, mileage, body_type, and fuel_type. The percentage of missing values ranges from 0.07% to 1.5% of the total values in the dataset. To handle these missing values, different strategies were employed, such as filling missing values with related column values or dropping rows with missing values.

## Outliers and Noise
After cleaning the data, the presence of outliers and noise was identified in the dataset. Outliers were observed in the mileage, year_of_registration, and price columns. These outliers were treated by removing extreme values that deviated significantly from the overall distribution of the data.

## Analysis and Visualization
The cleaned dataset was further analyzed and visualized to gain insights into the car company records. Descriptive statistics and visualizations were used to understand the distribution, relationships, and patterns within the data. The analysis aimed to provide a comprehensive understanding of the dataset and highlight key findings and trends.

Please refer to the report.ipynb notebook for a detailed analysis and visualization of the car company records dataset.
