# 🪙 Real-Time Data Extraction and Prediction of Cryptocurrency

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Flask](https://img.shields.io/badge/Flask-Backend-lightgrey)
![TensorFlow](https://img.shields.io/badge/TensorFlow-LSTM-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Model-yellowgreen)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

> A real-time cryptocurrency analysis and prediction system integrating *LSTM* and *XGBoost* machine learning models with a clean *frontend interface* for visualization.

---

## 🖼 Project Overview

This project focuses on real-time *data extraction, **machine learning prediction, and **visualization* of cryptocurrency trends.  
It combines *Flask-based backend APIs* with *HTML/CSS/JS frontend* to provide a simple web dashboard for crypto forecasting.

---

### 📂 Folder Structure

```bash
Real-Time_Data_Extraction_and_Prediction_of_Cryptocurrency/
│
├── run.txt
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   ├── train_lstm.py
│   ├── train_xgb.py
│   │
│   └── models/
│       ├── lstm_model.h5
│       ├── lstm_scaler.save
│       ├── xgb_btc_model.pkl
│       └── xgb_scaler.pkl
│
└── frontend/
    ├── index.html
    ├── style.css
    └── api_connection.js
```

---

## 🚀 Features

✅ Real-time cryptocurrency data extraction  
✅ LSTM-based time series forecasting  
✅ XGBoost-based short-term prediction  
✅ Interactive web dashboard  
✅ Modular backend–frontend separation  
✅ Clean code for scalability and deployment  

---

## 🧠 Tech Stack

*Backend:*
- Python, Flask  
- TensorFlow / Keras  
- XGBoost, Scikit-learn  
- Pandas, NumPy  

*Frontend:*
- HTML5  
- CSS3  
- JavaScript  

---

## ⚙ Setup Instructions

1. Clone Repository
   ```bash
   git clone https://github.com/Maadhu938/Real-Time_Data_Extraction_and_Prediction_of_Cryptocurrency.git
   cd Real-Time_Data_Extraction_and_Prediction_of_Cryptocurrency/backend
2. Install Dependencies

pip install -r requirements.txt


3. Run Backend

python train_lstm.py and python train_xgb.py
python app.py


4. Launch Frontend

Open the frontend/ and command python -m http.server 8000 and open localhost in browser

The page will automatically fetch data from your Flask backend.





---

📊 Model Summary

Model	Type	Purpose	File

LSTM	Deep Learning	Time-series crypto prediction	lstm_model.h5
XGBoost	Machine Learning	BTC regression forecasting	xgb_btc_model.pkl



---

🔮 Future Enhancements

Live chart updates with WebSocket

Deploy backend on Render / AWS / Heroku

Add user accounts & portfolio tracking

Support for multiple coins



---

🧾 License

Licensed under the MIT License.
You’re free to use, modify, and distribute this project with attribution.


---

👨‍💻 Author
Harish Gowda S
📧 harishgowdasuresh@gmail.com
📊 GitHub Profile


---

⭐ If you like this project, don’t forget to give it a star on GitHub! 🌟

---
