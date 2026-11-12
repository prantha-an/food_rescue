# 🍱 FoodRescue – Food Waste Reduction & Donation App

### Turning Surplus Food into Hope. Reducing Waste, Sharing Happiness. 🌱

FoodRescue is a Flutter-based food donation application designed to reduce food waste by connecting people who have surplus food with individuals who need it.

The platform allows donors to share available food and receivers to discover and request food donations. It provides a simple and organized way to manage donations, requests, and notifications.

This project was developed as an academic project using Flutter, Dart, and Firebase.

---

## 🎯 Project Overview

Food waste is a significant problem, while many people struggle to access sufficient food.

FoodRescue aims to bridge this gap by creating a digital platform where:

- Donors can share surplus food.
- Receivers can find and request available food.
- Donors can manage incoming requests.
- Users can track donation and request activities.

**Our Mission:** Reduce food waste and make food sharing easier through technology.

---

## ✨ Key Features

### 🔐 Authentication & User Management
- User Registration and Login
- Firebase Email & Password Authentication
- Forgot Password Functionality
- User Profile Management
- Role-Based Access (Donor & Receiver)

### 🍲 Food Donation Management
- Create Food Donations
- Edit and Delete Donations
- Add Food Images
- Set Food Quantity and Expiry Information
- Manage Donation Availability

### 🔎 Food Search & Discovery
- Browse Available Food Donations
- Search by Food Name
- Filter by Food Category
- View Detailed Food Information
- Automatically Hide Expired or Unavailable Donations

### 📦 Request Management
- Send Food Donation Requests
- Accept or Reject Requests
- Cancel Pending Requests
- Complete Food Requests
- Automatic Food Quantity Updates
- Prevent Duplicate Pending Requests

### 🔔 Notification System
- Real-Time In-App Notifications
- New Request Notifications for Donors
- Request Status Notifications for Receivers
- Read and Unread Notification Management
- Delete Notifications

### 📊 Dashboard & Impact Tracker
- Total Donations
- Available Food
- Total Requests
- Accepted and Completed Requests
- Food Saved Statistics
- People Helped Statistics
- Separate Donor and Receiver Dashboards

### 🔒 Security
- Firebase Authentication
- Firestore Security Rules
- Role-Based Data Access
- User-Specific Data Permissions

---

## 🛠️ Technology Stack

| Technology | Usage |
|---|---|
| Flutter | Cross-platform App Development |
| Dart | Programming Language |
| Firebase Authentication | User Authentication |
| Cloud Firestore | Real-Time Database |
| Image Picker | Food Image Selection |
| Material Design | User Interface |

---

## 🏗️ Project Architecture

The project follows a modular structure to keep the code organized and maintainable.

```text
lib/
│
├── models/
│   ├── user_model.dart
│   ├── donation_model.dart
│   ├── request_model.dart
│   └── notification_model.dart
│
├── services/
│   ├── auth_service.dart
│   ├── donation_service.dart
│   ├── request_service.dart
│   └── notification_service.dart
│
├── screens/
│   ├── authentication/
│   ├── home/
│   ├── donation/
│   ├── requests/
│   ├── profile/
│   └── notifications/
│
├── widgets/
│
└── utils/
```

**Architecture Overview:**

- **Models:** Represent application data such as users, donations, requests, and notifications.
- **Services:** Handle Firebase authentication and database operations.
- **Screens:** Contain the application's user interfaces.
- **Widgets:** Provide reusable UI components.
- **Utils:** Store shared constants, colors, and validation logic.

---

## 🔄 How FoodRescue Works

1. A user registers as a Donor or Receiver.
2. A Donor creates a food donation with relevant information.
3. Receivers browse available donations.
4. A Receiver sends a request for available food.
5. The Donor receives an in-app notification.
6. The Donor accepts or rejects the request.
7. Accepted requests update the available food quantity.
8. After completion, the dashboard updates the donation impact statistics.

---

## 🚀 Getting Started

### Prerequisites

Before running the project, make sure you have:

- Flutter SDK
- Dart SDK
- Visual Studio Code or Android Studio
- A Firebase Project

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/prantha-an/food_rescue.git
```

**2. Navigate to the project directory**

```bash
cd food_rescue
```

**3. Install dependencies**

```bash
flutter pub get
```

**4. Configure Firebase**

Connect the application to your own Firebase project and configure Firebase Authentication and Cloud Firestore.

**5. Run the application**

```bash
flutter run
```

---

## 📚 What I Learned

While developing FoodRescue, I gained practical experience in:

- Flutter UI Development
- Dart Programming
- Firebase Authentication
- Cloud Firestore Database Integration
- CRUD Operations
- Asynchronous Programming
- Real-Time Data Handling
- State Management with StatefulWidget and StreamBuilder
- Form Validation using Regular Expressions
- Role-Based Application Logic
- Git and GitHub Version Control

---

## 🔮 Future Improvements

Some features that could be added in future versions:

- Push Notifications
- Google Maps Integration
- Location-Based Food Discovery
- Food Donation Analytics
- More Advanced Impact Tracking

---

## 👨‍💻 Developer

**Nayan Talukder Prantha**

Computer Science & Engineering Student  
Leading University, Bangladesh

**GitHub:** prantha-an

---

## ❤️ Acknowledgement

This project represents my learning journey in Flutter application development and Firebase integration.

I hope FoodRescue can inspire more people to share surplus food and contribute to reducing food waste.

### Let's reduce food waste together! 🌍
