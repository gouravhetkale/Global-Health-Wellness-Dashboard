```
# 🌱 Global Eco-Health Tracker

A Streamlit dashboard that gives instant Health Wellness Index scores 
for every country, with disease risk profiling, infrastructure audits, 
and a 2027 ML-powered forecast using Random Forest.

---

## 🗂️ Project Structure

```
├── health_dashboard.py    # Main Streamlit app
├── train_model.py         # ML model training script
├── requirements.txt       # Python dependencies
└── .gitignore             # Files excluded from Git
```

> `Global Health Statistics.csv` and `health_model.pkl` are not included. 
> The PKL file gets auto-generated when you run the training script.

---

## ⚙️ Setup & Usage

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Add the dataset** — place `Global Health Statistics.csv` in the root folder

3. **Train the model**
   ```bash
   python train_model.py
   ```

4. **Launch the dashboard**
   ```bash
   streamlit run health_dashboard.py
   ```

---

## 🛠️ Tech Stack
Python · Streamlit · Pandas · Scikit-learn · Plotly · Joblib


---

Clean and to the point! Want any section added or removed?
