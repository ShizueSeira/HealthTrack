# HealthTrack - Fitness Tracking App 💪

A comprehensive Flutter-based mobile application designed to help users monitor and improve their fitness lifestyle with workout tracking, food intake logging, BMI calculation, and progress monitoring.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

## 📱 App Preview

| Dashboard | Workout Tracking | BMI Calculator | Food Tracker |
|:---------:|:----------------:|:--------------:|:------------:|
| 🏠 | 🏋️ | 📊 | 🍎 |
| *Main dashboard with all features* | *Exercise routines and tracking* | *BMI calculation and history* | *Food intake logging* |
## ✨ Features

### 🏋️ Workout Management
- **Predefined Workout Categories**: Flexibility, Agility, Strength, Endurance
- **Custom Workout Creation**: Build your own exercise routines
- **Exercise Timer**: Built-in timer for tracking workout duration
- **Completion Tracking**: Log completed workouts with timestamps
- **Workout History**: View past exercise sessions

### 🍎 Nutrition Tracking
- **Food Intake Logger**: Record daily meals and snacks
- **Calorie Tracking**: Monitor calorie consumption
- **Water Intake**: Log daily water consumption
- **Food History**: Review past dietary patterns

### 📊 Health Metrics
- **BMI Calculator**: Calculate Body Mass Index with categories
- **BMI History**: Track BMI changes over time
- **Progress Visualization**: Visual representation of fitness journey
- **Health Insights**: Get feedback on your health metrics

### 🔔 User Experience
- **Personalized Reminders**: Set workout and nutrition alerts
- **User Authentication**: Secure login with Firebase Auth
- **Progress Dashboard**: Centralized view of all fitness data
- **Responsive Design**: Optimized for mobile devices

## 🛠️ Technical Stack

- **Framework**: Flutter (Dart)
- **Backend**: Firebase (Authentication & Firestore)
- **State Management**: Flutter setState
- **Architecture**: Material Design
- **Navigation**: Flutter Navigator

## 📥 Installation

### Prerequisites
- Flutter SDK (>=3.0.0)
- Dart SDK (>=2.17.0)
- Android Studio / VS Code
- Firebase Project

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/HealthTrack.git
   cd HealthTrack

### Install dependencies

flutter run

### Firebase Setup
- Create a new Firebase project
- Enable Authentication (Email/Password)
- Set up Firestore Database
- Download google-services.json and place in android/app/

### Run the application

### 🏗️ Project Structure
lib/
├── main.dart                 # Application entry point
├── screens/
│   ├── login_screen.dart    # User authentication
│   ├── dashboard.dart       # Main dashboard
│   ├── workout_tracker.dart # Exercise management
│   ├── bmi_calculator.dart  # BMI calculation & history
│   ├── food_tracker.dart    # Food intake logging
│   └── profile_screen.dart  # User profile & settings
├── widgets/
│   ├── custom_appbar.dart   # Custom app bar
│   ├── workout_card.dart    # Exercise display
│   └── progress_chart.dart  # Progress visualization
└── services/
    ├── auth_service.dart    # Firebase authentication
    └── database_service.dart # Firestore operations

### 📱 App Demo
**Authentication Flow**
- **Login/Register**: Firebase authentication with email/password
- **Validation**: Form validation and error handling

**Workout Flow**
- Select workout category or create custom workout
- Start exercise with built-in timer
- Complete workout and save to history
- View progress in workout tracker

**Health Tracking**
- **BMI Calculation**: Input weight and height for instant results
- **Food Logging**: Record meals with calorie tracking
- **Progress History**: View historical data and trends

### 👥 Development Team
- **Charles Fredric G. Inventado** - Main Front-end Officer
- **John Vincent B. Rodelas** - Assistant Front-end & Back-end Code Officer
- **James Vincent V. Valles** - Main Back-end Officer

### 📄 Documentation
- Storyboard & Mockups
- Technical Documentation
- Source Code
- APK File

### 🎯 Future Enhancements
- Integration with health APIs (Google Fit, Apple Health)
- Social features and challenges
- Advanced analytics and insights
- Meal planning and recipes
- Wearable device integration
- Multi-language support
- Dark mode theme
