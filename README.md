Flutter Firebase Authentication App

Overview

This is a Flutter application that provides authentication and registration functionality using Firebase. Users can sign up, log in, and manage their authentication status using Firebase Authentication.

Features

User Registration (Sign Up)

User Login (Sign In)

Firebase Authentication Integration

Logout Functionality


Tech Stack

Framework: Flutter

Backend: Firebase Authentication

Repository

GitHub Repository: Flutter-Firebase-Auth

Setup Instructions

Prerequisites

Install Flutter: Flutter Installation Guide

Set up Firebase project: Firebase Console

Enable Firebase Authentication (Email/Password Sign-In)

Configure google-services.json (Android) and GoogleService-Info.plist (iOS)

Clone Repository

  git clone https://github.com/KJain-08/Flutter-Firebase-Auth.git
  cd Flutter-Firebase-Auth

Install Dependencies

  flutter pub get

Configure Firebase in Flutter

Add Firebase dependencies to pubspec.yaml:

dependencies:
  firebase_core: latest_version
  firebase_auth: latest_version

Run the following command to ensure Firebase is correctly initialized:

  flutterfire configure

Run the Application

  flutter run

Project Structure

lib/
|-- main.dart
|-- auth/
|   |-- login_screen.dart
|   |-- register_screen.dart
|   |-- auth_service.dart
|-- screens/
|   |-- home_screen.dart
|-- widgets/
|   |-- custom_button.dart

Firebase Configuration

Ensure that you have added the Firebase project configuration files:

Android: Place google-services.json in android/app/

iOS: Place GoogleService-Info.plist in ios/Runner/

Contributing

Fork the repository

Create a new branch (feature-branch)

Commit changes

Push to the branch

Open a pull request

License

This project is licensed under the MIT License.
