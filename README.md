# Hospital Appointment System

A simple Flutter application for managing hospital appointments. This application allows users to view available doctors, their details, and book appointments.

## Features

- View list of available doctors
- View detailed information about each doctor
- Book appointments with selected doctors
- Simple and intuitive user interface

## Requirements

- Flutter SDK (latest version)
- Dart SDK (latest version)
- Android Studio / VS Code with Flutter extensions

## Getting Started

1. Clone this repository
2. Navigate to the project directory:
   ```
   cd hospital_appointment_system
   ```
3. Install dependencies:
   ```
   flutter pub get
   ```
4. Run the application:
   ```
   flutter run
   ```

## Project Structure

- `lib/models/` - Contains data models (Doctor, Appointment)
- `lib/screens/` - Contains all the screens of the application
  - `home_screen.dart` - Main screen showing list of doctors
  - `doctor_details_screen.dart` - Screen showing doctor details
  - `book_appointment_screen.dart` - Screen for booking appointments
- `lib/main.dart` - Application entry point and route configuration

## Note

This is a simple implementation without any backend integration. The data is hardcoded for demonstration purposes. In a real application, you would want to:

1. Add proper data persistence
2. Implement user authentication
3. Add a backend server
4. Add proper error handling
5. Implement appointment validation
6. Add email/SMS notifications
