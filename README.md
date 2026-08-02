
# AI Powered Mental Health Monitoring Application

## 📖 Overview
This project is a **Flutter-based healthcare and mental health monitoring system**. It combines **AI-driven mental health detection** with **telemedicine features** such as video consultations, appointment scheduling, and role-based dashboards for doctors, patients, receptionists, and administrators.

---

## 🚀 Features
- **AI mental health monitoring** using Python-trained models integrated with Flutter  
- **Role-based dashboards** for Admin, Doctor, Patient, and Receptionist  
- **Video consultations** powered by Jitsi Meet integration  
- **Appointment management** including booking, reminders, and tracking  
- **Security settings** for account and data protection  
- **Real-time Firebase integration** for authentication and data storage  

---

## 🛠️ Tech Stack
- **Flutter** — mobile app development  
- **Dart** — core application logic and UI  
- **Firebase** — authentication, cloud storage, and real-time database  
- **Python** — AI model training and backend processing  

---

## 📂 Project Structure
```
AI-Mental-Health-App/
│
├── Admin/
│   ├── admin_dashboard_screen.dart
│   ├── manageAccountsScreen.dart
│   └── securitySettingsScreen.dart
│
├── Doctor/
│   ├── doctor_dashboard_screen.dart
│   ├── doctor_appointments_screen.dart
│   ├── doctor_consultation_screen.dart
│   └── doctor_patient_recommendations_screen.dart
│
├── Patient/
│   ├── patient_dashboard_screen.dart
│   ├── patient_reports_screen.dart
│   ├── appointment_booking_screen.dart
│   ├── assessment_screen.dart
│   └── consultation_screen.dart
│
├── Receptionist/
│   ├── receptionist_dashboard_screen.dart
│   ├── accept_appointments_screen.dart
│   ├── set_appointment_reminders_screen.dart
│   └── view_booked_appointments_screen.dart
│
├── widgets/
│   ├── mental_health_scale_widget.dart
│   └── jitsiMeetWidget.dart
│
├── common.dart
├── login_screen.dart
├── signup_screen.dart
├── role_selection_screen.dart
├── video_call_screen.dart
└── welcome_screen.dart
```

---

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/AI-Mental-Health-App.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AI-Mental-Health-App
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Configure Firebase:
   - Add your `google-services.json` (Android) and `GoogleService-Info.plist` (iOS).  

---

## ▶️ Usage
- **Admin**: Manage accounts, security settings, and system-wide configurations.  
- **Doctor**: View appointments, conduct consultations, and provide patient recommendations.  
- **Patient**: Book appointments, track progress, and access mental health assessments.  
- **Receptionist**: Manage schedules, accept appointments, and send reminders.  
- **Video Calls**: Use Jitsi Meet integration for secure telemedicine sessions.  

---

## 📊 Future Improvements
- **Wearable integration** for biometric monitoring  
- **Expanded AI detection** beyond stress, anxiety, and depression  
- **Analytics dashboard** for administrators  

---

Would you like me to also add a **Contribution Guide** (for developers who want to extend the project) or keep the README focused on **usage and features** for now?
