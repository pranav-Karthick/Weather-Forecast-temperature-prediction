🌦 Weather Forecast Temperature Prediction using Linear Regression
📌 Project Overview

This project uses a Linear Regression machine learning model to predict temperature based on weather parameters from a real dataset.
The aim is to learn how supervised learning regression models can be applied to environmental data to forecast temperature trends.

The project is implemented in Python and executed using Google Colab.

📁 Dataset Information

Dataset Source: Kaggle
Dataset Name: Weather Forecast Dataset
Author: Zeeshier

The dataset contains multiple environmental features such as:

Humidity

Wind speed

Pressure

Rainfall

Cloud cover

Other meteorological parameters

Target Variable: Temperature
Input Features: All numeric columns except Temperature

🛠 Tools and Libraries Used
Tool / Library	Purpose
Python	Programming language
Pandas	Data processing
NumPy	Numerical calculations
Matplotlib	Visualization
Scikit-learn	Machine learning
Kaggle API	Dataset download
Google Colab	Execution platform
⚙ Installation & Setup
Step 1: Upload Kaggle API Key

Download your kaggle.json file from your Kaggle account and upload it to Colab.

Step 2: Install Kaggle
pip install kaggle

Step 3: Configure API Key
mkdir ~/.kaggle
cp kaggle.json ~/.kaggle/
chmod 600 ~/.kaggle/kaggle.json

Step 4: Download Dataset
kaggle datasets download -d zeeshier/weather-forecast-dataset
unzip weather-forecast-dataset.zip

🧠 Machine Learning Workflow
1. Load Dataset

The CSV file is loaded using Pandas.

2. Data Cleaning

Remove missing values

Keep numerical features only

3. Feature Selection

Inputs: All parameters except Temperature

Output: Temperature

4. Train-Test Split

Dataset split into:

80% Training data

20% Testing data

5. Model Training

A Linear Regression model is trained using Scikit-learn.

6. Prediction

Temperature values are predicted for test data.

7. Evaluation

Model is evaluated using:

MAE (Mean Absolute Error)

RMSE (Root Mean SquARED Error)

R² Score

📊 Output

You will get:

✅ Actual vs Predicted temperature values
✅ Error metrics (MAE, MSE, RMSE)
✅ Accuracy score (R²)
✅ Visual comparison plot

📈 Sample Output Visualization

The model plots a graph showing:

Actual temperature values

Predicted temperature values

This helps visually evaluate prediction quality.

📂 Project Structure
├── weather_forecast_data.csv
├── temperature_prediction.py
├── README.md

🚀 How to Run

Open Google Colab

Upload this project

Run code cells in order

Observe predictions & output graph

🔮 Future Improvements

Use Polynomial Regression

Try Random Forest Regressor

Implement LSTM for Time-Series Prediction

Feature importance analysis

Hyperparameter tuning

✅ Conclusion

Linear Regression gives a simple baseline for temperature prediction and helps you understand:

Regression concepts

Feature relationships

Prediction accuracy measurement

This project is ideal for beginners learning machine learning with real-world data.