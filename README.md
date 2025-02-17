# Student Wellness Dashboard
### Overview <br/>
The Student Wellness Dashboard is a predictive system designed to monitor and assess student stress levels based on psychological, physiological, and environmental factors. Using machine learning models and an interactive dashboard, the system provides insights, alerts, and recommendations to promote student well-being.
<br/>
<div align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/19910087-1d5c-4310-8d5e-8600b3b89d9c" />
</div>
<br/>
![image]()

### 🚀 Features
- Stress Prediction: Utilizes machine learning (Random Forest) to analyze student stress levels based on various factors.
- Interactive Dashboard: Provides real-time data visualization of stress trends, triggers, and personalized recommendations.
- Notification System: Alerts students and parents when stress levels are critically high.
- Wellness Recommendations: Offers suggestions like mindfulness exercises, physical activities, and screen time management.
- Explainable AI (XAI): Uses SHAP analysis to interpret the most influential features impacting stress.
- Gamification: Encourages engagement through achievements and wellness tracking.

### 🛠 Methodology
- Dataset: The Kaggle Student Stress Dataset containing 20+ features grouped into:
  - Psychological (e.g., anxiety_level, mental_health_history)
  - Physiological (e.g., blood_pressure, sleep_quality)
  - Environmental (e.g., noise_level, living_conditions)
  - Academic (e.g., study_load, future_career_concerns)
  - Social (e.g., peer_pressure, social_support)

- Machine Learning Models:
  - Feature selection using ANOVA & Chi-Square Test.
  - Stress prediction using Decision Tree and Random Forest Regressor (R² = 0.82).
  - SHAP Analysis: Identifies key factors influencing stress levels.

- System Components
  - Sensors (Future Scope): Blood pressure monitors, PIR motion sensors, and emotion recognition via cameras.
  - Database: SQLite3 for storing real-time stress data.
  - Dashboard: Displays monthly stress trends, productivity insights, and stress triggers.

### 🎯 Use Cases
- Students: Monitor stress levels before exams, presentations, and daily routines.
- Parents: Get insights into student well-being and establish healthier habits.
- Educators (Future Scope): View anonymized student stress trends for proactive intervention.

### 🔮 Challenges & Future Scope
- Sensor Integration: Expanding real-time monitoring using wearables and environmental sensors.
- Personalized AI Recommendations: Stress history-based suggestions.
- Mobile Application: Extending accessibility beyond web platforms.
- Teacher Dashboard: Institutional-level intervention planning.
