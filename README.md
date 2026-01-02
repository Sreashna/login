LOGIN AND REGISTRATION APP (FLUTTER)

This is a simple Flutter application that demonstrates a complete Login and Registration flow. The app includes form validation, state management using Provider, clean navigation, and a simple Material Design user interface.

FEATURES

The application contains two main screens: Login and Registration.

LOGIN SCREEN DESCRIPTION

The login screen allows users to enter their email and password to sign in. It includes a remember me option and a forgot password link for user interface purposes. The screen validates user input and shows error messages when credentials are invalid. Upon successful login, the user is navigated to a Thank You screen.

REGISTRATION SCREEN DESCRIPTION

The registration screen allows new users to create an account by entering their name, email, password, and confirm password. It validates the input fields, checks password match, and allows navigation back to the login screen after successful registration.

AUTHENTICATION LOGIC

The authentication flow is implemented using mock logic with Provider. User credentials entered during registration are stored locally in memory. During login, the entered credentials are validated against the registered data. This structure allows easy replacement with Firebase or API-based authentication in the future.

STATE MANAGEMENT

Provider with ChangeNotifier is used for state management. It handles loading states, error messages, and authentication logic across the application.

USER INTERFACE

The user interface follows light Material Design principles. It uses clean spacing, readable typography, and responsive layouts to ensure a smooth user experience across different screen sizes.

PROJECT STRUCTURE

The project is organized into providers, screens, and reusable widgets. Authentication logic is separated from the UI to keep the code clean and maintainable.

HOW TO RUN THE PROJECT

Ensure Flutter SDK is installed on your system. Navigate to the project directory and run the following commands.

flutter pub get
flutter run
