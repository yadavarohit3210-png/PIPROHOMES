# PIPROHOMES Flutter App

## Project Description
PIPROHOMES is a versatile Flutter application that allows users to find and manage properties efficiently. The app offers a seamless user experience with extensive features tailored for both buyers and sellers in the real estate market.

## Features
- User authentication and profile management.
- Search and filter properties based on multiple criteria.
- Property details with images and descriptions.
- Secure messaging between buyers and sellers.
- Favorites list for saved properties.
- Map integration for location tracking.

## Tech Stack
- **Frontend:** Flutter
- **Backend:** Firebase
- **Database:** Firestore
- **State Management:** Provider
- **Deployment:** Firebase Hosting

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yadavarohit3210-png/PIPROHOMES.git
   cd PIPROHOMES
   ```
2. Install Flutter on your machine if not already installed.
3. Open the project in your preferred IDE (e.g., Android Studio, Visual Studio Code).
4. Run the following command to get the dependencies:
   ```bash
   flutter pub get
   ```
5. Configure Firebase for your project and replace the `google-services.json` file (for Android) or `GoogleService-Info.plist` (for iOS) accordingly.
6. Run the application:
   ```bash
   flutter run
   ```

## Deployment Guide
1. Make sure your Flutter app is ready for production.
2. Run the command to build your app:
   ```bash
   flutter build web
   ```
3. Deploy to Firebase Hosting:
   ```bash
   firebase deploy
   ```

Ensure you have set up Firebase CLI and authenticated your Firebase project before deploying.