# kcapTrack-fittness-tracker-with-food-analysis

🥗 AI-Powered Health & Food Tracking App
📌 Overview

This project is a full-stack AI-powered health tracking application that helps users monitor their diet, health metrics, and daily activities. It uses food analysis, health calculations, and tracking modules to provide personalized insights and recommendations.

🚀 Features

👤 User Profile Management – Register and store personal details (age, weight, height, gender, goals).

❤️ Health Metrics Calculation – Calculates BMI, AMR, calorie requirements based on user profile.

🍲 Food Analysis – AI-powered food recognition & nutritional breakdown.

📊 Daily Tracker – Track daily food intake, calories consumed, and exercises performed.

🔒 Authentication System – Secure login and user authentication.

💾 Database Integration – Store user data, food logs, and progress history.

📈 Progress Dashboard – Visualize calories consumed vs burned, weight management goals.

📂 Project Structure
.
├── 1_User_Profile.py        # Manage user profiles
├── 2_Health_Metrics.py      # Calculate BMI, AMR, calorie needs
├── 3_Food_Analysis.py       # Food recognition & nutrition analysis
├── 4_Daily_Tracker.py       # Daily food & activity tracking
├── app.py                   # Main application entry point
├── authentication.py        # User authentication logic
├── database.py              # Database connection & models
├── food_analysis.py         # Extra utilities for food analysis
├── health_calculations.py   # Helper functions for health metrics
├── pyproject.toml           # Project dependencies & build system
├── README.md                # Project documentation
└── generated-icon.png       # App icon/logo

🛠️ Tech Stack

Python (FastAPI / Flask / Streamlit – depending on setup)

PostgreSQL / SQLite for database

Pandas & NumPy for calculations

OpenCV / ML Model for food detection (optional AI extension)

Matplotlib / Plotly for visualizations

⚡ Installation & Setup

Clone this repository:

git clone https://github.com/yourusername/health-tracker-app.git
cd health-tracker-app


Create and activate virtual environment:

python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows


Install dependencies:

pip install -r requirements.txt


Run the application:

python app.py

📊 Future Enhancements

🔗 Integration with wearable devices (Fitbit, Apple Watch).

📱 Mobile app interface (React Native / Flutter).

🤖 AI-powered meal recommendations based on user goals.

🌍 Cloud deployment with Docker & Kubernetes.

🙌 Contributors

Deepesh Manju – AI/ML Aspirant & Developer
