# 📌 FitnessPro - Gym Management System

**FitnessPro** is a comprehensive, web-based Gym Management System designed to streamline fitness center operations. It provides a seamless interface for administrators to manage memberships and staff, trainers to curate personalized fitness journeys, and members to track their progress, diets, and workouts.

---

## ✨ Features

* **Member Lifecycle Management**: User registration with payment proof upload and admin-controlled approval process.
* **Role-Based Dashboards**:
* **Admin**: Manage trainer attendance, approve memberships, assign trainers, and view financial analytics/revenue charts.
* **Trainer**: Create and manage custom workout and diet plans, and oversee assigned clients.
* **Member**: Access personalized workout/diet plans, calculate BMI, and request personal training.


* **Dynamic Workout & Diet Plans**: Trainers can build 7-day schedules with specific exercises and meal details for their clients.
* **Automated Membership Tracking**: System automatically blocks expired memberships and handles renewal reminders.
* **Real-time Analytics**: Visual progress charts for admin to monitor member growth and revenue trends.
* **Gym Info Management**: Admin can update gym contact details and operating hours dynamically.

---

## 🛠️ Tech Stack

* **Backend**: Python / Django
* **Frontend**: HTML5, CSS3 (Custom Variables & Gradients), JavaScript
* **UI Framework**: Bootstrap 5.3 & FontAwesome 6.5
* **Database**: SQLite (Default Django ORM)
* **Animations**: AOS (Animate on Scroll)
* **Data Visualization**: Chart.js (via JSON data injection)

---

## 📁 Folder Structure

```text
fitnesspro-root/
├── fitnesspro/           # Project configuration
├── gym/                  # Main application logic
│   ├── models.py         # Gym_user, Trainer, WorkoutPlan, etc.
│   ├── views.py          # Core logic (Auth, Dashboards, CRUD)
│   ├── forms.py          # GymInfoForm and user inputs
│   ├── templates/        # HTML templates (Admin, Trainer, User)
│   │   ├── admin/
│   │   ├── trainer/
│   │   └── base.html
│   └── static/           # CSS, Images, and JS files
├── manage.py
└── requirements.txt

```

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/FAHAD-ALI-github/fitnesspro.git

# Navigate into the project directory
cd fitnesspro

# Install dependencies
pip install -r requirements.txt

# Apply database migrations
python manage.py migrate

# Create a superuser (Optional for Django Admin)
python manage.py createsuperuser

# Run the development server
python manage.py runserver

```

---

## 🌐 Live Demo

[🔗 Live Site](https://fitnesspro.pythonanywhere.com/)

---

## 👤 Author

**Fahad Ali** GitHub: [@FAHAD-ALI-github](https://github.com/FAHAD-ALI-github)

LinkedIn: [fahadali1078](https://www.linkedin.com/in/fahadali1078/)
