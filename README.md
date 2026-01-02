🔐 Login & Registration App (Flutter)

A simple Flutter application implementing Login and Registration flow with form validation, state management using Provider, and clean Material UI.

✨ Features
Login Screen

Email input

Password input (show / hide)

Remember Me checkbox

Forgot Password (UI only)

Navigation to Register screen

Validation & error handling

Success navigation to Thank You screen

Registration Screen

Name input

Email input

Password input

Confirm Password input

Password match validation

Back to Login navigation

Authentication

Mock authentication using Provider

Registered credentials are stored locally (in-memory)

Login validates against registered credentials

🧠 State Management

Provider (ChangeNotifier)

Handles:

Loading state

Error messages

Authentication logic

🎨 UI

Light, modern Material Design

Clean spacing and readable typography

Responsive layout

User-friendly form validation messages

📂 Project Structure
lib/
├── main.dart
├── provider/
│   └── auth_provider.dart
├── screens/
│   ├── login_screen.dart
│   ├── registration_screen.dart
│   └── thank_you_screen.dart
└── widget/
    └── auth_widget.dart

🚀 How to Run
flutter pub get
flutter run
