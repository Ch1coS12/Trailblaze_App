# Trailblaze App

**Trailblaze App** is part of a personal portfolio. This repository hosts the mobile version of the project, originally inspired by a university prototype.  
It brings the **territorial planning and management platform** to life as a **modern, mobile-first Flutter application**, enabling users to visualize, register, and manage land parcels with real-time interaction and integrated photos.

---

## ✨ Features

- **Interactive Maps**
  - Display parcels and boundaries using **Google Maps SDK + GeoJSON**
  - Smooth rendering of extensive geographic datasets
  - Filter and search parcels by specific attributes

- **Parcel & Photo Management**
  - Create, update, and track land parcels
  - Attach **single or multiple photos** to each parcel
  - Photos are uploaded directly via the backend API

- **User Access & Roles**
  - Secure authentication and session management
  - Role-based permissions (Admin / Operator / Viewer)
  - Profile information synchronized with backend API

- **Cross-Platform Support**
  - Built with **Flutter** for Android, iOS, and Web
  - Consistent UI design and responsive layout

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (version 3.0+)
- Dart SDK
- Android Studio or VS Code
- (Optional) Firebase CLI or backend API endpoint

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Ch1coS12/Trailblaze_App.git
cd Trailblaze_App
```
2. Install dependencies:
```bash
flutter pub get
```
4. Run locally (Android, iOS, or Web):
```bash
flutter run
```
5. (Optional) Build for production:
```bash
flutter build apk      # Android
flutter build ios      # iOS
flutter build web      # Web
```

---

## 👥 User Roles

- **Admin** – full access to all parcels and system operations
- **Operator** – can create, update, and manage parcels and photos
- **Viewer** – read-only access to maps and data

---

## 💻 Tech Stack

- **Framework**: Flutter (Dart)
- **Backend Integration**: REST API (custom or Firebase)
- **Database / Storage**: Firebase Firestore or Cloud Storage
- **Maps**: Google Maps SDK with GeoJSON overlays
- **State Management**: Provider / Riverpod (depending on configuration)
- **Auth**: Custom authentication layer with role validation

---

## 🧠 Project Highlights

This project demonstrates skills in:
  - **Cross-platform mobile development** (Flutter)
  - **Map-based application design**
  - **Asynchronous data handling and image processing**
  - **Role-based authentication and app architecture**

---

## 📝 License / Notice

This repository originates from a university coursework project. It is published for portfolio purposes, and reuse may be limited if no explicit license is specified.
