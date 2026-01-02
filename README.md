LOGIN & REGISTRATION APP (FLUTTER)

A clean and modern Flutter application demonstrating a complete Login and Registration flow with form validation, Provider-based state management, and Material UI.

FEATURES

LOGIN SCREEN

Email input field

Password input field with show / hide option

Remember Me checkbox

Forgot Password (UI only)

Navigation to Registration screen

Validation and error handling

Successful login navigates to a Thank You screen

REGISTRATION SCREEN

Name input field

Email input field

Password input field

Confirm Password input field

Password match validation

Navigation back to Login screen

AUTHENTICATION

Mock authentication using Provider

Registered credentials stored locally (in-memory)

Login validates against registered credentials

STATE MANAGEMENT

Provider (ChangeNotifier)

Handles:

Loading state

Error messages

Authentication logic

UI AND UX

Light, modern Material Design

Clean spacing and readable typography

Responsive layout

User-friendly validation messages

PROJECT STRUCTURE

lib/

main.dart

provider/

auth_provider.dart

screens/

login_screen.dart

registration_screen.dart

thank_you_screen.dart

widget/

auth_widget.dart

GETTING STARTED

Install Flutter SDK

Run the following commands:

flutter pub get
flutter run
