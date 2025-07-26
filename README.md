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

attrition/
├── accounts/ # Authentication logic
├── employee_attrition/ # ML model integration
├── templates/ # HTML templates
├── static/ # CSS, JS, images
├── staticfiles/ # Collected static files for deployment
├── db.sqlite3 # Local database
└── manage.py # Django management script

📊 Machine Learning Model
Developed using Random Forest Classifier

Trained on IBM HR Analytics dataset

Evaluated using accuracy, precision, and confusion matrix
