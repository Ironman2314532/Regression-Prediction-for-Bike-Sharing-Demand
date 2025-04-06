# Regression Prediction for Bike Sharing Demand

This project focuses on developing predictive models to estimate the hourly demand for bike rentals in Seoul, leveraging the [Seoul Bike Sharing Demand dataset](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand) from the UCI Machine Learning Repository.

## Project Overview

Accurately forecasting bike rental demand is crucial for ensuring that bike-sharing systems can meet user needs efficiently. This project explores two regression models:

- **Linear Regression Model**: A statistical approach to model the relationship between the dependent variable (bike demand) and independent variables (weather conditions, time, etc.).
  
- **Regression Neural Network Model**: A deep learning approach that captures complex, non-linear relationships in the data.

## Dataset

The dataset comprises 8,760 instances with 14 attributes, including:

- **Date**: Recorded in the format year-month-day.
- **Rented Bike Count**: Number of bikes rented per hour.
- **Hour**: Hour of the day (0 to 23).
- **Temperature**: Measured in Celsius.
- **Humidity**: Percentage.
- **Windspeed**: Measured in m/s.
- **Visibility**: Measured in 10 meters.
- **Dew Point Temperature**: Measured in Celsius.
- **Solar Radiation**: Measured in MJ/m².
- **Rainfall**: Measured in mm.
- **Snowfall**: Measured in cm.
- **Seasons**: Categorical variable indicating Winter, Spring, Summer, or Autumn.
- **Holiday**: Binary variable indicating Holiday/No holiday.
- **Functional Day**: Binary variable indicating NoFunc (Non-functional hours) or Fun (Functional hours).

For more details, refer to the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand).

## Usage Instructions

To replicate the analysis:

1. **Download the Dataset**: Obtain the `SeoulBikeData.csv` file from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand).

2. **Open the Notebook**: Access the `Seoul_bikes_regression.ipynb` file in [Google Colab](https://colab.research.google.com/).

3. **Upload the Dataset**: In the Colab interface, upload the `SeoulBikeData.csv` file to the session storage.

4. **Execute the Notebook**: Run all cells in the notebook to train, validate, and test both regression models. The notebook provides detailed explanations and outputs for each step.

## Contributing

Pull requests are welcome.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Acknowledgments

Special thanks to the UCI Machine Learning Repository for providing the [Seoul Bike Sharing Demand dataset](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand), which forms the foundation of this project.

