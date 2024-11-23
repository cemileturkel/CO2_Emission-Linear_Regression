# CO2 Emission Analysis

This repository contains data and code for analyzing CO2 emissions based on various vehicle attributes. The primary dataset used in this analysis is `CO2_emission.csv`.

## Dataset

The `CO2_emission.csv` file contains the following columns:

- **Model_Year**: The year the vehicle model was manufactured.
- **Make**: The brand of the vehicle (e.g., Toyota, Ford, BMW).
- **Model**: The specific model of the vehicle (e.g., Corolla, Mustang, X5).
- **Vehicle_Class**: The class of the vehicle (e.g., sedan, SUV, truck).
- **Engine_Size**: The size of the vehicle's engine in liters.
- **Cylinders**: The number of cylinders in the vehicle's engine.
- **Transmission**: The type of transmission (e.g., manual, automatic).
- **Fuel_Consumption_in_City(L/100 km)**: The fuel consumption of the vehicle in the city, measured in liters per 100 kilometers.
- **Fuel_Consumption_in_City_Hwy(L/100 km)**: The fuel consumption of the vehicle on the highway, measured in liters per 100 kilometers.
- **Fuel_Consumption_comb(L/100km)**: The combined fuel consumption of the vehicle, measured in liters per 100 kilometers.
- **CO2_Emissions**: The CO2 emissions of the vehicle, measured in grams per kilometer.
- **Smog_Level**: The smog level contribution of the vehicle.

## Analysis

The analysis includes the following steps:

1. **Data Loading and Preparation**:
   - Load the dataset using pandas.
   - Handle missing values and encode categorical variables.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of CO2 emissions.
   - Analyze the relationship between CO2 emissions and other variables.

3. **Model Building**:
   - Build a linear regression model to predict CO2 emissions based on vehicle attributes.
   - Evaluate the model using metrics such as Mean Squared Error (MSE) and R² score.

4. **Prediction**:
   - Use the trained model to predict CO2 emissions for new data points.

## Usage

To run the analysis, follow these steps:

1. Clone the repository: ```bash
   git clone https://github.com/cemileturkel/CO2_Emission-Linear_Regression.git
   cd CO2_Emission-Linear_Regression

   Install the required dependencies:

pip install -r requirements.txt
Run the analysis script:

python analysis.py
Results
The results of the analysis, including visualizations and model performance metrics, are saved in the results directory.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
