# Flutter Login UI

This project is a simple Flutter login application built as part of my internship (Week 1 task).

## 📱 Features
- Login screen with:
  - Email field with validation
  - Password field with validation
  - Show/Hide password functionality
- Form validation:
  - Email must not be empty and must contain '@'
  - Password must be at least 6 characters
- Navigation to Home Screen on successful login
- "Forgot Password?" text UI

## 🛠️ Tech Stack
- Flutter
- Dart

## 📂 Project Structure
- `login_screen.dart` → Handles UI, validation, and navigation
- `home_screen.dart` → Destination screen after login
- `main.dart` → App entry point

## 🚀 How It Works
1. User enters email and password
2. Form validation runs:
   - Checks if email is valid
   - Checks password length
3. If valid:
   - Navigates to Home Screen using `Navigator.push()`

## 🚀 How to Run
1. Clone the repository
2. Run:

## 👨‍💻 Author
Faraz Sarwar