# Skill-Based Learning & Tracking Platform  
**Hackathon Project – Nirman, February 2024**

This project is a skill-oriented e-learning platform with user activity tracking and admin analytics, built using Python (Flask), MongoDB, and integrated with YouTube for content delivery. Developed during the Nirman 2024 Hackathon, it enables users to explore curated learning paths and provides the admin with insightful analytics.

---

## 🧠 Features

- User authentication (Signup, Login, Password Reset, Role-based access)
- Embedded skill-based YouTube learning content (e.g., Web Design, Web Development, Healthcare)
- Real-time user activity logging with MongoDB
- Admin dashboard with detailed analytics and visualizations (time spent, page visits, etc.)
- Dynamic charts (bar, pie, histogram, boxplot) generated using Matplotlib and Seaborn
- Secure session handling and role protection for admin access

---

## 🔧 Tech Stack

- **Frontend:** HTML, CSS, Jinja2 Templates
- **Backend:** Flask (Python), RESTful Routes
- **Database:** MongoDB (with collections: `users`, `user_activity`, `skill_video`, etc.)
- **Data Visualization:** Matplotlib, Seaborn, Pandas
- **API Integration:** YouTube Data API, BeautifulSoup for metadata extraction

---

## 📁 Project Structure

- `main.py` – Core backend logic with all routes and data handling
- `users.csv` – Sample dataset for testing or population
- `analysis.ipynb` – Jupyter notebook for data analysis/visualization (admin insights)
- `templates/` – HTML templates for login, signup, dashboard, etc.
- `static/` – CSS, JS, and static files (not uploaded here)

---

## 🚀 How to Run

### 1. Clone the repository

### 2. Install required packages
pip install -r requirements.txt

### 3.Run the Flask app
python main.py (Access the app at: http://localhost:5000)
