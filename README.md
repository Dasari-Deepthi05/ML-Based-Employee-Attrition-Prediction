# AttriTrack🔍  
*A Machine Learning–Powered Employee Attrition Prediction System*

AttriSight is a web-based platform designed to help organizations predict employee attrition using a machine learning model integrated with a Django backend. The system enables HR teams to make proactive decisions by identifying at-risk employees.

---

## 🚀 Features

- Employee attrition prediction based on input data  
- Secure user authentication (login & registration)  
- Intuitive interface with visualized results  
- Integrated ML model with Jupyter Notebook

---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python, Django  
- **Database:** SQLite (default), PostgreSQL (recommended)  
- **Machine Learning:** Jupyter Notebook (scikit-learn, pandas)

---

## 📁 Project Structure Overview

```bash
attrition/
├── accounts/                    # User authentication (login, register)
│   ├── migrations/              # Django migration files
│   ├── __init__.py
│   ├── admin.py                 # Admin panel setup
│   ├── apps.py                  # App configuration
│   ├── forms.py                 # Custom user forms
│   ├── models.py                # User models
│   ├── tests.py                 # Unit tests
│   ├── urls.py                  # Routes for accounts
│   └── views.py                 # Logic for login/register
│
├── attrition/                   # Main Django project config (settings, urls, wsgi)
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── employee_attrition/          # ML model logic and integration
│   ├── Attrition_Model.ipynb    # Jupyter Notebook for training and evaluation
│   └── predict.py               # Python script for inference
│
├── static/                      # Static assets (CSS, JS, images)
│   └── css/
│   └── js/
│   └── images/
│
├── staticfiles/                 # Collected static files (for deployment)
│
├── templates/                   # HTML templates for frontend pages
│   ├── base.html
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── predict.html
│   ├── about.html
│   ├── project.html
│   └── service.html
│
├── db.sqlite3                   # Default SQLite database (can switch to PostgreSQL)
├── manage.py                    # Django command-line utility
└── requirements.txt             # Python dependencies
```

📊 Machine Learning Model
Developed using Random Forest Classifier

Trained on IBM HR Analytics dataset

Evaluated using accuracy, precision, and confusion matrix

📤 Output

🧠 Prediction Logic – Based on user-input employee data, the system predicts if the employee is likely to stay or leave.
📊 Result Display – Output is shown on the prediction page with clear labels and optional visual indicators like colors or charts.
