🌦️ Weather Temperature Prediction using Linear & Polynomial Regression

This project builds and compares Linear Regression and Polynomial Regression models to predict daily temperature using historical weather data. It also includes data visualization using pairplots to understand relationships between temperature and other features.

📁 Dataset

Dataset used:

/content/daily_weather.csv


Source: Kaggle (Indian Weather Dataset)

🎯 Project Objective

To:

Predict temperature using regression models

Compare Linear vs Polynomial Regression

Visualize data relationships using Pairplot

Evaluate performance using accuracy metrics

Display actual vs predicted temperature

⚙️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

Google Colab / Jupyter Notebook

🧠 Models Implemented
1. Linear Regression

Assumes a linear relationship between input features and temperature.

2. Polynomial Regression (Degree = 2)

Handles non-linear relationships by expanding features.

📊 Exploratory Data Analysis
Pairplot Visualization

Used to visualize relationships between temperature and numeric features:

Helps detect linear / non-linear patterns

Helps find strong predictors

Detects outliers

📌 Steps to Run the Project
Step 1: Upload Dataset

Upload the file daily_weather.csv in Google Colab.

Step 2: Install Dependencies (if required)
pip install pandas numpy matplotlib seaborn scikit-learn

Step 3: Run the Script

Execute the provided Python file / notebook.

Step 4: View Results

The output will include:

Pairplot graph

Actual vs predicted temperature table

Linear regression plot

Polynomial regression plot

Performance metrics

📈 Evaluation Metrics Used
Metric	Meaning
MSE	Average squared error
RMSE	Root of MSE
R² Score	Accuracy measure
✅ Sample Output

Example:

Linear Regression:
MSE: 4.28
RMSE: 2.06
R2 Score: 0.72

Polynomial Regression:
MSE: 3.91
RMSE: 1.97
R2 Score: 0.78

🔍 Interpretation

Higher R² score indicates a better model

Lower RMSE indicates better prediction

If Polynomial has higher R² → data is non-linear

If Linear is better → data follows simple pattern

🚀 Possible Enhancements

Hyperparameter tuning

Time-series forecasting

Feature engineering

Deep learning implementation

Model deployment

🧾 Project Structure
/project-directory
│
├── daily_weather.csv
├── temperature_prediction.ipynb
├── README.md

👨‍💻 Author

Created by: Pranav Karthick

📜 License

This project is licensed under the MIT License