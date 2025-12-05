🌤 Weather Forecasting Using Synthetic Data (Linear Regression)
📌 Project Overview

This project demonstrates how Linear Regression can be used to predict temperature using artificially generated weather data.
Instead of using a real dataset, a synthetic dataset is created to simulate weather conditions such as humidity, pressure, wind speed, and sunlight.

The model then learns from this data and predicts temperature values.
This project is ideal for understanding regression modelling, data generation, and prediction visualization.

📊 Synthetic Dataset Description

The dataset is programmatically generated using random values with realistic ranges:

Feature	Description	Unit
Humidity	Moisture in the air	%
Pressure	Atmospheric pressure	hPa
Wind	Wind speed	m/s
Sunlight	Sunlight duration	hours
Temperature	Output variable (Target)	°C

The temperature is generated using a mathematical formula with controlled noise to simulate real-world behavior.

🛠 Technologies Used

Python

NumPy

Pandas

Matplotlib

Scikit-learn

⚙ How the Model Works

Synthetic weather data is generated.

Features are separated from the target (Temperature).

Dataset is split into training and testing sets.

Linear Regression model is trained.

Predictions are generated.

Performance evaluated with R² and RMSE.

Results are plotted.

📂 Project Structure
├── weather_prediction.py
├── README.md

🚀 How to Run
Step 1 — Install required libraries

Make sure Python is installed and run:

pip install numpy pandas matplotlib scikit-learn

Step 2 — Run the script
python weather_prediction.py

Step 3 — View Output

You will see:

✅ R² and RMSE values in terminal
✅ Table showing Actual vs Predicted temperature
✅ Graph comparing predictions against actual values

📈 Sample Output

The graph shows:

Real (synthetic) temperature values

Model predictions

A close overlap indicates good accuracy.

🧠 Learning Outcomes

Understanding regression models

Creating datasets synthetically

Training ML models

Measuring prediction performance

Visualizing results

🔮 Future Improvements

Add Polynomial Regression

Introduce seasonal patterns

Add noise analysis

Use Random Forest

Convert to real dataset input

Deploy as web app

✅ Conclusion

This project shows how Linear Regression successfully predicts temperature when a linear relationship exists.
It helps beginners understand how models behave under controlled environments.