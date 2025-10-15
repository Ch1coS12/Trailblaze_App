# Trailblaze App

**Trailblaze App** is part of a personal portfolio. This part contains the App version of project, originally inspired by a university prototype.  
It reimagines the **territorial planning and management platform** experience in a **modern, mobile-first Flutter application**, allowing users to visualize, register, and manage land parcels with real-time interaction and photo integration.

---

## ✨ Features

- **Interactive Maps**
  - Visualization of parcels and boundaries using **Google Maps SDK + GeoJSON**
  - Smooth rendering of large geographic datasets
  - Search and filter parcels by attributes

- **Parcel & Photo Management**
  - Create, edit, and track land parcels
  - Attach **single or multiple photos** per parcel
  - Offline-safe photo upload with error handling

- **User Access & Roles**
  - Authentication and secure session control
  - Role-based permissions (Admin / Operator / Viewer)
  - Profile data synchronized with backend API

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

- **Admin** – full access to all parcels and system management
- **Operator** – can create, update, and manage parcels and photos
- **Viewer** – read-only access to geographic data

---

## 💻 Tech Stack

- **Framework**: Flutter (Dart)
- **Backend Integration**: REST API (custom or Firebase)
- **Database / Storage**: Firebase Firestore or Cloud Storage
- **Maps**: Google Maps SDK with GeoJSON overlays
- **State Management**: Provider / Riverpod (depending on configuration)
- **Auth**: Custom authentication layer with role validation

---

## 🧠 Project Goals

This project showcases my work in:
  - **Cross-platform mobile development** (Flutter)
  - **Map-based application design**
  - **Asynchronous data handling and image processing**
  - **Role-based authentication and app architecture**

---

## 📝 License / Notice

This repository reflects a **university coursework project**.  
Code is published for **portfolio purposes**; reuse may be restricted if no explicit license is defined.
