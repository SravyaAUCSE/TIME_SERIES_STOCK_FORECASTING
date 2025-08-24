TIME_SERIES_STOCK_FORECASTING
An interactive and automated stock market forecasting dashboard built with Streamlit, integrating both classical time series models (ARIMA, SARIMA, Prophet) and deep learning (LSTM).

The project’s goal is to provide analysts and investors with a user-friendly forecasting tool that automates data preprocessing, model building, and performance evaluation for better decision-making.

🚀 Features

✅ Upload or auto-load multiple stock datasets

📊 EDA with trend visualization, rolling averages & outlier detection

🧹 Preprocessing: missing values handling, scaling, formatting

📈 Forecasting with ARIMA, SARIMA, Prophet, and LSTM

🎛️ Hyperparameter tuning (manual & automated)

📉 Model performance comparison using RMSE, MAE, and MAPE

💾 Save trained models for reuse

📊 Real-time interactive plots with Plotly

🧠 LSTM for capturing long-term dependencies

🧭 Dashboard Modules

🔍 Exploratory Data Analysis & Outlier Detection

🤖 Forecasting with Classical & Deep Learning Models

📊 Model Comparison Metrics

📊 Models Implemented Model Type Framework Key Feature ARIMA Traditional statsmodels Works on lag, trend, and moving average SARIMA Traditional statsmodels Adds seasonality Prophet Additive Model fbprophet Handles seasonality, holidays, and trends LSTM Deep Learning TensorFlow/Keras Learns sequential patterns & long-term dependencies

📊 Evaluation Metrics

RMSE – Penalizes large errors

MAE – Mean of absolute errors

MAPE – Percentage-based error measure

📁 Project Structure

TIME_SERIES_STOCK_FORECASTING/

│── app.py # Main Streamlit application

│── data/ # Stock CSV datasets

│── models/ # Trained models storage

│── screenshots/ # Screenshots for documentation

│── traditional_models.py # ARIMA, SARIMA, Prophet functions

│── lstm_model.py # Deep Learning LSTM logic

│── eda_outliers.py # EDA & outlier detection

│── comparison.py # Model comparison and evaluation

│── utils.py # Utility functions (scaling, metrics, etc.)

│── requirements.txt # Required Python packages

└── README.md # Documentation

📦 Installation & Running Locally

1.Clone the Repo bash Copy Edit git clone https://github.com/Hamsavall/TIME_SERIES_STOCK_FORECASTING.git cd TIME_SERIES_STOCK_FORECASTING

2.Install Dependencies bash Copy Edit pip install -r requirements.txt

3.Add CSV Data Dataset: https://www.kaggle.com/datasets/szrlee/stock-time-series-20050101-to-20171231?utm_source=chatgpt.com

4.Run the Streamlit App bash Copy Edit streamlit run app.py 📬 Usage Notes ✅ Handles multiple stocks: loops through all CSVs in /data folder.

SCREENSHOTS:
<img width="653" height="472" alt="481370934-2d5fffda-267f-4b9d-a6c9-abf16ff8a737" src="https://github.com/user-attachments/assets/680d618e-1b33-40e9-afa3-fb5b76570301" />

<img width="719" height="435" alt="481371573-e1513c97-e879-4d7e-852f-74fcc2d53a70" src="https://github.com/user-attachments/assets/644df44b-13b0-4274-b91c-5c9ea9de287f" />

<img width="674" height="439" alt="481371594-776015ed-2122-49a1-bd79-7da1e73cf5c8" src="https://github.com/user-attachments/assets/3a2131e4-724f-4aa6-adb6-28d9b7915e1c" />

📌 Usage Guide

Data Handling: Upload your own stock CSVs or use provided datasets.

EDA: Explore trends, rolling averages, and detect anomalies.

Modeling: Choose between ARIMA, SARIMA, Prophet, or LSTM.

Tuning: Adjust hyperparameters manually or run automated tuning.

Forecasting: Generate predictions for future stock values.

Comparison: Evaluate models side by side using RMSE, MAE, and MAPE.

Save & Reuse: Store trained models in /models for later use.

🛠 Tools & Technologies

Languages: Python

Frameworks: Streamlit, TensorFlow/Keras, Statsmodels, FbProphet

Libraries: Pandas, NumPy, Scikit-learn, Plotly, Matplotlib, Seaborn

Deployment: Streamlit app (local or cloud hosting)

🤝 Contributing

Fork the repository

Create a feature branch

Make your changes

Add tests if applicable

Submit a pull request

👤 Author :

JAMI SRAVYA - https://github.com/SravyaAUCSE

👥 Contributor :

V HAMSA VALLI - https://github.com/Hamsavall

📄 License

This project is licensed under the MIT License
