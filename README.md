# ​ Online Doctor Appointment App 

A Flutter-based application integrated with **Firebase**, designed for patients to browse doctors, schedule appointments, and for admins to manage bookings and doctors—all in real time through a clean, responsive UI.

---
##  Screenshot

![App Screenshot](https://github.com/MuhammadSaimArshad/Online-Doctor-Appointment-App/blob/15426c79d673a65a0207a27609e618c7e4d87d52/onlinedoctorapp.png)

---

##  Features

### Patient Frontend
- **Doctor Directory**: Browse doctors by specialty, rating, or availability.  
- **Appointment Booking**: Select date and time slots, confirm bookings with real-time updates from Firestore.  
- **User Authentication**: Sign up and log in using Firebase Auth.  
- **Responsive UI**: Ensures seamless experience across smartphones and tablets.

### Admin Dashboard
- **Manage Doctors**: Add, edit, or remove doctor profiles and availability.  
- **View Appointments**: Track and manage current and upcoming patient appointments.  
- **Real-Time Sync**: Admin and user interfaces stay in sync via Firebase Realtime Database or Firestore.

---



##  Tech Stack
- **Flutter** – Frontend development  
- **Dart** – Core programming language  
- **Firebase** – Backend services including:  
  - **Firebase Authentication** – User login/sign-up  
  - **Cloud Firestore** – Data storage & real-time updates  
  - **Firebase Realtime Database** or **Firestore** – For live admin/patient synchronization  
  - **Optional**: Firebase Hosting & Cloud Functions for advanced deployment and backend logic

---

##  Setup & Installation

```bash
# Clone the repository
git clone https://github.com/MuhammadSaimArshad/Online-Doctor-Appointment-App.git

# Navigate to project directory
cd Online-Doctor-Appointment-App

# Install dependencies
flutter pub get

# Launch the app (ensure emulator or device is connected)
flutter run
