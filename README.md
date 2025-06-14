🚲 Bike Sharing Demand Prediction using HistGradientBoosting Regressor
This project aims to predict the number of rented bikes per day based on various environmental and seasonal factors using the HistGradientBoosting Regressor from Scikit-learn. The dataset used is a day-level summary of bike rental data, originally from the UCI Machine Learning Repository.

📁 Project Structure
Copy
Edit
📦 Bike_Sharing_HGBR
 ┣ 📄 Bike_Sharing_HistGradientBoosting_Regressor.ipynb
 ┣ 📄 day.csv
 ┗ 📄 README.md
📊 Dataset
The dataset day.csv contains daily counts of rental bikes from a bike-sharing system in Washington, D.C. Variables include:

season, yr, mnth, holiday, weekday, workingday: time and calendar-related features

temp, atemp, hum, windspeed: weather conditions

cnt: total count of bikes rented (target variable)

🔍 Objectives
Preprocess the data (e.g., handle categorical features, scaling)

Train a HistGradientBoostingRegressor model

Evaluate model performance using metrics like MAE, RMSE, and R²

Visualize prediction results and feature importances

🧠 Machine Learning Model
Algorithm: HistGradientBoosting Regressor (Scikit-learn)

Target: cnt (daily total bike rental count)

Features: Weather, date, and season attributes

📈 Results
The model achieves high accuracy and performs well in predicting daily demand.

MAE, RMSE, and R² metrics are computed and visualized.

Feature importance is plotted to interpret which variables impact demand the most.

📌 Requirements
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

Install dependencies using: pip install -r requirements.txt

🚀 Getting Started
1. Clone this repository:
git clone https://github.com/Jake281103/biksharingdemanprediction.git
cd bike-sharing-hgbr

2. Launch the Jupyter notebook:
jupyter notebook Bike_Sharing_HistGradientBoosting_Regressor.ipynb

📚 References
Bike Sharing Dataset - UCI Repository
Pedregosa et al., Scikit-learn: Machine Learning in Python, JMLR 2011
https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset


