# 🔬Molecular Deconstruction of Immortal Pollutants (Breaking down PFAS and Fluorine Recovery) 

This project focuses on developing a multi-stage system to analyze, deconstruct, and recover fluorine from PFAS (Per- and Polyfluoroalkyl Substances) — commonly known as "forever chemicals" — which are resistant to natural degradation and pose significant environmental threats.

## 📌 Objective

To build a structured and interactive platform that:

- Analyzes materials containing PFAS.
- Calculates decomposition energy and recovery efficiency.
- Predicts purified fluorine percentage using a DecisionTreeRegressor machine learning model.
- Generates comprehensive reports at each stage for validation and sustainability analysis.

---

## 🚀 Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: Python, Django
- Database: MySQL
- Machine Learning: scikit-learn (Decision Tree Regressor)
- IDE: PyCharm

---

## 🧠 System Modules

1. Admin Panel  
   Uploads requirements, manages registrations, and validates reports.

2. Fluroscan 
   Calculates % of PFAS and fluorine from input materials.

3. Decompoenergy  
   Computes moles of C-F bonds and required energy for breakdown.

4. Fluroreclaim  
   Analyzes recovery efficiency and recovered fluorine amount.

5. Purecheck  
   Applies `DecisionTreeRegressor` to predict the final purified fluorine percentage.

---

## 🔎 Sample Workflow

1. Admin uploads analysis parameters.
2. Teams register and are approved by the admin.
3. Each module performs respective calculations and forwards data to the next.
4. Final prediction report is generated and validated.

---

## 📊 Machine Learning Model

- Algorithm Used: Decision Tree Regressor
- Purpose: To predict the purification percentage of recovered fluorine based on computed parameters such as decomposition energy, initial PFAS %, and recovery efficiency.


## 📁 Folder Structure

project-root/
│
├── admins/ # Admin logic and views
├── fluroscan/ # Fluroscan module (PFAS & fluorine analysis)
├── decompoenergy/ # Decomposition analysis
├── fluroreclaim/ # Recovery logic
├── purecheck/ # Purification prediction using ML
├── templates/ # HTML templates
├── static/ # CSS/JS/Images
├── db.sqlite3 # (Or MySQL setup)
├── manage.py # Django project manager
└── README.md # You're here!

---

## 📌 How to Run the Project

1. Clone the repository.
2. Set up a virtual environment:
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   
3.Install dependencies:
pip install -r requirements.txt

4.Set up MySQL database or use SQLite for testing.

5.Run the Django server:
python manage.py runserver

📚 Future Enhancements
Adding support for more machine learning models for comparison.

Implement better real-time analytics dashboards.

Integrate with environmental sensors for automatic data input.
