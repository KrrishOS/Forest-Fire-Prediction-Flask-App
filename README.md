# Forest Fire Prediction Flask App

A simple end-to-end machine learning project that predicts the Fire Weather Index (FWI) using weather and vegetation-related parameters from the Algerian Forest Fires dataset.

## Built With

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy

## Project Structure

forest-fire-prediction/
│
├── models/
├── notebooks/
├── templates/
├── application.py
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE

## Run Locally

```bash
git clone <repo-url>
cd forest-fire-prediction

python -m venv .venv
source .venv/bin/activate      # Linux/macOS
# .venv\Scripts\activate       # Windows

pip install -r requirements.txt
python application.py
```

Visit:

```
http://127.0.0.1:5000
```

## Model

- Ridge Regression
- StandardScaler

## Dataset

Algerian Forest Fires Dataset

---

A small project built to understand the complete workflow—from data preprocessing and model training to deploying a machine learning model with Flask.
