# Todo

**Todo** - A simple task management app for Android.

## Details

Todo is a basic task manager app built using **Kotlin**, structured with **MVVM / Clean Architecture**. The app uses **Fragments** and integrates **Firebase** for backend services (Authentication & Firestore). It supports both light and dark modes based on system preferences.

## Key Features
- **Task Management**: Create, update, delete tasks with title, description, due date, priority, and completion status.
- **Data Persistence**: Task data stored in **Cloud Firestore**.
- **User Authentication**: Secure sign-in via **Firebase Authentication**.
- **Dark/Light Mode**: Adaptive UI based on device theme.

## Screenshots
![App Screenshots](images/todo-screenshots.png)

## Setup Instructions
1. Clone the repository.
2. Open in **Android Studio**.
3. Add `google-services.json` to the `app` directory.
4. Build & run on an emulator/device.

## References
- [Android Architecture Docs](https://developer.android.com/topic/architecture)
- [Firebase Setup Guide](https://firebase.google.com/docs/android/setup)
