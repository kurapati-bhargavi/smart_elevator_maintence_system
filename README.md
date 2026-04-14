# smart_elevator_maintence_system
it is fully implemented using jupyternotebook and python lanuguage
# 🚀 Elevator Predictive Maintenance System

## 📌 Project Overview
This project focuses on predicting elevator failures using Machine Learning and forecasting elevator usage using Time Series analysis.

The system helps in proactive maintenance by identifying potential failures before they occur.

---

## 🎯 Objectives
- Predict elevator failures using operational data
- Handle imbalanced datasets using SMOTE
- Forecast future elevator usage using ARIMA
- Predict future failure risks

---

## 📊 Dataset Features
- `floor_trips` → Number of trips made by elevator
- `load_kg` → Load inside the elevator
- `temperature_C` → Machine temperature
- `humidity_%` → Environmental humidity
- `error` → Failure occurrence (0 = No, 1 = Yes)

---

## 🧠 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Random Forest)
- SMOTE (Imbalanced Data Handling)
- ARIMA (Time Series Forecasting)

---

## ⚙️ Model Workflow
1. Data preprocessing
2. Feature engineering
3. ARIMA model for forecasting elevator usage
4. SMOTE for balancing dataset
5. Random Forest for failure prediction
6. Evaluation using accuracy, recall, and confusion matrix

---

## 📈 Key Results
- Improved failure detection using SMOTE
- Achieved better recall for minority class
- Successfully forecasted future elevator usage

---

## 🔮 Future Enhancements
- Real-time sensor integration
- Streamlit dashboard for visualization
- Multiple elevator prediction system
- Deployment using cloud platforms

---

## 📁 Project Structure
