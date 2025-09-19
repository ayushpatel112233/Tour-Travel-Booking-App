# Indian Tour & Travel Booking App

A full-featured Flutter app for booking tours and travels in India, with:
- User and Admin dashboards
- Firebase backend integration
- Full project structure: models, services, screens, utils

## Features
- Browse and book tour packages
- User authentication (Firebase)
- Admin dashboard for managing packages and bookings
- Responsive UI for mobile and web

## Structure

- **models/**: Data models (TourPackage, User, Booking)
- **providers/**: State providers (Auth, Package, Booking, User)
- **services/**: Business logic and Firebase interaction
- **screens/**: UI screens (Splash, Login, Home, Details, Booking, Admin Dashboard)
- **utils/**: Theme, constants

## Firebase Setup
1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
2. Add Android/iOS/Web apps and download `google-services.json` & `GoogleService-Info.plist`
3. Replace `firebase_options.dart` with your actual configuration using FlutterFire CLI

## Getting Started

```bash
flutter pub get
flutter run
```

## Contribution

Feel free to open issues or submit PRs for improvements!
