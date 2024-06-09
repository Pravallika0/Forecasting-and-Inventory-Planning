# Forecasting-and-Inventory-Planning
# Forecasting and Inventory Planning

## Overview
This project involves forecasting passenger numbers for an airline using time series analysis techniques in R. The dataset used is the "AirPassengers" dataset, which contains monthly passenger numbers from 1949 to 1960.

## Steps

### 1. Load Forecast Package and Data
- The "forecast" package is installed and loaded into RStudio, along with the "readxl" package for Excel file reading.
- The dataset is loaded from an Excel file named "AirPassengers.xlsx" and its class is checked.

### 2. Display Dataset
- The dataset is displayed using the "head" function to view its structure.

### 3. Summary and Handling Missing Values
- Summary statistics of the dataset are checked using the "summary" function.
- Any missing values in the dataset are identified and removed using the "na.omit" function.

### 4. Plot the Dataset
- The dataset is plotted to visualize the trend in passenger numbers over time.

### 5. Estimate Trend
- A moving average is used to estimate the trend in passenger numbers.

### 6. Plot Dataset with Trendline
- The dataset is plotted again with the estimated trendline.

### 7. Create Univariate Time Series Object
- A univariate time series object is created using the "ts" function.

### 8. Apply Auto ARIMA Model
- The auto.arima function is applied to the univariate time series to automatically select the best ARIMA model.

### 9. Forecast Future Values
- Forecasted values for the next 10 years are generated using the forecast function.

### 10. Validate the Model
- The accuracy of the ARIMA model is assessed using the accuracy function.

![image](https://github.com/Pravallika0/Forecasting-and-Inventory-Planning/assets/117079437/a6a94db8-058d-48e7-bd30-6fed1799f43f)
![image](https://github.com/Pravallika0/Forecasting-and-Inventory-Planning/assets/117079437/6890f083-45bd-4733-9a95-5de1b1228198)


## README Generation
A README file summarizing the steps performed for forecasting passenger numbers and inventory planning is generated. This README provides an overview of the project, steps involved, and key findings.

---

Feel free to customize this README according to your specific analysis and results before uploading it to GitHub.
