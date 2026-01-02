🔐 Login & Registration App (Flutter)

A clean and modern Flutter application that demonstrates a complete Login and Registration flow with form validation, Provider-based state management, and a user-friendly Material Design UI.

✨ Features
🔑 Login Screen

Email input field

Password input field with show / hide option

Remember Me checkbox

Forgot Password link (UI only)

Navigation to Registration screen

Input validation with error messages

Successful login navigates to a Thank You screen

📝 Registration Screen

Name input field

Email input field

Password input field

Confirm Password input field

Password match validation

Navigation back to Login screen

🔐 Authentication

Mock authentication implemented using Provider

Registered user credentials are stored locally (in-memory)

Login validates user credentials against registered data

This structure allows easy replacement with Firebase or API-based authentication in the future.

🧠 State Management

Provider (ChangeNotifier)

Manages:

Loading state

Error messages

Authentication logic

🎨 UI & UX

Light, modern Material Design

Clean spacing and readable typography

Responsive layout for different screen sizes

User-friendly form validation feedback

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

🚀 Getting Started
Prerequisites

Flutter SDK installed

Android Studio / VS Code

Run the App
flutter pub get
flutter run
