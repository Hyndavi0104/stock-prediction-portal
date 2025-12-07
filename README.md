# 📊 Stock Price Prediction Portal

A full-stack web application that predicts future stock prices using an LSTM-based machine learning model.  
Users can enter a stock ticker (example: **AAPL, TSLA, MSFT**) and visualize:

✔ Historical stock prices  
✔ 100-Day and 200-Day Moving Averages  
✔ Predicted vs Actual Price Graph  
✔ Model Evaluation Metrics (MSE, RMSE, R² Score)

---

## 🚀 Tech Stack

### 🖥 Frontend
- React.js
- Axios
- Vite
- Bootstrap

### ⚙ Backend
- Django REST Framework
- TensorFlow / Keras
- Pandas, NumPy, Scikit-Learn
- Matplotlib

---

## 📦 Features

- Fetches real-time stock market data using **Yahoo Finance (yfinance)**  
- Generates and saves prediction graphs dynamically
- Interactive UI to view:
  - Stock price curve
  - Moving averages
  - Final prediction plot
- REST API endpoint for stock predictions

---

## 🔧 Installation

### Backend (Django)

cd backend

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver

### Frontend

cd frontend

npm install

npm run dev

###🔑 Environment Variables

Create a .env file inside the React frontend:

VITE_BACKEND_BASE_API=http://127.0.0.1:8000/api/v1

### 🧠 Machine Learning Model

Model Type: LSTM Neural Network

Scaling: MinMaxScaler

Evaluation Metrics:

MSE (Mean Squared Error)

RMSE (Root Mean Squared Error)

R² Score

### ▶️ Usage

Enter a stock ticker symbol (Example: AAPL).

Click See Prediction.

View:

Price graph

Moving averages

Prediction curve

Model performance



### 👩‍💻 Author

Hyndavi Thota

### ⭐ Contribution

Pull Requests are welcome. For major changes, open an issue first.

### 📜 License

This project is licensed under the MIT License.
