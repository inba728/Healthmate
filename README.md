# 🏥 HealthMate

**HealthMate** is a Flask-based smart health assistant that helps users predict diseases based on symptoms, manage medicine reminders with alarms, track BMI, monitor medicine expiry, visualize health history, and generate downloadable health reports.

---

## 🚀 Features

- ✅ **Symptom-based Disease Prediction** using Machine Learning
- ⏰ **Medicine Reminder System** with alarm and email alerts
- 📅 **Medicine Expiry Tracker** with 5-day early warning
- 📊 **Symptom History Charts** using Chart.js
- 🧮 **BMI Calculator** for health monitoring
- 📁 **Download Health Report** as PDF
- 👤 **User Profile** with image/avatar upload
- 📋 **Modern Dashboard UI** with clean, responsive design

---

## 💻 Technologies Used

- **Frontend**: HTML, CSS, JavaScript (Chart.js)
- **Backend**: Python (Flask), APScheduler
- **Database**: MySQL
- **Machine Learning**: Scikit-learn
- **Other Tools**: xhtml2pdf (for PDF generation), smtplib (email), threading

---


---

## 🛠️ Setup Instructions

### 1. Clone the Repository
git clone https://github.com/your-username/HealthMate.git
cd HealthMate


### 2. Create Virtual Environment and Install Dependencies
python -m venv venv
venv\Scripts\activate  # On Windows
pip install -r requirements.txt


### 3. Set Up MySQL Database
Create a MySQL database (e.g. healthmate)
Import schema.sql if available
Update app.py with your DB credentials


### 4. Run the Flask App
python app.py
Visit http://localhost:5001 in your browser.

## 📬 Contact

If you have any questions, feedback, or suggestions, feel free to reach out:

- 📧 Email: inba728@gmail.com

