# Flutter Local Notifications Demo

This is a demo project that showcases the usage of the `flutter_local_notifications` package to display local notifications in a Flutter application.

## Prerequisites

Before running this demo, make sure you have the following prerequisites:

- Flutter SDK (version 3.10.1 or higher)
- Dart SDK (version 3.0.1 or higher)
- Android Studio or VS Code with Flutter extensions installed

## Installation

Follow the steps below to run the demo:

1. Clone the repository:
   ```bash
   git clone https://github.com/tuanvo2908t/flutter_local_notifications_demo.git
2. Navigate to the project directory:
   ```bash
   cd flutter_local_notifications_demo
3. flutter pub get
   ```bash
   flutter pub get
4. Run the app:
   ```bash
   flutter run
   
## Usage
1. Launch the app on your device/emulator.
2. Grant the necessary permissions for notifications when prompted.


## Code Explanation

This demo project consists of the following key files and directories:

- `main.dart`: The main entry point of the Flutter application. It sets up the app and defines the `MyApp` widget.
- `home_page.dart`: The home page of the app, which displays a simple UI with a button to schedule a notification.
- `Services/notifi_service.dart`: A helper class that encapsulates the logic for displaying local notifications using the `flutter_local_notifications` package.


The `notifi_service.dart` file is the main component responsible for handling local notifications. It utilizes the `flutter_local_notifications` package to display notifications. The key methods in this file include:

- `AndroidInitializationSettings `: Initialize configuration for Android platform.
- `initializationSettingsIOS `: Initialize configuration for iOS platform.
- `initializationSettings `: Create a global initialization configuration.
- `notificationDetails()`: Define detailed configuration for notifications.
- `showNotification()`: Show notification.

The `home_page.dart` file defines the UI of the home screen. It provides a button that, when tapped, triggers a local notification.


